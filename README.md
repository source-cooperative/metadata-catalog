# Source Cooperative Data Catalog

Each JSON file here is one STAC Collection for one Source Cooperative dataset.

## Layout

```
catalog/
  {publisher}/{product}.json          # 1:1 product = dataset (common case)
  {publisher}/{product}-{slug}.json   # sub-dataset within a multi-dataset product
  _keywords.jsonl                     # canonical keyword vocabulary
  _synonyms.json                      # observed-keyword → canonical map
  _log.jsonl                          # per-action pipeline log
```

Most Source Coop products map 1:1 to a catalog entry. Some products contain multiple distinct datasets (e.g. `harvard-lil/gov-data` is an archive of ~300k data.gov datasets). These get decomposed into separate entries as we encounter them.

## Identifiers

Every entry carries `account_id` and `product_id` as the first two project-specific fields, matching the directory layout. The STAC-required `id` field is set to `{account_id}/{product_id}` — globally unique across Source Cooperative.

## State funnel

Every entry has a `_state` field tracking pipeline progress:

| State | Written by | What's in the file |
|-------|-----------|--------------------|
| **seed** | `21-gen-seed` | Inventory aggregates (`file_count`, `total_bytes`, `exts`), API metadata (title, description, tags, mirrors, dates, visibility) |
| **orphan** | `21-gen-seed` | Inventory aggregates only; the bucket has this repo but the source.coop API does not. Dead-end; dashboard counts these. |
| **drafted** | `41-compose-collection` | Full STAC Collection assembled from cached README + probe + upstream STAC + AI synthesis |
| **reviewed** | (manual) | Human-confirmed; never overwritten by automation |

Locked states: `orphan`, `drafted`, `reviewed`. Gather and compose scripts refuse to clobber them. `--redraft` on compose bypasses `drafted` but not `reviewed` or `orphan`.

Entries only move forward. If an early-stage script is re-run against a later-state entry, it logs a `locked` line and exits 0.

## Gather caches (not in the entry)

Raw inputs collected by the gather stage live under `cache/`, not in the catalog entry. `compose_collection` reads these when assembling the final STAC:

```
cache/readme/{pub}/{prod}/<filename>     # README bytes (directory per repo)
cache/probe/{pub}/{prod}.jsonl           # probe summary (first line) + per-file
cache/stac/{pub}/{prod}/…                # upstream STAC doc(s) mirrored from S3
cache/ai/{pub}/{prod}.jsonl              # AI response cache (30-day TTL)
```

This keeps the catalog entries clean: `catalog.jsonl` is just `jq -c '.' catalog/*/*.json` with no strip step, because working data never landed in the entries in the first place. The top-level `readme` field (concatenated README text with path headers) is intentional — it supports full-text search over the compiled catalog.

## What counts as a separate dataset?

A dataset warrants its own catalog entry when:

- **Different provenance**: different original source, producer, or collection method
- **Independent extent**: could meaningfully have its own spatial and/or temporal bounds
- **Discoverable unit**: someone searching for data would expect it as a distinct result

This rubric is intentionally incomplete. We develop it case-by-case as we encounter ambiguous products. When in doubt, start with one entry per product and flag it for review.

### Known multi-dataset products

| Product | Situation | Status |
|---------|-----------|--------|
| `harvard-lil/gov-data` | ~300k data.gov archives in BagIt format | Not yet decomposed |

## Publishing model

These JSON files are the catalog's resting artifacts — work has been put into collecting, creating, cleaning, and verifying, but they're a best-effort record, not blessed by the data owner. We maintain `catalog/{publisher}/{product}.json` here; we do not push generated `collection.json` files back to the data buckets. At most, we offer a smaller version or backport to the repo owner, who uploads it themselves.

## Scripts

See `/pipeline.dot` at the repo root for the dependency graph and `/README.md` for usage. Libraries live in `scripts/lib/` (not runnable); numbered scripts (`NN-name.py`) are the pipeline stages.
