# Source Cooperative Data Catalog

Machine-readable metadata for every dataset published on
[Source Cooperative](https://source.coop) — one [STAC
Collection](https://github.com/radiantearth/stac-spec/blob/master/collection-spec/collection-spec.md)-shaped
JSON document per dataset, describing what it is, who made it, where it sits, what
licence it carries, and how big it is.

Entries are assembled from the Source Cooperative API, the data bucket's S3
inventory, the dataset's own README and STAC metadata, and an AI synthesis pass.
They are a best-effort record — see [Trust and provenance](#trust-and-provenance).

## Get the catalog

The whole catalog as one JSON-Lines file (one entry per line), rebuilt daily:

```bash
# stable "latest" URL, from the metadata-catalog GitHub release
curl -LO https://github.com/source-cooperative/metadata-catalog/releases/latest/download/catalog.jsonl

# or from Source Cooperative itself
curl -O https://data.source.coop/source/metadata-catalog/catalog.jsonl
```

```sql
-- e.g. every public dataset over 1 TB, largest first
SELECT id, title, total_bytes
FROM read_json_auto('catalog.jsonl', union_by_name = true)
WHERE _state = 'drafted' AND visibility = 'public' AND total_bytes > 1e12
ORDER BY total_bytes DESC;
```

The controlled keyword vocabulary ships alongside it as `_keywords.jsonl`
(`{term, freq, desc}` per line). Or clone this repo and read
`{account_id}/{product_id}.json` directly.

## Schema (v1)

Every entry carries a top-level integer `schema_version`. **1** is the current
version; an entry without the field is v1 from before the field existed. See
[Compatibility](#compatibility) for what bumps it.

Not every field is on every entry — a dataset the pipeline has only inventoried
(`_state: seed`) has counts but no STAC body. The **States** column below says
where a field appears: **all**, **seed** (`seed` + `unregistered`), or **full**
(`drafted` + `amended`, the entries with a composed STAC body).

### Identity

| Field | Type | States | Meaning |
|-------|------|--------|---------|
| `schema_version` | integer | all | Version of *this* schema. Currently `1`. |
| `id` | string | full | `{account_id}/{product_id}`. Globally unique across Source Cooperative. The STAC-required identifier. Absent on most seeds; construct it from the two fields below. |
| `account_id` | string | all | Publishing account (organization or individual), e.g. `kerner-lab`. |
| `product_id` | string | all | Product slug within that account, e.g. `fields-of-the-world-austria`. |

`{account_id}/{product_id}` is also this repo's directory layout, the dataset's
web page (`https://source.coop/{account_id}/{product_id}`), and its data prefix
(`https://data.source.coop/{account_id}/{product_id}/`).

### Description

| Field | Type | States | Meaning |
|-------|------|--------|---------|
| `title` | string | all but `unregistered` | Human-readable dataset name. |
| `description` | string | all but `unregistered` | 1–3 sentence summary of what the dataset *is*. AI-written from the README unless upstream STAC supplied one. |
| `keywords` | array of string | all but `unregistered` | Topical terms drawn from the shared vocabulary in `_keywords.jsonl`. |
| `license` | string | full, when known | SPDX identifier (`CC-BY-4.0`, `CC0-1.0`, …). **Omitted when the licence could not be established** — absence means unknown, not unlicensed. |
| `providers` | array of object | full | STAC providers: `{name, roles, url?}`, roles a subset of `producer`/`licensor`/`processor`/`host`. Source Cooperative is always present as `host`. A `role_uncertain: true` flag marks an inferred role. |
| `readme` | string | where a README was found | The dataset's README text, concatenated with path headers. Present so full-text search over `catalog.jsonl` works. |

### Extent and structure

| Field | Type | States | Meaning |
|-------|------|--------|---------|
| `type` | string | full | Always `"Collection"`. |
| `stac_version` | string | full | `"1.1.0"` (a few older entries still carry `"1.0.0"`). |
| `stac_extensions` | array of string | full, when tabular | Schema URLs for the STAC extensions in use — currently only the [Table extension](https://github.com/stac-extensions/table). |
| `extent` | object | full | `{spatial: {bbox: [[w,s,e,n]]}, temporal: {interval: [[start,end]]}}`. **Components are `null` when unknown**, so a bbox of `[null,null,null,null]` means "not established", not "empty". |
| `assets` | object | full | STAC assets keyed by name. Each has `href` (a `data.source.coop` URL), `type` (media type), `roles`, and for tabular data a `table:columns` list of `{name, type, description?}`. |
| `links` | array of object | full | STAC links: `self` (the collection doc), `via` (the Source Cooperative product page), `cite-as` (a DOI) when one is known. |
| `summaries` | object | full, when available | STAC summaries. `item_count` is the row/feature count when probing established one. |
| `table:columns` | array of object | full, when uniform | Collection-level column schema, hoisted here when every data asset shares it; per-asset schemas remain only where they genuinely differ. |
| `sci_citation`, `sci_doi` | string | sub-dataset entries | Citation string and DOI suffix when the source states one. |

### Size and contents

Derived from the data bucket's S3 inventory, refreshed on a weekly snapshot.

| Field | Type | States | Meaning |
|-------|------|--------|---------|
| `object_count` | integer | all | Number of S3 objects under the dataset's prefix. (Named `file_count` before schema v1.) |
| `objects_updated_at` | string \| null | all | ISO 8601 UTC timestamp of the most recently modified object — i.e. when the *data* last changed, as distinct from `updated_at`. |
| `total_bytes` | integer | all | Sum of object sizes. |
| `exts` | object | all | File extension → object count, e.g. `{"parquet": 4}`. Capped to the top extensions by count; the long tail of chunk-store pseudo-extensions is dropped, so this may not sum to `object_count`. |
| `ext_bytes` | object | seed | Extension → total bytes, same capping. |
| `store_format` | string \| null | all | Chunked-store format when the prefix holds one rather than discrete files: `zarr`, `icechunk`, `filegdb`, else `null`. |

### Access and hosting

Mirrored from the Source Cooperative product record.

| Field | Type | States | Meaning |
|-------|------|--------|---------|
| `visibility` | string | all but `unregistered` | `public`, `unlisted`, or `restricted`. |
| `data_mode` | string | all but `unregistered` | `open` for openly-licensed data. |
| `disabled` | boolean | all but `unregistered` | Product has been disabled by its owner or an admin. |
| `featured` | integer | all but `unregistered` | Non-zero if promoted on Source Cooperative. |
| `created_at`, `updated_at` | string \| null | all but `unregistered` | ISO 8601 timestamps for the **product record** — registration and last metadata edit. For data changes read `objects_updated_at`. |
| `mirrors` | object | all but `unregistered` | Storage locations keyed by connection id. Each: `{storage_type, is_primary, connection_id, config: {region, bucket}, prefix}`. The primary mirror's `prefix` is authoritative for where the data actually lives — it is not always `{account_id}/{product_id}/`. |

### Catalog-internal fields

Underscore-prefixed fields plus `cataloged_at` are the catalog's own bookkeeping.
Read `_state`; treat the rest as provenance you may inspect but should not depend
on — they change without a `schema_version` bump.

| Field | Type | Meaning |
|-------|------|---------|
| `_state` | string | Entry state — see [Entry states](#entry-states). The one field worth filtering on. |
| `cataloged_at` | string | ISO 8601 UTC timestamp of the last write to this entry. |
| `_source` | object | Which inputs produced the entry: `{source_coop_api, s3_inventory, api_status?, decomposed_readme?}`. |
| `_review` | array of string | Notes on what a human should verify — an unresolved licence, an inferred provider role, a missing bbox. Their presence is the honest signal that an entry is unconfirmed. |
| `_source_format` | string | Format of the upstream metadata document that was read: `stac`, `taco`, `unknown`. |
| `_amended` | object | `{ts, changed}` — what an additions-only refresh changed on a reviewed entry. |
| `_citation` | string | Publisher-asserted citation, held privately until a public field is standardized. |
| `_decomposed_from` | string | Parent `{account_id}/{product_id}` for a sub-dataset entry. |
| `_decompose_model`, `_decompose_prompt_version` | string, integer | Which model and prompt drafted a sub-dataset entry. |
| `_derived`, `_probe`, `_readme` | object | **Legacy.** Written by a retired drafting script; present on ~26 old entries, never written now. Ignore them. |

## Entry states

`_state` says how far an entry has come, and therefore how much to trust it.

| `_state` | What it means | What's in it |
|----------|---------------|--------------|
| `seed` | Inventoried and registered, not yet described. | Identity, product record, sizes. No STAC body. |
| `unregistered` | The bucket holds this prefix but Source Cooperative has no product for it. A dead end; counted, never described. | Identity and sizes only. |
| `drafted` | Fully composed. | Everything — STAC body, licence, extent, assets. Machine-generated; check `_review`. |
| `reviewed` | A human confirmed the drafted entry. | As `drafted`, verified. |
| `amended` | A `reviewed` entry whose sizes and extent were auto-refreshed after the data changed; editorial content untouched, awaiting re-review. | As `reviewed`, counts refreshed. |

Most consumers want `_state` in (`drafted`, `reviewed`, `amended`) — those are
the entries with a description, licence, and extent.

## Repository layout

```
{account_id}/{product_id}.json          # one dataset (the common case)
{account_id}/{product_id}-{slug}.json   # one dataset within a multi-dataset product
_keywords.jsonl                         # controlled keyword vocabulary: {term, freq, desc}
_synonyms.json                          # observed keyword → canonical term
_log.jsonl                              # append-only record of every pipeline action
_probe_issues.jsonl                     # open data-inspection issues, by dataset
_runs.jsonl                             # per-run health ledger
```

The `_*` ledgers are operational records, not part of the schema. `catalog.jsonl`
is a build artifact and is not committed here.

## What an entry is, and isn't

### Entries describe, they don't enumerate

A catalog entry describes the dataset; it never manifests every file or item in it (that scales to millions and belongs in the source's own `collection.json`). Compose keeps only semantic upstream links and drops `item`/`child` enumeration — we point at the source via `self`/`via` — and stores a partitioned table's `table:columns` once at the collection level, keeping per-asset only the schemas that genuinely differ.

### What counts as a separate dataset?

Most Source Coop products map 1:1 to a catalog entry. Some products contain multiple distinct datasets (e.g. `harvard-lil/gov-data` is an archive of ~300k data.gov datasets). These get decomposed into separate `{product_id}-{slug}` entries as we encounter them, each carrying `_decomposed_from`.

A dataset warrants its own catalog entry when:

- **Different provenance**: different original source, producer, or collection method
- **Independent extent**: could meaningfully have its own spatial and/or temporal bounds
- **Discoverable unit**: someone searching for data would expect it as a distinct result

This rubric is intentionally incomplete. We develop it case-by-case as we encounter ambiguous products. When in doubt, start with one entry per product and flag it for review.

### Trust and provenance

These JSON files are the catalog's resting artifacts — work has been put into collecting, creating, cleaning, and verifying, but they're a best-effort record, not blessed by the data owner. We maintain `{publisher}/{product}.json` here; we do not push generated `collection.json` files back to the data buckets. At most, we offer a smaller version or backport to the repo owner, who uploads it themselves.

Concretely: a `drafted` entry's description, keywords, licence and providers are
machine-derived from the dataset's own README. `_review` lists what the pipeline
itself flagged as uncertain. An omitted `license` means unknown.

## Compatibility

`schema_version` exists so a consumer can tell whether the shape changed under it.

**Bumps the version** — any change that can break a reader:

- renaming or removing a documented field
- changing a field's type, or the meaning of an existing value
- moving a field between levels of the document

**Does not bump the version:**

- adding a new field (readers must ignore unknown fields)
- adding a value to a documented set (`store_format`, `_state`, …), so match on
  the values you know and have a default branch
- anything under an underscore-prefixed field other than `_state`
- changes to the `_*.jsonl` ledgers

An entry with no `schema_version` is v1 — the field was introduced during v1 and
backfilled, but treat its absence as `1` rather than as an error.

### Changelog

| Version | Date | Changes |
|---------|------|---------|
| 1 | 2026-08 | First formalized schema. `schema_version` introduced and backfilled; `file_count` renamed to `object_count`; `objects_updated_at` added. |

---

The pipeline that produces this catalog lives in
[metadata-catalog-pipeline](https://github.com/source-cooperative/metadata-catalog-pipeline).
File issues about **data** (a wrong description, a missing licence) here; issues
about **how it's produced** there.
