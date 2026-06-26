# Source Cooperative catalog — status

_Updated 2026-06-26 19:08 UTC by the nightly pipeline._

**261 datasets cataloged**  ·  **20 queued for next run**  ·  last run handled **10**

## Last run

| outcome                       | count |
| ----------------------------- | ----: |
| ✅ drafted                     |    10 |
| ⏭️ incomplete (gap)           |     0 |
| ⚠️ probe failed (issue filed) |     0 |

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
| CATALOGED               |       257 |    2.6 PB |       |          |
|   drafted               |           |           |   257 |   2.6 PB |
| BACKLOG                 |        59 |  130.8 TB |       |          |
|   in s3, not yet seeded |           |           |    53 | 129.6 TB |
|   all_failed .icechunk  |           |           |     1 |   1.0 TB |
|   amended (no format)   |           |           |     1 |  65.7 GB |
|   all_failed .parquet   |           |           |     1 |  61.6 GB |
|   no_probe .fcb         |           |           |     2 |   4.2 GB |
|   all_failed .zarr      |           |           |     1 |   3.3 GB |
| SKIPPED                 |       195 |    1.1 PB |       |          |
|   not_geo               |           |           |    34 | 908.2 TB |
|   unlisted              |           |           |   133 | 148.1 TB |
|   test_repo             |           |           |     5 |   1.9 TB |
|   tiny                  |           |           |    23 |  31.2 KB |
| UNREGISTERED            |        39 |  924.2 TB |       |          |
|   stowaways             |           |           |    39 | 924.2 TB |
| S3 total                |       550 |    4.7 PB |       |          |

| subreport | meaning                                          | count |    bytes |
| --------- | ------------------------------------------------ | ----: | -------: |
| ghosts    | catalog entry, no S3 data                        |    43 |  29.7 TB |
| stowaways | S3 data, no source.coop product                  |    39 | 924.2 TB |
| stale     | catalog bytes ≠ S3 (fixed by `make process-all`) |    37 | 981.8 TB |
