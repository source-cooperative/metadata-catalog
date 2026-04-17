# Source Cooperative Data Catalog

Each JSON file in this directory represents one meaningful dataset stewarded by Source Cooperative.

## Layout

```
catalog/
  {publisher}/{product}.json          # 1:1 product = dataset (common case)
  {publisher}/{product}-{slug}.json   # sub-dataset within a multi-dataset product
```

Most Source Coop products map 1:1 to a catalog entry. Some products contain multiple distinct datasets (e.g. `harvard-lil/gov-data` is an archive of ~300k data.gov datasets). These get decomposed into separate entries as we encounter them.

## Phases

Every catalog entry has a `_state` field tracking where it is in the curation pipeline:

| State | What happened | What's in the file |
|-------|---------------|--------------------|
| **seed** | Created from S3 inventory + Source Coop API | `file_count`, `total_bytes`, `exts`, `title`, `description`, `keywords` (from API tags) |
| **gathered** | Automated tools fetched all available structured data | + STAC extent (bbox, temporal), README text, file structure analysis |
| **drafted** | AI synthesized gathered data into catalog-quality metadata | + cleaned description, license, providers, keywords, citation |
| **reviewed** | A human confirmed or corrected the metadata | All fields verified; ready for publication |

Entries only move forward. If a script re-runs, it should not overwrite a file that's already at a later phase (e.g. don't clobber a `reviewed` entry with `gathered` output).

## What counts as a separate dataset?

A dataset warrants its own catalog entry when:

- **Different provenance**: it comes from a different original source, producer, or collection method
- **Independent extent**: it could meaningfully have its own spatial and/or temporal bounds
- **Discoverable unit**: someone searching for data would expect to find it as a distinct result

This rubric is intentionally incomplete. We develop it case-by-case as we encounter ambiguous products. When in doubt, start with one entry per product and flag it for review.

### Known multi-dataset products

| Product | Situation | Status |
|---------|-----------|--------|
| `harvard-lil/gov-data` | ~300k data.gov archives in BagIt format | Not yet decomposed |

## AI Response Cache

AI-generated metadata is expensive. Cached responses live in:

```
cache/ai/{publisher}/{product}.jsonl
```

Each line is a JSON object with a `_ts` timestamp. New responses are appended; the latest response is always the last line (`tail -1`). The `--refresh` flag forces a new AI call and appends the result.

## Scripts

| Script | Purpose |
|--------|---------|
| `gen_stubs.py` | Generate `seed` stubs from `cache/s3inv/repo_metadata.jsonl` |
| `gen_collection.py` | Generate a rich STAC Collection for one repo (gather + draft) |
