# Source Cooperative catalog — status

_Updated 2026-06-17 18:39 UTC by the nightly pipeline._

**261 datasets cataloged**  ·  **31 queued for next run**  ·  last run handled **25**

## Last run

| outcome                       | count |
| ----------------------------- | ----: |
| ✅ drafted                     |    20 |
| ⏭️ incomplete (gap)           |     2 |
| ⚠️ probe failed (issue filed) |     3 |

Failed: bkr/cams, cboettig/obis, dynamical/dwd-icon-eu-forecast-5-day — see [open probe-failure issues](https://github.com/source-cooperative/metadata-catalog/issues?q=is%3Aissue+is%3Aopen+label%3Aprobe-failure).

## Needs a prober (no_probe)

| format   | datasets                   |
| -------- | -------------------------- |
| .fcb     | 2 datasets                 |
| .fgb     | smartmaps/next-ksj         |
| .geojson | geovibes/geometries        |
| .nc      | 2 datasets                 |
| .pmtiles | 4 datasets                 |
| .shp     | cboettig/habitat-corridors |

| group                   | agg count | agg bytes | count |    bytes |
| ----------------------- | --------: | --------: | ----: | -------: |
| CATALOGED               |       257 |    2.5 PB |       |          |
|   drafted               |           |           |   257 |   2.5 PB |
| BACKLOG                 |        32 |   42.5 TB |       |          |
|   in s3, not yet seeded |           |           |    26 |  41.3 TB |
|   all_failed .icechunk  |           |           |     1 |   1.0 TB |
|   amended (no format)   |           |           |     1 |  65.7 GB |
|   all_failed .parquet   |           |           |     1 |  61.6 GB |
|   no_probe .fcb         |           |           |     2 |   4.2 GB |
|   all_failed .zarr      |           |           |     1 |   3.3 GB |
| SKIPPED                 |       195 |    1.1 PB |       |          |
|   not_geo               |           |           |    35 | 901.8 TB |
|   unlisted              |           |           |   133 | 148.1 TB |
|   test_repo             |           |           |     5 |   1.9 TB |
|   tiny                  |           |           |    22 |  30.6 KB |
| UNREGISTERED            |        39 |  923.7 TB |       |          |
|   stowaways             |           |           |    39 | 923.7 TB |
| S3 total                |       523 |    4.5 PB |       |          |

| subreport | meaning                                          | count |    bytes |
| --------- | ------------------------------------------------ | ----: | -------: |
| ghosts    | catalog entry, no S3 data                        |    43 |  29.7 TB |
| stowaways | S3 data, no source.coop product                  |    39 | 923.7 TB |
| stale     | catalog bytes ≠ S3 (fixed by `make process-all`) |    44 |   1.0 PB |
