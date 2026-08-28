# Source Cooperative catalog — status

_Updated 2026-08-28 12:39 UTC by the nightly pipeline._

**402 datasets cataloged**  ·  **42 queued for next run**  ·  last run handled **10**

## Last run

<details><summary>✅ drafted — 10 datasets</summary>

| repo                                                                                             |
| ------------------------------------------------------------------------------------------------ |
| [bkr/geos](https://source.coop/bkr/geos)                                                         |
| [cboettig/land-cover](https://source.coop/cboettig/land-cover)                                   |
| [cboettig/rap](https://source.coop/cboettig/rap)                                                 |
| [dynamical/ecmwf-aifs-single-forecast](https://source.coop/dynamical/ecmwf-aifs-single-forecast) |
| [dynamical/noaa-hrrr-forecast-48-hour](https://source.coop/dynamical/noaa-hrrr-forecast-48-hour) |
| [harvard-lil/smithsonian-open-access](https://source.coop/harvard-lil/smithsonian-open-access)   |
| [planet/disasterdata](https://source.coop/planet/disasterdata)                                   |
| [root-geospatial/flight-tracks](https://source.coop/root-geospatial/flight-tracks)               |
| [smartmaps/japan-geotiff-dem](https://source.coop/smartmaps/japan-geotiff-dem)                   |
| [walkthru-earth/indices](https://source.coop/walkthru-earth/indices)                             |

</details>


## Recent runs

| run                                                                                                    | outcome     |    drafted | manual resets | failed | queued | cataloged |
| ------------------------------------------------------------------------------------------------------ | ----------- | ---------: | ------------: | -----: | -----: | --------: |
| [2026-08-28](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/33170171623) | ✅ success   | 10 (10 re) |               |      0 |     42 |       402 |
| [2026-08-27](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/33069036341) | ✅ success   |  10 (1 re) |            10 |      0 |     52 |       402 |
| [2026-08-26](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/33023409593) | ❌ cancelled |          0 |               |      0 |   None |       403 |
| [2026-08-26](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/33020335868) | ✅ success   |          0 |               |      0 |      1 |       403 |
| [2026-08-26](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/33016907154) | ✅ success   |          0 |               |      0 |      1 |       403 |
| [2026-08-26](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/32948543871) | ✅ success   |   9 (9 re) |               |      0 |     48 |       403 |
| [2026-08-25](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/32827398611) | ✅ success   |  10 (4 re) |               |      0 |     62 |       403 |

## Persistent failures

**1 dataset failing**  ·  1 open issue  ·  oldest **6d**  ·  **0** ≥30d  ·  [all open issues](https://github.com/source-cooperative/metadata-catalog/issues?q=is%3Aissue+is%3Aopen+label%3Aprobe-failure)

<details><summary>the 1 open issues, oldest first</summary>

| repo                                                                               | age (d) |                                                                     issue |
| ---------------------------------------------------------------------------------- | ------: | ------------------------------------------------------------------------: |
| [wadhwani-ai/wiai-pm-open-data](https://source.coop/wadhwani-ai/wiai-pm-open-data) |       6 | [#155](https://github.com/source-cooperative/metadata-catalog/issues/155) |

</details>

## Perpetual gaps

**1 dataset** re-queued every run without progress — each retry fetched the repo's keys and hit the same gap.

| repo                                               | gap                 | runs | since      | retries                     |
| -------------------------------------------------- | ------------------- | ---: | ---------- | --------------------------- |
| [cboettig/obis](https://source.coop/cboettig/obis) | all_failed .parquet |   21 | 2026-04-24 | backed off until 2026-09-20 |

## 13 datasets need a prober

<details><summary>by format — ranked by bytes unlocked if built</summary>

<details><summary>.zip — 5 datasets · 18.0 TB</summary>

| repo                                                                                                                           |   bytes |
| ------------------------------------------------------------------------------------------------------------------------------ | ------: |
| [harvard-lil/gov-data](https://source.coop/harvard-lil/gov-data)                                                               | 17.9 TB |
| [cboettig/usgs-nhd](https://source.coop/cboettig/usgs-nhd)                                                                     | 49.7 GB |
| [taco/darktom](https://source.coop/taco/darktom)                                                                               |  3.0 GB |
| [symbotic-computing-lab/chesapeake-land-cover-subset](https://source.coop/symbotic-computing-lab/chesapeake-land-cover-subset) |  2.2 GB |
| [asterisk-labs/cozip](https://source.coop/asterisk-labs/cozip)                                                                 | 98.5 KB |

</details>

<details><summary>.mkv — 1 dataset · 10.9 GB</summary>

| repo                                                                                                   |   bytes |
| ------------------------------------------------------------------------------------------------------ | ------: |
| [dataforcanada/d4c-datapkg-field-imagery](https://source.coop/dataforcanada/d4c-datapkg-field-imagery) | 10.9 GB |

</details>

<details><summary>.gndc — 1 dataset · 720.9 MB</summary>

| repo                                                                     |    bytes |
| ------------------------------------------------------------------------ | -------: |
| [jianbo/gndc-higlass-ls20](https://source.coop/jianbo/gndc-higlass-ls20) | 720.9 MB |

</details>

<details><summary>.json — 5 datasets · 329.4 MB</summary>

| repo                                                                                               |    bytes |
| -------------------------------------------------------------------------------------------------- | -------: |
| [troyschmidt/hurrevac-storm-advisories](https://source.coop/troyschmidt/hurrevac-storm-advisories) | 321.4 MB |
| [fiboa/br-ba-lem](https://source.coop/fiboa/br-ba-lem)                                             |   7.3 MB |
| [youssef-harby/overture-maps-stac](https://source.coop/youssef-harby/overture-maps-stac)           | 718.0 KB |
| [fish-pace/chla-z](https://source.coop/fish-pace/chla-z)                                           |  12.0 KB |
| [cboettig/glen](https://source.coop/cboettig/glen)                                                 |  10.9 KB |

</details>

<details><summary>(no format) — 1 dataset · 75.7 MB</summary>

| repo                                                                   |   bytes |
| ---------------------------------------------------------------------- | ------: |
| [pangeo/geozarr-examples](https://source.coop/pangeo/geozarr-examples) | 75.7 MB |

</details>

</details>

## Catalog funnel

_Each bucket links to its datasets under [Datasets per category](#datasets-per-category)._

| group                       | agg count | agg bytes | count |    bytes |
| --------------------------- | --------: | --------: | ----: | -------: |
| [CATALOGED](#cataloged)     |       361 |    4.2 PB |       |          |
|   drafted                   |           |           |   361 |   4.2 PB |
| [BACKLOG](#backlog)         |         4 |  219.1 GB |       |          |
|   all_failed .jpg           |           |           |     1 |  91.8 GB |
|   amended (no format)       |           |           |     1 |  65.7 GB |
|   all_failed .parquet       |           |           |     1 |  61.6 GB |
|   in s3, not yet seeded     |           |           |     1 |    3.0 B |
| [SKIPPED](#skipped)         |       205 |    1.8 PB |       |          |
|   unlisted                  |           |           |   162 |   1.8 PB |
|   no_prober                 |           |           |    11 |  18.0 TB |
|   test_repo                 |           |           |     7 |   2.0 TB |
|   tiny                      |           |           |    25 |  33.4 KB |
| [UNREGISTERED](#mismatches) |        42 |  951.4 TB |       |          |
|   stowaways                 |           |           |    42 | 951.4 TB |
| S3 total                    |       612 |    6.9 PB |       |          |

## Datasets per category

_Each entry expands to the datasets counted in it (collapsed by default)._

### CATALOGED

<details><summary>drafted — 361 datasets (4.2 PB)</summary>

| repo                                                                                                                                                 |    bytes |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------: |
| [harvard-lil/smithsonian-open-access](https://source.coop/harvard-lil/smithsonian-open-access)                                                       | 851.1 TB |
| [tge-labs/aef](https://source.coop/tge-labs/aef)                                                                                                     | 576.6 TB |
| [tge-labs/aef-mosaic](https://source.coop/tge-labs/aef-mosaic)                                                                                       | 552.9 TB |
| [bkr/icon](https://source.coop/bkr/icon)                                                                                                             | 335.0 TB |
| [bkr/geo](https://source.coop/bkr/geo)                                                                                                               | 224.8 TB |
| [dynamical/noaa-gefs-forecast-35-day](https://source.coop/dynamical/noaa-gefs-forecast-35-day)                                                       | 211.3 TB |
| [dynamical/ecmwf-ifs-grib](https://source.coop/dynamical/ecmwf-ifs-grib)                                                                             | 201.7 TB |
| [earthgenome/earthindeximagery](https://source.coop/earthgenome/earthindeximagery)                                                                   | 171.2 TB |
| [govscape/eota-pdf-archive](https://source.coop/govscape/eota-pdf-archive)                                                                           | 107.3 TB |
| [geoai-ucph/gvsm](https://source.coop/geoai-ucph/gvsm)                                                                                               | 101.7 TB |
| [earthgenome/sentinel2-temporal-mosaics](https://source.coop/earthgenome/sentinel2-temporal-mosaics)                                                 |  76.3 TB |
| [cworthy/dor-efficiency-atlas](https://source.coop/cworthy/dor-efficiency-atlas)                                                                     |  74.1 TB |
| [bkr/metoffice](https://source.coop/bkr/metoffice)                                                                                                   |  61.7 TB |
| [cworthy/oae-efficiency-atlas](https://source.coop/cworthy/oae-efficiency-atlas)                                                                     |  56.6 TB |
| [dynamical/ecmwf-ifs-ens-forecast-15-day-0-25-degree](https://source.coop/dynamical/ecmwf-ifs-ens-forecast-15-day-0-25-degree)                       |  48.7 TB |
| [dynamical/dwd-icon-grib](https://source.coop/dynamical/dwd-icon-grib)                                                                               |  48.5 TB |
| [agentmorris/lila-wildlife](https://source.coop/agentmorris/lila-wildlife)                                                                           |  43.3 TB |
| [bkr/geos](https://source.coop/bkr/geos)                                                                                                             |  39.0 TB |
| [bkr/ifs](https://source.coop/bkr/ifs)                                                                                                               |  37.3 TB |
| [dynamical/noaa-gfs-forecast](https://source.coop/dynamical/noaa-gfs-forecast)                                                                       |  29.1 TB |
| [mapterhorn/mapterhorn](https://source.coop/mapterhorn/mapterhorn)                                                                                   |  26.7 TB |
| [bkr/silam-dust](https://source.coop/bkr/silam-dust)                                                                                                 |  26.1 TB |
| [bkr/dmi](https://source.coop/bkr/dmi)                                                                                                               |  25.4 TB |
| [tge-labs/meta-chm-v2](https://source.coop/tge-labs/meta-chm-v2)                                                                                     |  23.8 TB |
| [carbonplan/carbonplan-ocr](https://source.coop/carbonplan/carbonplan-ocr)                                                                           |  20.8 TB |
| [dataforcanada/d4c-datapkg-orthoimagery](https://source.coop/dataforcanada/d4c-datapkg-orthoimagery)                                                 |  16.0 TB |
| [fused/overture](https://source.coop/fused/overture)                                                                                                 |  13.8 TB |
| [dynamical/noaa-hrrr-forecast-48-hour](https://source.coop/dynamical/noaa-hrrr-forecast-48-hour)                                                     |  13.0 TB |
| [bkr/marine](https://source.coop/bkr/marine)                                                                                                         |  12.1 TB |
| [bkr/polar](https://source.coop/bkr/polar)                                                                                                           |  10.9 TB |
| [clay/lgnd-embeddings](https://source.coop/clay/lgnd-embeddings)                                                                                     |   9.6 TB |
| [earthgenome/earthindexembeddings](https://source.coop/earthgenome/earthindexembeddings)                                                             |   8.5 TB |
| [bkr/precipradar](https://source.coop/bkr/precipradar)                                                                                               |   7.4 TB |
| [clay/clay-v1-5-naip-2](https://source.coop/clay/clay-v1-5-naip-2)                                                                                   |   6.6 TB |
| [bkr/mrms](https://source.coop/bkr/mrms)                                                                                                             |   6.6 TB |
| [wherobots/fields-of-the-world](https://source.coop/wherobots/fields-of-the-world)                                                                   |   5.4 TB |
| [malariaatlas/lst](https://source.coop/malariaatlas/lst)                                                                                             |   5.3 TB |
| [auspatious/geomad-sids](https://source.coop/auspatious/geomad-sids)                                                                                 |   4.5 TB |
| [ausantarctic/ghrsst-mur-v2](https://source.coop/ausantarctic/ghrsst-mur-v2)                                                                         |   4.3 TB |
| [major-tom/elliot-pretrain](https://source.coop/major-tom/elliot-pretrain)                                                                           |   4.2 TB |
| [bkr/gmgi](https://source.coop/bkr/gmgi)                                                                                                             |   4.0 TB |
| [dataforcanada/d4c-datapkg-web-corpus](https://source.coop/dataforcanada/d4c-datapkg-web-corpus)                                                     |   4.0 TB |
| [bkr/imerg](https://source.coop/bkr/imerg)                                                                                                           |   4.0 TB |
| [bkr/gfs](https://source.coop/bkr/gfs)                                                                                                               |   3.8 TB |
| [vida/google-microsoft-open-buildings](https://source.coop/vida/google-microsoft-open-buildings)                                                     |   3.6 TB |
| [vida/google-microsoft-osm-open-buildings](https://source.coop/vida/google-microsoft-osm-open-buildings)                                             |   2.8 TB |
| [malariaatlas/tcw](https://source.coop/malariaatlas/tcw)                                                                                             |   2.7 TB |
| [malariaatlas/tcb](https://source.coop/malariaatlas/tcb)                                                                                             |   2.7 TB |
| [malariaatlas/evi](https://source.coop/malariaatlas/evi)                                                                                             |   2.6 TB |
| [dynamical/ecmwf-aifs-single-forecast](https://source.coop/dynamical/ecmwf-aifs-single-forecast)                                                     |   2.0 TB |
| [major-tom/core](https://source.coop/major-tom/core)                                                                                                 |   1.9 TB |
| [root-geospatial/flight-tracks](https://source.coop/root-geospatial/flight-tracks)                                                                   |   1.5 TB |
| [englacial/ismip6](https://source.coop/englacial/ismip6)                                                                                             |   1.3 TB |
| [smartmaps/japan-seamlessphoto](https://source.coop/smartmaps/japan-seamlessphoto)                                                                   |   1.2 TB |
| [dynamical/noaa-gefs-analysis](https://source.coop/dynamical/noaa-gefs-analysis)                                                                     |   1.1 TB |
| [bkr/cams](https://source.coop/bkr/cams)                                                                                                             |   1.0 TB |
| [wildland-almanac/conus](https://source.coop/wildland-almanac/conus)                                                                                 |   1.0 TB |
| [wildland-almanac/treatment-scenarios](https://source.coop/wildland-almanac/treatment-scenarios)                                                     | 894.7 GB |
| [taco/3dclouds](https://source.coop/taco/3dclouds)                                                                                                   | 832.5 GB |
| [walkthru-earth/dem-terrain](https://source.coop/walkthru-earth/dem-terrain)                                                                         | 831.4 GB |
| [cholmes/overture](https://source.coop/cholmes/overture)                                                                                             | 779.1 GB |
| [smartmaps/xing](https://source.coop/smartmaps/xing)                                                                                                 | 748.1 GB |
| [dynamical/noaa-gfs-analysis](https://source.coop/dynamical/noaa-gfs-analysis)                                                                       | 658.3 GB |
| [walkthru-earth/indices](https://source.coop/walkthru-earth/indices)                                                                                 | 638.4 GB |
| [bkr/nsrdb](https://source.coop/bkr/nsrdb)                                                                                                           | 636.9 GB |
| [geospatialml/terrabit](https://source.coop/geospatialml/terrabit)                                                                                   | 626.2 GB |
| [wildland-almanac/california](https://source.coop/wildland-almanac/california)                                                                       | 557.5 GB |
| [earthgenome/food-twin](https://source.coop/earthgenome/food-twin)                                                                                   | 544.1 GB |
| [fika/waternet](https://source.coop/fika/waternet)                                                                                                   | 527.0 GB |
| [dataforcanada/d4c-datapkg-elevation](https://source.coop/dataforcanada/d4c-datapkg-elevation)                                                       | 526.0 GB |
| [kylebarron/usgs-landcover](https://source.coop/kylebarron/usgs-landcover)                                                                           | 506.5 GB |
| [clay/lgnd-clay-v1-5-sentinel-2-l2a](https://source.coop/clay/lgnd-clay-v1-5-sentinel-2-l2a)                                                         | 503.2 GB |
| [protomaps/openstreetmap](https://source.coop/protomaps/openstreetmap)                                                                               | 488.7 GB |
| [smartmaps/cogenerate](https://source.coop/smartmaps/cogenerate)                                                                                     | 427.7 GB |
| [giswqs/tn-imagery](https://source.coop/giswqs/tn-imagery)                                                                                           | 412.5 GB |
| [bkr/weatherreal](https://source.coop/bkr/weatherreal)                                                                                               | 399.2 GB |
| [abry-tudelft/eubucco](https://source.coop/abry-tudelft/eubucco)                                                                                     | 395.2 GB |
| [smartmaps/japan-geotiff-dem](https://source.coop/smartmaps/japan-geotiff-dem)                                                                       | 376.7 GB |
| [englacial/zagg](https://source.coop/englacial/zagg)                                                                                                 | 358.8 GB |
| [geovibes/search](https://source.coop/geovibes/search)                                                                                               | 330.6 GB |
| [eco4cast/neon4cast-forecasts](https://source.coop/eco4cast/neon4cast-forecasts)                                                                     | 330.1 GB |
| [taco/methaneset](https://source.coop/taco/methaneset)                                                                                               | 325.0 GB |
| [bkr/err](https://source.coop/bkr/err)                                                                                                               | 288.6 GB |
| [dynamical/noaa-mrms-conus-analysis-hourly](https://source.coop/dynamical/noaa-mrms-conus-analysis-hourly)                                           | 252.4 GB |
| [smartmaps/ngs](https://source.coop/smartmaps/ngs)                                                                                                   | 232.0 GB |
| [tge-labs/globalbuildingatlas-lod1](https://source.coop/tge-labs/globalbuildingatlas-lod1)                                                           | 224.7 GB |
| [cboettig/land-cover](https://source.coop/cboettig/land-cover)                                                                                       | 221.3 GB |
| [tge-labs/openbuildingmap](https://source.coop/tge-labs/openbuildingmap)                                                                             | 208.3 GB |
| [smartmaps/gel](https://source.coop/smartmaps/gel)                                                                                                   | 196.0 GB |
| [cboettig/carbon](https://source.coop/cboettig/carbon)                                                                                               | 170.8 GB |
| [cboettig/gbif](https://source.coop/cboettig/gbif)                                                                                                   | 169.0 GB |
| [rseg/sentinel1-lfmc](https://source.coop/rseg/sentinel1-lfmc)                                                                                       | 168.3 GB |
| [pfrost/climacell-monthly](https://source.coop/pfrost/climacell-monthly)                                                                             | 162.4 GB |
| [planet/disasterdata](https://source.coop/planet/disasterdata)                                                                                       | 155.1 GB |
| [giswqs/giw](https://source.coop/giswqs/giw)                                                                                                         | 146.6 GB |
| [dataforcanada/d4c-datapkg-statistical](https://source.coop/dataforcanada/d4c-datapkg-statistical)                                                   | 134.1 GB |
| [nlebovits/phl-aerial-imagery](https://source.coop/nlebovits/phl-aerial-imagery)                                                                     | 129.6 GB |
| [hdx/google-open-buildings](https://source.coop/hdx/google-open-buildings)                                                                           | 123.4 GB |
| [wherobots/usa-structures](https://source.coop/wherobots/usa-structures)                                                                             | 122.5 GB |
| [kerner-lab/fields-of-the-world](https://source.coop/kerner-lab/fields-of-the-world)                                                                 | 120.8 GB |
| [cboettig/wetlands](https://source.coop/cboettig/wetlands)                                                                                           | 109.7 GB |
| [hdx/microsoft-open-buildings](https://source.coop/hdx/microsoft-open-buildings)                                                                     | 105.1 GB |
| [alexgleith/tasmania-dem-2m](https://source.coop/alexgleith/tasmania-dem-2m)                                                                         |  95.2 GB |
| [pacificspatial/field-polygon-jp](https://source.coop/pacificspatial/field-polygon-jp)                                                               |  94.8 GB |
| [englacial/demogorgn](https://source.coop/englacial/demogorgn)                                                                                       |  93.0 GB |
| [cholmes/portolan-nl](https://source.coop/cholmes/portolan-nl)                                                                                       |  83.6 GB |
| [giswqs/nwi](https://source.coop/giswqs/nwi)                                                                                                         |  82.4 GB |
| [planet/venezuela-earthquake-2026-06-24](https://source.coop/planet/venezuela-earthquake-2026-06-24)                                                 |  74.0 GB |
| [youssef-harby/egms-copernicus](https://source.coop/youssef-harby/egms-copernicus)                                                                   |  73.0 GB |
| [nlebovits/jrc-glofas](https://source.coop/nlebovits/jrc-glofas)                                                                                     |  70.8 GB |
| [vizzuality/hfp-100](https://source.coop/vizzuality/hfp-100)                                                                                         |  70.4 GB |
| [cboettig/overturemaps](https://source.coop/cboettig/overturemaps)                                                                                   |  64.6 GB |
| [cboettig/rap](https://source.coop/cboettig/rap)                                                                                                     |  63.4 GB |
| [pacificspatial/flateau](https://source.coop/pacificspatial/flateau)                                                                                 |  63.3 GB |
| [planet/rapidcrops](https://source.coop/planet/rapidcrops)                                                                                           |  62.6 GB |
| [csaybar/methaneset](https://source.coop/csaybar/methaneset)                                                                                         |  62.2 GB |
| [avikertesz/002](https://source.coop/avikertesz/002)                                                                                                 |  61.4 GB |
| [planet/eu-field-boundaries](https://source.coop/planet/eu-field-boundaries)                                                                         |  61.3 GB |
| [fused/fsq-os-places](https://source.coop/fused/fsq-os-places)                                                                                       |  60.3 GB |
| [bkr/aoml](https://source.coop/bkr/aoml)                                                                                                             |  55.7 GB |
| [dataforcanada/d4c-datapkg-foundation](https://source.coop/dataforcanada/d4c-datapkg-foundation)                                                     |  52.8 GB |
| [cboettig/nc-frontiers](https://source.coop/cboettig/nc-frontiers)                                                                                   |  52.0 GB |
| [fiboa/data](https://source.coop/fiboa/data)                                                                                                         |  49.9 GB |
| [cboettig/usgs-nhd](https://source.coop/cboettig/usgs-nhd)                                                                                           |  49.7 GB |
| [cboettig/high-seas](https://source.coop/cboettig/high-seas)                                                                                         |  47.3 GB |
| [reflective/geomipzarr](https://source.coop/reflective/geomipzarr)                                                                                   |  47.3 GB |
| [tge-labs/mgrs](https://source.coop/tge-labs/mgrs)                                                                                                   |  45.6 GB |
| [planet/skyscraper](https://source.coop/planet/skyscraper)                                                                                           |  44.6 GB |
| [cboettig/census](https://source.coop/cboettig/census)                                                                                               |  42.8 GB |
| [cboettig/hazard](https://source.coop/cboettig/hazard)                                                                                               |  40.7 GB |
| [cboettig/padus](https://source.coop/cboettig/padus)                                                                                                 |  35.2 GB |
| [henryspatialanalysis/openpois](https://source.coop/henryspatialanalysis/openpois)                                                                   |  34.5 GB |
| [cboettig/population](https://source.coop/cboettig/population)                                                                                       |  32.8 GB |
| [ganzk/lcms](https://source.coop/ganzk/lcms)                                                                                                         |  28.8 GB |
| [giswqs/depressions](https://source.coop/giswqs/depressions)                                                                                         |  27.6 GB |
| [hdx/cod-ab](https://source.coop/hdx/cod-ab)                                                                                                         |  27.3 GB |
| [ybyra-br/secondary-forest](https://source.coop/ybyra-br/secondary-forest)                                                                           |  26.6 GB |
| [smartmaps/foil4gr1](https://source.coop/smartmaps/foil4gr1)                                                                                         |  25.0 GB |
| [cboettig/pad-us-3](https://source.coop/cboettig/pad-us-3)                                                                                           |  21.9 GB |
| [seerai/hifld](https://source.coop/seerai/hifld)                                                                                                     |  21.6 GB |
| [dynamical/asos-parquet](https://source.coop/dynamical/asos-parquet)                                                                                 |  20.2 GB |
| [cboettig/indigenous](https://source.coop/cboettig/indigenous)                                                                                       |  20.2 GB |
| [opengeos/geoai](https://source.coop/opengeos/geoai)                                                                                                 |  19.4 GB |
| [giswqs/opengeos](https://source.coop/giswqs/opengeos)                                                                                               |  19.2 GB |
| [nlebovits/ghsl](https://source.coop/nlebovits/ghsl)                                                                                                 |  19.0 GB |
| [clarkcga/hls-multi-temporal-cloud-gap-imputation](https://source.coop/clarkcga/hls-multi-temporal-cloud-gap-imputation)                             |  18.1 GB |
| [giswqs/playa](https://source.coop/giswqs/playa)                                                                                                     |  17.8 GB |
| [ftw/ftw-grid](https://source.coop/ftw/ftw-grid)                                                                                                     |  17.8 GB |
| [geovibes/embeddings](https://source.coop/geovibes/embeddings)                                                                                       |  17.5 GB |
| [vizzuality/lg-land-carbon-data](https://source.coop/vizzuality/lg-land-carbon-data)                                                                 |  17.2 GB |
| [youssef-harby/exiobase-3](https://source.coop/youssef-harby/exiobase-3)                                                                             |  16.3 GB |
| [smartmaps/amx-2024-04](https://source.coop/smartmaps/amx-2024-04)                                                                                   |  16.2 GB |
| [cboettig/sahara-trees](https://source.coop/cboettig/sahara-trees)                                                                                   |  15.7 GB |
| [cboettig/facts](https://source.coop/cboettig/facts)                                                                                                 |  15.1 GB |
| [nlebovits/microsoft-ml-road-detections](https://source.coop/nlebovits/microsoft-ml-road-detections)                                                 |  14.8 GB |
| [tristangruppwri/mapbiomas](https://source.coop/tristangruppwri/mapbiomas)                                                                           |  14.7 GB |
| [youssef-harby/geoparquet-overviews](https://source.coop/youssef-harby/geoparquet-overviews)                                                         |  14.7 GB |
| [zluo43/citibike](https://source.coop/zluo43/citibike)                                                                                               |  14.1 GB |
| [ganzk/vodca](https://source.coop/ganzk/vodca)                                                                                                       |  13.4 GB |
| [cboettig/social-vulnerability](https://source.coop/cboettig/social-vulnerability)                                                                   |  13.0 GB |
| [cboettig/usgs-wbd](https://source.coop/cboettig/usgs-wbd)                                                                                           |  12.1 GB |
| [planet/agroforestry-individual-tree-detection-india](https://source.coop/planet/agroforestry-individual-tree-detection-india)                       |  11.3 GB |
| [ausantarctic/gebco](https://source.coop/ausantarctic/gebco)                                                                                         |  11.1 GB |
| [planet/philippines-earthquake-2026-06-08](https://source.coop/planet/philippines-earthquake-2026-06-08)                                             |  10.3 GB |
| [terrafloww/aef-v1-annual-rasteret](https://source.coop/terrafloww/aef-v1-annual-rasteret)                                                           |   8.6 GB |
| [eco4cast/neon4cast-scores](https://source.coop/eco4cast/neon4cast-scores)                                                                           |   7.7 GB |
| [clarkcga/multi-temporal-crop-classification](https://source.coop/clarkcga/multi-temporal-crop-classification)                                       |   7.2 GB |
| [nlebovits/moldova-geodata](https://source.coop/nlebovits/moldova-geodata)                                                                           |   7.0 GB |
| [fiboa/japan](https://source.coop/fiboa/japan)                                                                                                       |   6.7 GB |
| [pacificspatial/vegetation-jp](https://source.coop/pacificspatial/vegetation-jp)                                                                     |   6.7 GB |
| [cboettig/inat](https://source.coop/cboettig/inat)                                                                                                   |   6.5 GB |
| [fiboa/france-ec](https://source.coop/fiboa/france-ec)                                                                                               |   6.5 GB |
| [fish-pace/gobai-o2](https://source.coop/fish-pace/gobai-o2)                                                                                         |   5.6 GB |
| [planet/agroforestry-tree-species-identification-india](https://source.coop/planet/agroforestry-tree-species-identification-india)                   |   5.5 GB |
| [fiboa/us-usda-cropland](https://source.coop/fiboa/us-usda-cropland)                                                                                 |   5.3 GB |
| [rsignell/ncei-estuarine-bathymetry](https://source.coop/rsignell/ncei-estuarine-bathymetry)                                                         |   5.3 GB |
| [fish-pace/globcolour](https://source.coop/fish-pace/globcolour)                                                                                     |   5.2 GB |
| [alexgleith/gebco-2024](https://source.coop/alexgleith/gebco-2024)                                                                                   |   4.6 GB |
| [fish-pace/pace-oci](https://source.coop/fish-pace/pace-oci)                                                                                         |   4.5 GB |
| [cboettig/fishbase](https://source.coop/cboettig/fishbase)                                                                                           |   4.3 GB |
| [fiboa/es-cl](https://source.coop/fiboa/es-cl)                                                                                                       |   4.2 GB |
| [caires-tudelft/plateau-tokyo-fcb-2](https://source.coop/caires-tudelft/plateau-tokyo-fcb-2)                                                         |   4.1 GB |
| [fused/hex](https://source.coop/fused/hex)                                                                                                           |   3.6 GB |
| [tristangruppwri/cadastral](https://source.coop/tristangruppwri/cadastral)                                                                           |   3.6 GB |
| [clay/clay-model-v0-embeddings](https://source.coop/clay/clay-model-v0-embeddings)                                                                   |   3.6 GB |
| [fiboa/at-crop](https://source.coop/fiboa/at-crop)                                                                                                   |   3.4 GB |
| [fiboa/es-cm](https://source.coop/fiboa/es-cm)                                                                                                       |   3.4 GB |
| [dynamical/dwd-icon-eu-forecast-5-day](https://source.coop/dynamical/dwd-icon-eu-forecast-5-day)                                                     |   3.3 GB |
| [ftw/harmonized-field-data](https://source.coop/ftw/harmonized-field-data)                                                                           |   3.3 GB |
| [jrc-lucas/jrc-lucas-ml](https://source.coop/jrc-lucas/jrc-lucas-ml)                                                                                 |   3.3 GB |
| [cboettig/ecoregion](https://source.coop/cboettig/ecoregion)                                                                                         |   3.3 GB |
| [cboettig/fire](https://source.coop/cboettig/fire)                                                                                                   |   3.2 GB |
| [fiboa/es-vc](https://source.coop/fiboa/es-vc)                                                                                                       |   3.2 GB |
| [nlebovits/eurosat-ms](https://source.coop/nlebovits/eurosat-ms)                                                                                     |   3.2 GB |
| [englacial/bedmap](https://source.coop/englacial/bedmap)                                                                                             |   3.2 GB |
| [avikertesz/001](https://source.coop/avikertesz/001)                                                                                                 |   3.1 GB |
| [ksa/kenol-section](https://source.coop/ksa/kenol-section)                                                                                           |   3.0 GB |
| [geographyis/wb-gad](https://source.coop/geographyis/wb-gad)                                                                                         |   2.8 GB |
| [cboettig/rivers](https://source.coop/cboettig/rivers)                                                                                               |   2.7 GB |
| [smartmaps/dem1a](https://source.coop/smartmaps/dem1a)                                                                                               |   2.6 GB |
| [ganzk/ads](https://source.coop/ganzk/ads)                                                                                                           |   2.5 GB |
| [fiboa/portugal](https://source.coop/fiboa/portugal)                                                                                                 |   2.4 GB |
| [fiboa/es-ar](https://source.coop/fiboa/es-ar)                                                                                                       |   2.4 GB |
| [fiboa/es-an](https://source.coop/fiboa/es-an)                                                                                                       |   2.3 GB |
| [fiboa/es-ex](https://source.coop/fiboa/es-ex)                                                                                                       |   2.3 GB |
| [fiboa/es-cat](https://source.coop/fiboa/es-cat)                                                                                                     |   2.2 GB |
| [smartmaps/mapterhorn-japan-bridge](https://source.coop/smartmaps/mapterhorn-japan-bridge)                                                           |   2.0 GB |
| [fiboa/nl-crop](https://source.coop/fiboa/nl-crop)                                                                                                   |   2.0 GB |
| [scar/distant](https://source.coop/scar/distant)                                                                                                     |   1.9 GB |
| [fiboa/es-ga](https://source.coop/fiboa/es-ga)                                                                                                       |   1.8 GB |
| [nlebovits/ign-argentina](https://source.coop/nlebovits/ign-argentina)                                                                               |   1.8 GB |
| [earthgenome/amazon-mining-watch](https://source.coop/earthgenome/amazon-mining-watch)                                                               |   1.8 GB |
| [cboettig/gfw](https://source.coop/cboettig/gfw)                                                                                                     |   1.7 GB |
| [pangeo/example-tiff](https://source.coop/pangeo/example-tiff)                                                                                       |   1.6 GB |
| [cboettig/epa-water](https://source.coop/cboettig/epa-water)                                                                                         |   1.6 GB |
| [walkthru-earth/opensensor-space](https://source.coop/walkthru-earth/opensensor-space)                                                               |   1.5 GB |
| [fiboa/estonia-ec](https://source.coop/fiboa/estonia-ec)                                                                                             |   1.4 GB |
| [cboettig/cpad](https://source.coop/cboettig/cpad)                                                                                                   |   1.4 GB |
| [cboettig/ca-dac](https://source.coop/cboettig/ca-dac)                                                                                               |   1.4 GB |
| [earthblox/cciwr](https://source.coop/earthblox/cciwr)                                                                                               |   1.3 GB |
| [cboettig/taxadb](https://source.coop/cboettig/taxadb)                                                                                               |   1.2 GB |
| [boston-university/bu-glance](https://source.coop/boston-university/bu-glance)                                                                       |   1.2 GB |
| [tabaqat/riyadh-satellite-pmtiles](https://source.coop/tabaqat/riyadh-satellite-pmtiles)                                                             |   1.1 GB |
| [ordnancesurvey/ngd-boundaries](https://source.coop/ordnancesurvey/ngd-boundaries)                                                                   |   1.0 GB |
| [alukach/firesmoke](https://source.coop/alukach/firesmoke)                                                                                           | 990.4 MB |
| [tabaqat/riyadh-sentinel-rgb](https://source.coop/tabaqat/riyadh-sentinel-rgb)                                                                       | 964.8 MB |
| [smartmaps/next-ksj](https://source.coop/smartmaps/next-ksj)                                                                                         | 962.3 MB |
| [cboettig/justice40](https://source.coop/cboettig/justice40)                                                                                         | 937.8 MB |
| [youssef-harby/weather-station-realtime-parquet](https://source.coop/youssef-harby/weather-station-realtime-parquet)                                 | 925.8 MB |
| [fiboa/ec-lv](https://source.coop/fiboa/ec-lv)                                                                                                       | 864.9 MB |
| [fiboa/austria](https://source.coop/fiboa/austria)                                                                                                   | 831.3 MB |
| [tabaqat/geocoding-cng](https://source.coop/tabaqat/geocoding-cng)                                                                                   | 820.0 MB |
| [fiboa/ireland](https://source.coop/fiboa/ireland)                                                                                                   | 805.5 MB |
| [carbonplan/virtual-datasets](https://source.coop/carbonplan/virtual-datasets)                                                                       | 783.7 MB |
| [smartmaps/h3ys-worldpop](https://source.coop/smartmaps/h3ys-worldpop)                                                                               | 777.5 MB |
| [fiboa/be-vlg](https://source.coop/fiboa/be-vlg)                                                                                                     | 719.2 MB |
| [planet/esri-tutorial-data](https://source.coop/planet/esri-tutorial-data)                                                                           | 716.6 MB |
| [smartmaps/dem10a](https://source.coop/smartmaps/dem10a)                                                                                             | 698.5 MB |
| [woodwell-climate/rangelands-raster-1](https://source.coop/woodwell-climate/rangelands-raster-1)                                                     | 694.0 MB |
| [smartmaps/mobility-gtfs-pmtiles](https://source.coop/smartmaps/mobility-gtfs-pmtiles)                                                               | 685.2 MB |
| [fiboa/latvia](https://source.coop/fiboa/latvia)                                                                                                     | 684.4 MB |
| [fiboa/nl-ref](https://source.coop/fiboa/nl-ref)                                                                                                     | 676.2 MB |
| [englacial/ice-sheet-temperature](https://source.coop/englacial/ice-sheet-temperature)                                                               | 676.1 MB |
| [nlebovits/censo-argentino](https://source.coop/nlebovits/censo-argentino)                                                                           | 649.4 MB |
| [cboettig/us-boundaries](https://source.coop/cboettig/us-boundaries)                                                                                 | 644.7 MB |
| [tge-labs/admin-boundaries](https://source.coop/tge-labs/admin-boundaries)                                                                           | 622.0 MB |
| [fiboa/es-pm](https://source.coop/fiboa/es-pm)                                                                                                       | 612.0 MB |
| [fiboa/denmark](https://source.coop/fiboa/denmark)                                                                                                   | 570.1 MB |
| [smartmaps/opencellid](https://source.coop/smartmaps/opencellid)                                                                                     | 559.6 MB |
| [fiboa/finland](https://source.coop/fiboa/finland)                                                                                                   | 558.1 MB |
| [fiboa/es-cb](https://source.coop/fiboa/es-cb)                                                                                                       | 551.1 MB |
| [cboettig/trails](https://source.coop/cboettig/trails)                                                                                               | 542.2 MB |
| [nlebovits/gaul-l2-admin](https://source.coop/nlebovits/gaul-l2-admin)                                                                               | 509.1 MB |
| [fiboa/sweden](https://source.coop/fiboa/sweden)                                                                                                     | 502.7 MB |
| [major-tom/index](https://source.coop/major-tom/index)                                                                                               | 498.7 MB |
| [fiboa/croatia](https://source.coop/fiboa/croatia)                                                                                                   | 481.2 MB |
| [cboettig/calenviroscreen](https://source.coop/cboettig/calenviroscreen)                                                                             | 475.9 MB |
| [fiboa/slovakia](https://source.coop/fiboa/slovakia)                                                                                                 | 468.2 MB |
| [cboettig/usgs-ungulate-migration](https://source.coop/cboettig/usgs-ungulate-migration)                                                             | 458.7 MB |
| [fiboa/czech](https://source.coop/fiboa/czech)                                                                                                       | 458.2 MB |
| [cecil/forest-carbon-boundaries](https://source.coop/cecil/forest-carbon-boundaries)                                                                 | 453.5 MB |
| [fiboa/switzerland](https://source.coop/fiboa/switzerland)                                                                                           | 445.3 MB |
| [cboettig/ncp](https://source.coop/cboettig/ncp)                                                                                                     | 420.6 MB |
| [fiboa/slovenia-ec](https://source.coop/fiboa/slovenia-ec)                                                                                           | 393.3 MB |
| [nlebovits/pergamino-ide](https://source.coop/nlebovits/pergamino-ide)                                                                               | 390.6 MB |
| [earthgenome/storm-events-db](https://source.coop/earthgenome/storm-events-db)                                                                       | 373.7 MB |
| [fiboa/es-md](https://source.coop/fiboa/es-md)                                                                                                       | 356.3 MB |
| [fiboa/slovenia](https://source.coop/fiboa/slovenia)                                                                                                 | 354.6 MB |
| [cboettig/usfws](https://source.coop/cboettig/usfws)                                                                                                 | 330.2 MB |
| [addresscloud/epc](https://source.coop/addresscloud/epc)                                                                                             | 302.5 MB |
| [fiboa/es-nc](https://source.coop/fiboa/es-nc)                                                                                                       | 293.8 MB |
| [cboettig/mobi](https://source.coop/cboettig/mobi)                                                                                                   | 283.4 MB |
| [fiboa/de-nrw](https://source.coop/fiboa/de-nrw)                                                                                                     | 273.9 MB |
| [tabaqat/roads-overture-pmtiles](https://source.coop/tabaqat/roads-overture-pmtiles)                                                                 | 268.6 MB |
| [fiboa/de-nds](https://source.coop/fiboa/de-nds)                                                                                                     | 252.2 MB |
| [dataforcanada/d4c-datapkg-environment-climate-health](https://source.coop/dataforcanada/d4c-datapkg-environment-climate-health)                     | 239.9 MB |
| [cboettig/connectivity](https://source.coop/cboettig/connectivity)                                                                                   | 222.7 MB |
| [smartmaps/nagasaki-mago](https://source.coop/smartmaps/nagasaki-mago)                                                                               | 220.7 MB |
| [fiboa/es-pv](https://source.coop/fiboa/es-pv)                                                                                                       | 203.7 MB |
| [fiboa/us-ca-scm](https://source.coop/fiboa/us-ca-scm)                                                                                               | 201.6 MB |
| [fiboa/de-th](https://source.coop/fiboa/de-th)                                                                                                       | 179.7 MB |
| [fiboa/es-cn](https://source.coop/fiboa/es-cn)                                                                                                       | 179.6 MB |
| [krishnaglodha/ksrsac-gis](https://source.coop/krishnaglodha/ksrsac-gis)                                                                             | 160.2 MB |
| [smartmaps/toshik](https://source.coop/smartmaps/toshik)                                                                                             | 159.9 MB |
| [earthgenome/open-ground](https://source.coop/earthgenome/open-ground)                                                                               | 154.9 MB |
| [fiboa/de-mv](https://source.coop/fiboa/de-mv)                                                                                                       | 150.8 MB |
| [hackl/euroflood-index](https://source.coop/hackl/euroflood-index)                                                                                   | 138.8 MB |
| [smartmaps/uppsala-conflict](https://source.coop/smartmaps/uppsala-conflict)                                                                         | 136.2 MB |
| [cboettig/cgs](https://source.coop/cboettig/cgs)                                                                                                     | 135.2 MB |
| [fiboa/de-sax](https://source.coop/fiboa/de-sax)                                                                                                     | 127.2 MB |
| [fiboa/be-wa](https://source.coop/fiboa/be-wa)                                                                                                       | 126.2 MB |
| [caires-tudelft/tokyo-13999-fcb](https://source.coop/caires-tudelft/tokyo-13999-fcb)                                                                 | 122.2 MB |
| [fiboa/lacunalabels](https://source.coop/fiboa/lacunalabels)                                                                                         | 109.6 MB |
| [fiboa/de-bb](https://source.coop/fiboa/de-bb)                                                                                                       | 102.8 MB |
| [streambatch/worldcereal](https://source.coop/streambatch/worldcereal)                                                                               | 100.0 MB |
| [kerner-lab/fields-of-the-world-spain](https://source.coop/kerner-lab/fields-of-the-world-spain)                                                     |  93.1 MB |
| [joshmoore/idr-ome-ngff-samples](https://source.coop/joshmoore/idr-ome-ngff-samples)                                                                 |  92.3 MB |
| [fiboa/de-sh](https://source.coop/fiboa/de-sh)                                                                                                       |  87.6 MB |
| [portolan/portolan-pipeline](https://source.coop/portolan/portolan-pipeline)                                                                         |  86.1 MB |
| [cholmes/admin-boundaries](https://source.coop/cholmes/admin-boundaries)                                                                             |  77.2 MB |
| [pangeo/geozarr-examples](https://source.coop/pangeo/geozarr-examples)                                                                               |  75.7 MB |
| [cboettig/habitat-corridors](https://source.coop/cboettig/habitat-corridors)                                                                         |  69.4 MB |
| [hdx/hapi](https://source.coop/hdx/hapi)                                                                                                             |  66.3 MB |
| [kerner-lab/fields-of-the-world-latvia](https://source.coop/kerner-lab/fields-of-the-world-latvia)                                                   |  57.6 MB |
| [rcejudo/000002](https://source.coop/rcejudo/000002)                                                                                                 |  54.3 MB |
| [fiboa/ai4sf](https://source.coop/fiboa/ai4sf)                                                                                                       |  53.3 MB |
| [fiboa/de-sl](https://source.coop/fiboa/de-sl)                                                                                                       |  47.5 MB |
| [tabaqat/gdelt-sa](https://source.coop/tabaqat/gdelt-sa)                                                                                             |  47.0 MB |
| [kerner-lab/fields-of-the-world-estonia](https://source.coop/kerner-lab/fields-of-the-world-estonia)                                                 |  46.6 MB |
| [kerner-lab/fields-of-the-world-austria](https://source.coop/kerner-lab/fields-of-the-world-austria)                                                 |  43.9 MB |
| [catalystcoop/pudl](https://source.coop/catalystcoop/pudl)                                                                                           |  42.1 MB |
| [kerner-lab/fields-of-the-world-croatia](https://source.coop/kerner-lab/fields-of-the-world-croatia)                                                 |  41.7 MB |
| [fiboa/luxembourg](https://source.coop/fiboa/luxembourg)                                                                                             |  39.3 MB |
| [esbach/lu-ecuador-2024](https://source.coop/esbach/lu-ecuador-2024)                                                                                 |  35.2 MB |
| [cboettig/mappinginequality](https://source.coop/cboettig/mappinginequality)                                                                         |  28.2 MB |
| [kerner-lab/fields-of-the-world-slovakia](https://source.coop/kerner-lab/fields-of-the-world-slovakia)                                               |  26.4 MB |
| [kerner-lab/fields-of-the-world-lithuania](https://source.coop/kerner-lab/fields-of-the-world-lithuania)                                             |  26.2 MB |
| [alliance-bioversity-international-ciat/sample-earth-2026-co-gh](https://source.coop/alliance-bioversity-international-ciat/sample-earth-2026-co-gh) |  24.6 MB |
| [kerner-lab/fields-of-the-world-finland](https://source.coop/kerner-lab/fields-of-the-world-finland)                                                 |  24.5 MB |
| [kerner-lab/fields-of-the-world-sweden](https://source.coop/kerner-lab/fields-of-the-world-sweden)                                                   |  23.8 MB |
| [nlebovits/philly-zoning](https://source.coop/nlebovits/philly-zoning)                                                                               |  23.7 MB |
| [fiboa/newzealand](https://source.coop/fiboa/newzealand)                                                                                             |  23.4 MB |
| [geovibes/geometries](https://source.coop/geovibes/geometries)                                                                                       |  22.1 MB |
| [ftw/trazo-fiboa](https://source.coop/ftw/trazo-fiboa)                                                                                               |  22.1 MB |
| [kerner-lab/fields-of-the-world-netherlands](https://source.coop/kerner-lab/fields-of-the-world-netherlands)                                         |  21.7 MB |
| [kerner-lab/fieldscapes-denmark](https://source.coop/kerner-lab/fieldscapes-denmark)                                                                 |  19.9 MB |
| [kerner-lab/fields-of-the-world-denmark](https://source.coop/kerner-lab/fields-of-the-world-denmark)                                                 |  19.9 MB |
| [kerner-lab/fields-of-the-world-cambodia](https://source.coop/kerner-lab/fields-of-the-world-cambodia)                                               |  19.3 MB |
| [kerner-lab/fields-of-the-world-france](https://source.coop/kerner-lab/fields-of-the-world-france)                                                   |  18.8 MB |
| [cboettig/conservation-policy](https://source.coop/cboettig/conservation-policy)                                                                     |  18.3 MB |
| [kerner-lab/fields-of-the-world-belgium](https://source.coop/kerner-lab/fields-of-the-world-belgium)                                                 |  17.7 MB |
| [ecovoice/canada-energy-supply-and-demand](https://source.coop/ecovoice/canada-energy-supply-and-demand)                                             |  17.1 MB |
| [kerner-lab/fields-of-the-world-luxembourg](https://source.coop/kerner-lab/fields-of-the-world-luxembourg)                                           |  16.2 MB |
| [kerner-lab/fields-of-the-world-slovenia](https://source.coop/kerner-lab/fields-of-the-world-slovenia)                                               |  15.1 MB |
| [cassiebuhler/30x30-state-policy](https://source.coop/cassiebuhler/30x30-state-policy)                                                               |  15.0 MB |
| [tristangruppwri/soft-commodity-infrastructure](https://source.coop/tristangruppwri/soft-commodity-infrastructure)                                   |  13.9 MB |
| [kerner-lab/fields-of-the-world-vietnam](https://source.coop/kerner-lab/fields-of-the-world-vietnam)                                                 |  10.5 MB |
| [englacial/xopr](https://source.coop/englacial/xopr)                                                                                                 |   8.5 MB |
| [kerner-lab/fields-of-the-world-india](https://source.coop/kerner-lab/fields-of-the-world-india)                                                     |   7.8 MB |
| [avikertesz/004](https://source.coop/avikertesz/004)                                                                                                 |   7.7 MB |
| [cholmes/trimet](https://source.coop/cholmes/trimet)                                                                                                 |   7.6 MB |
| [ecovoice/canada-solar-maps](https://source.coop/ecovoice/canada-solar-maps)                                                                         |   6.2 MB |
| [kerner-lab/fields-of-the-world-germany](https://source.coop/kerner-lab/fields-of-the-world-germany)                                                 |   6.0 MB |
| [avikertesz/003](https://source.coop/avikertesz/003)                                                                                                 |   5.6 MB |
| [source/metadata-catalog](https://source.coop/source/metadata-catalog)                                                                               |   5.3 MB |
| [maxar/maxar-opendata](https://source.coop/maxar/maxar-opendata)                                                                                     |   5.0 MB |
| [tabaqat/riyadh-places](https://source.coop/tabaqat/riyadh-places)                                                                                   |   4.7 MB |
| [cholmes/nyc-taxi-zones](https://source.coop/cholmes/nyc-taxi-zones)                                                                                 |   3.5 MB |
| [mdsumner/mdstest2](https://source.coop/mdsumner/mdstest2)                                                                                           |   3.2 MB |
| [kerner-lab/fields-of-the-world-portugal](https://source.coop/kerner-lab/fields-of-the-world-portugal)                                               |   3.0 MB |
| [sarahgamal/overture-places-riyadh](https://source.coop/sarahgamal/overture-places-riyadh)                                                           |   2.8 MB |
| [kerner-lab/fields-of-the-world-southafrica](https://source.coop/kerner-lab/fields-of-the-world-southafrica)                                         |   2.0 MB |
| [kerner-lab/fields-of-the-world-corsica](https://source.coop/kerner-lab/fields-of-the-world-corsica)                                                 |   2.0 MB |
| [ecovoice/canada-natural-gas-imports-exports](https://source.coop/ecovoice/canada-natural-gas-imports-exports)                                       |   2.0 MB |
| [geovibes/geovibes-datasets](https://source.coop/geovibes/geovibes-datasets)                                                                         |   1.8 MB |
| [kerner-lab/fields-of-the-world-brazil](https://source.coop/kerner-lab/fields-of-the-world-brazil)                                                   |   1.6 MB |
| [mdsumner/product](https://source.coop/mdsumner/product)                                                                                             |   1.2 MB |
| [000123/000001](https://source.coop/000123/000001)                                                                                                   | 773.3 KB |
| [ftw/ftw-inference-input](https://source.coop/ftw/ftw-inference-input)                                                                               | 342.9 KB |
| [kerner-lab/fields-of-the-world-rwanda](https://source.coop/kerner-lab/fields-of-the-world-rwanda)                                                   | 140.4 KB |
| [kerner-lab/fields-of-the-world-kenya](https://source.coop/kerner-lab/fields-of-the-world-kenya)                                                     |  92.5 KB |

</details>

### BACKLOG

<details><summary>all_failed .jpg — 1 dataset (91.8 GB)</summary>

| repo                                                                               |   bytes |
| ---------------------------------------------------------------------------------- | ------: |
| [wadhwani-ai/wiai-pm-open-data](https://source.coop/wadhwani-ai/wiai-pm-open-data) | 91.8 GB |

</details>

<details><summary>amended (no format) — 1 dataset (65.7 GB)</summary>

| repo                                                       |   bytes |
| ---------------------------------------------------------- | ------: |
| [cholmes/eurocrops](https://source.coop/cholmes/eurocrops) | 65.7 GB |

</details>

<details><summary>all_failed .parquet — 1 dataset (61.6 GB)</summary>

| repo                                               |   bytes |
| -------------------------------------------------- | ------: |
| [cboettig/obis](https://source.coop/cboettig/obis) | 61.6 GB |

</details>

<details><summary>in s3, not yet seeded — 1 dataset (3.0 B)</summary>

| repo                                                             | bytes |
| ---------------------------------------------------------------- | ----: |
| [major-tom/Core-S2L1C](https://source.coop/major-tom/Core-S2L1C) | 3.0 B |

</details>

### SKIPPED

<details><summary>unlisted — 162 datasets (1.8 PB)</summary>

| repo                                                                                                                                     |    bytes |
| ---------------------------------------------------------------------------------------------------------------------------------------- | -------: |
| [tessera/tessera](https://source.coop/tessera/tessera)                                                                                   |   1.5 PB |
| [mvrl/amos-v1](https://source.coop/mvrl/amos-v1)                                                                                         |  69.6 TB |
| [firststreet/aef-zarr](https://source.coop/firststreet/aef-zarr)                                                                         |  54.7 TB |
| [mvrl/amos](https://source.coop/mvrl/amos)                                                                                               |  53.5 TB |
| [govscape/eota-ocr](https://source.coop/govscape/eota-ocr)                                                                               |  12.8 TB |
| [carbonplan/srm-downscaling](https://source.coop/carbonplan/srm-downscaling)                                                             |   8.7 TB |
| [dynamical/eccc-hrdps-grib](https://source.coop/dynamical/eccc-hrdps-grib)                                                               |   7.1 TB |
| [clay/clay-v1-5-naip](https://source.coop/clay/clay-v1-5-naip)                                                                           |   6.8 TB |
| [e4drr-project/forecasts](https://source.coop/e4drr-project/forecasts)                                                                   |   5.1 TB |
| [clay/clay-v1-5-sentinel2](https://source.coop/clay/clay-v1-5-sentinel2)                                                                 |   3.2 TB |
| [zarr/landcovernet-zarr](https://source.coop/zarr/landcovernet-zarr)                                                                     |   2.1 TB |
| [bkr/obs](https://source.coop/bkr/obs)                                                                                                   |   1.7 TB |
| [harvard-lil/federal-github](https://source.coop/harvard-lil/federal-github)                                                             |   1.6 TB |
| [ftw/global-data-change](https://source.coop/ftw/global-data-change)                                                                     |   1.5 TB |
| [mvrl/ftw-inference-gfm](https://source.coop/mvrl/ftw-inference-gfm)                                                                     |   1.5 TB |
| [ftw/global-field-boundaries](https://source.coop/ftw/global-field-boundaries)                                                           |   1.1 TB |
| [earthgenome/s2-embeddings](https://source.coop/earthgenome/s2-embeddings)                                                               | 999.7 GB |
| [harvard-lil/smithsonian-transcription-center](https://source.coop/harvard-lil/smithsonian-transcription-center)                         | 853.9 GB |
| [vida/merged-google-microsoft-open-buildings](https://source.coop/vida/merged-google-microsoft-open-buildings)                           | 843.8 GB |
| [uos-shiver/antarctica](https://source.coop/uos-shiver/antarctica)                                                                       | 699.9 GB |
| [uos-shiver/greenland](https://source.coop/uos-shiver/greenland)                                                                         | 651.5 GB |
| [diegovd/geo-data-test](https://source.coop/diegovd/geo-data-test)                                                                       | 385.5 GB |
| [dynamical/noaa-gfs-analysis-hourly](https://source.coop/dynamical/noaa-gfs-analysis-hourly)                                             | 342.3 GB |
| [major-tom/landsatl8toa](https://source.coop/major-tom/landsatl8toa)                                                                     | 337.1 GB |
| [epoch/forest-typology-2020](https://source.coop/epoch/forest-typology-2020)                                                             | 333.3 GB |
| [vizzuality/biodiversity-intactness-100m-v1-1](https://source.coop/vizzuality/biodiversity-intactness-100m-v1-1)                         | 316.4 GB |
| [mlcommons/unsupservised-peoples-speech](https://source.coop/mlcommons/unsupservised-peoples-speech)                                     | 258.3 GB |
| [harvard-lil/nih](https://source.coop/harvard-lil/nih)                                                                                   | 220.5 GB |
| [isaaccorley/ftw-scratchpad](https://source.coop/isaaccorley/ftw-scratchpad)                                                             | 203.3 GB |
| [luddaludwig/boreal-fire-carbon](https://source.coop/luddaludwig/boreal-fire-carbon)                                                     | 200.1 GB |
| [geovibes/aeromancy](https://source.coop/geovibes/aeromancy)                                                                             | 163.4 GB |
| [tge-labs/mind](https://source.coop/tge-labs/mind)                                                                                       | 161.8 GB |
| [epoch/jrc-tmf](https://source.coop/epoch/jrc-tmf)                                                                                       | 125.9 GB |
| [giswqs/building-height](https://source.coop/giswqs/building-height)                                                                     | 115.8 GB |
| [ftw/ftw-planet](https://source.coop/ftw/ftw-planet)                                                                                     | 102.3 GB |
| [cboettig/us-rivers](https://source.coop/cboettig/us-rivers)                                                                             |  99.3 GB |
| [wri-data-lab/trazofields](https://source.coop/wri-data-lab/trazofields)                                                                 |  57.6 GB |
| [kerner-lab/fields-of-the-world-archive](https://source.coop/kerner-lab/fields-of-the-world-archive)                                     |  56.8 GB |
| [giswqs/biomass](https://source.coop/giswqs/biomass)                                                                                     |  47.0 GB |
| [clay/california-naip-clay-v1](https://source.coop/clay/california-naip-clay-v1)                                                         |  46.8 GB |
| [e4drr-project/observations](https://source.coop/e4drr-project/observations)                                                             |  44.2 GB |
| [ftw/ftw-inference-output](https://source.coop/ftw/ftw-inference-output)                                                                 |  38.9 GB |
| [tristangruppwri/trazofields](https://source.coop/tristangruppwri/trazofields)                                                           |  29.2 GB |
| [cholmes/fiboa-scratch](https://source.coop/cholmes/fiboa-scratch)                                                                       |  21.7 GB |
| [khvzix/delineate-anything-fields](https://source.coop/khvzix/delineate-anything-fields)                                                 |  21.7 GB |
| [luddaludwig/potential-agc-combustion-ssp585-v0](https://source.coop/luddaludwig/potential-agc-combustion-ssp585-v0)                     |  21.4 GB |
| [fiboa/mgrs](https://source.coop/fiboa/mgrs)                                                                                             |  21.1 GB |
| [amitbajaj/testrepo401](https://source.coop/amitbajaj/testrepo401)                                                                       |  21.0 GB |
| [berkeley-dse/mrcl](https://source.coop/berkeley-dse/mrcl)                                                                               |  20.2 GB |
| [opengeos/us-buildings](https://source.coop/opengeos/us-buildings)                                                                       |  19.2 GB |
| [epoch/global-natural-planted-forests](https://source.coop/epoch/global-natural-planted-forests)                                         |  18.3 GB |
| [cholmes/nhd](https://source.coop/cholmes/nhd)                                                                                           |  17.0 GB |
| [ftw/usda-csb](https://source.coop/ftw/usda-csb)                                                                                         |  14.9 GB |
| [ondata/cadastral-italy-geospatial-data](https://source.coop/ondata/cadastral-italy-geospatial-data)                                     |  14.7 GB |
| [ftw/aef-field-boundaries](https://source.coop/ftw/aef-field-boundaries)                                                                 |  12.4 GB |
| [calebrob6/geospatialml](https://source.coop/calebrob6/geospatialml)                                                                     |  12.0 GB |
| [avineon-tensing/england-trees-outside-woodland-tow](https://source.coop/avineon-tensing/england-trees-outside-woodland-tow)             |  11.9 GB |
| [jwasserman/geoparquet-spatial-query-testing](https://source.coop/jwasserman/geoparquet-spatial-query-testing)                           |  11.5 GB |
| [calebrob6/venezuela-2026-earthquake-planet-aois](https://source.coop/calebrob6/venezuela-2026-earthquake-planet-aois)                   |  11.3 GB |
| [developmentseed/stac-geoparquet](https://source.coop/developmentseed/stac-geoparquet)                                                   |  11.0 GB |
| [major-tom/esaworldcover](https://source.coop/major-tom/esaworldcover)                                                                   |  10.9 GB |
| [cholmes/stac-geoparquet-public](https://source.coop/cholmes/stac-geoparquet-public)                                                     |  10.9 GB |
| [mindearth/wsf](https://source.coop/mindearth/wsf)                                                                                       |  10.7 GB |
| [humane-intelligence/bias-bounty-mapping-equity-challenge](https://source.coop/humane-intelligence/bias-bounty-mapping-equity-challenge) |   8.0 GB |
| [source/manifests](https://source.coop/source/manifests)                                                                                 |   8.0 GB |
| [cholmes/openet-demo](https://source.coop/cholmes/openet-demo)                                                                           |   6.8 GB |
| [hirooimaki/vegetation-jp](https://source.coop/hirooimaki/vegetation-jp)                                                                 |   6.7 GB |
| [amitbajaj/repotoday](https://source.coop/amitbajaj/repotoday)                                                                           |   6.2 GB |
| [vida/dre-atlas](https://source.coop/vida/dre-atlas)                                                                                     |   5.4 GB |
| [rsignell/esip2025](https://source.coop/rsignell/esip2025)                                                                               |   5.3 GB |
| [cholmes/aois](https://source.coop/cholmes/aois)                                                                                         |   5.1 GB |
| [root-geospatial/flight-counts](https://source.coop/root-geospatial/flight-counts)                                                       |   4.6 GB |
| [m-mohr/ftw-confidence-layers](https://source.coop/m-mohr/ftw-confidence-layers)                                                         |   4.5 GB |
| [caires-tudelft/plateau-tokyo-fcb](https://source.coop/caires-tudelft/plateau-tokyo-fcb)                                                 |   3.9 GB |
| [cholmes/os-opendata-cng](https://source.coop/cholmes/os-opendata-cng)                                                                   |   3.9 GB |
| [brunosan/clay-model-v0-embeddings](https://source.coop/brunosan/clay-model-v0-embeddings)                                               |   3.6 GB |
| [nishadhka/aq-icechunk-store-ifs](https://source.coop/nishadhka/aq-icechunk-store-ifs)                                                   |   2.7 GB |
| [tyler/colombia-ecosystems-map](https://source.coop/tyler/colombia-ecosystems-map)                                                       |   2.5 GB |
| [espm-288/espm-288-testing](https://source.coop/espm-288/espm-288-testing)                                                               |   2.3 GB |
| [tyler/usda-nass-cdl](https://source.coop/tyler/usda-nass-cdl)                                                                           |   2.1 GB |
| [tyler/gadm](https://source.coop/tyler/gadm)                                                                                             |   2.0 GB |
| [tristangruppwri/trazotraining](https://source.coop/tristangruppwri/trazotraining)                                                       |   1.9 GB |
| [calebrob6/spokane-wildfires-august-2026](https://source.coop/calebrob6/spokane-wildfires-august-2026)                                   |   1.9 GB |
| [wri-data-lab/trazoannotations](https://source.coop/wri-data-lab/trazoannotations)                                                       |   1.9 GB |
| [vdavez/usaspending-data](https://source.coop/vdavez/usaspending-data)                                                                   |   1.9 GB |
| [harvard-lil/data-gov-metadata](https://source.coop/harvard-lil/data-gov-metadata)                                                       |   1.3 GB |
| [youssef-harby/cloud-native-geocoding](https://source.coop/youssef-harby/cloud-native-geocoding)                                         |   1.1 GB |
| [amitbajaj/testrepo12](https://source.coop/amitbajaj/testrepo12)                                                                         |   1.1 GB |
| [tge-labs/st-louis-open-data-mirror](https://source.coop/tge-labs/st-louis-open-data-mirror)                                             | 809.1 MB |
| [idi/scout-test-repo](https://source.coop/idi/scout-test-repo)                                                                           | 806.8 MB |
| [alukach/test-product](https://source.coop/alukach/test-product)                                                                         | 756.1 MB |
| [ktyle/metar2024](https://source.coop/ktyle/metar2024)                                                                                   | 682.4 MB |
| [cboettig/ca30x30](https://source.coop/cboettig/ca30x30)                                                                                 | 457.5 MB |
| [smartmaps/sugi](https://source.coop/smartmaps/sugi)                                                                                     | 395.0 MB |
| [cr458/google](https://source.coop/cr458/google)                                                                                         | 392.7 MB |
| [ome/sample-images](https://source.coop/ome/sample-images)                                                                               | 340.6 MB |
| [earthgenome/sed-test](https://source.coop/earthgenome/sed-test)                                                                         | 337.3 MB |
| [smartmaps/rwanda10](https://source.coop/smartmaps/rwanda10)                                                                             | 337.0 MB |
| [englacial/ismip6-combined](https://source.coop/englacial/ismip6-combined)                                                               | 320.3 MB |
| [epoch/global-forest-loss-drivers](https://source.coop/epoch/global-forest-loss-drivers)                                                 | 302.0 MB |
| [kbgg/test](https://source.coop/kbgg/test)                                                                                               | 290.9 MB |
| [cholmes/stac-geoparquet-s2l2a](https://source.coop/cholmes/stac-geoparquet-s2l2a)                                                       | 275.1 MB |
| [cboettig/288-demo](https://source.coop/cboettig/288-demo)                                                                               | 230.0 MB |
| [smartmaps/rw-wip-2024-05-31](https://source.coop/smartmaps/rw-wip-2024-05-31)                                                           | 226.5 MB |
| [roorda-tudelft/public-trees-in-nl](https://source.coop/roorda-tudelft/public-trees-in-nl)                                               | 220.9 MB |
| [smartmaps/tmet](https://source.coop/smartmaps/tmet)                                                                                     | 193.1 MB |
| [zarr/geozarr-tests](https://source.coop/zarr/geozarr-tests)                                                                             | 156.6 MB |
| [eeholmes/cefi](https://source.coop/eeholmes/cefi)                                                                                       | 138.5 MB |
| [m-mohr/test](https://source.coop/m-mohr/test)                                                                                           | 115.3 MB |
| [michelle/test](https://source.coop/michelle/test)                                                                                       | 102.8 MB |
| [kerner-lab/fieldscapes-spain](https://source.coop/kerner-lab/fieldscapes-spain)                                                         |  93.1 MB |
| [kerner-lab/fieldscapes-latvia](https://source.coop/kerner-lab/fieldscapes-latvia)                                                       |  57.6 MB |
| [kerner-lab/fieldscapes-estonia](https://source.coop/kerner-lab/fieldscapes-estonia)                                                     |  46.6 MB |
| [kerner-lab/fieldscapes-austria](https://source.coop/kerner-lab/fieldscapes-austria)                                                     |  43.9 MB |
| [kerner-lab/fieldscapes-romania](https://source.coop/kerner-lab/fieldscapes-romania)                                                     |  43.4 MB |
| [kerner-lab/fieldscapes-croatia](https://source.coop/kerner-lab/fieldscapes-croatia)                                                     |  41.7 MB |
| [ftw/ftw-tests](https://source.coop/ftw/ftw-tests)                                                                                       |  38.4 MB |
| [kerner-lab/fieldscapes-slovakia](https://source.coop/kerner-lab/fieldscapes-slovakia)                                                   |  26.4 MB |
| [kerner-lab/fieldscapes-lithuania](https://source.coop/kerner-lab/fieldscapes-lithuania)                                                 |  26.2 MB |
| [kerner-lab/fieldscapes-finland](https://source.coop/kerner-lab/fieldscapes-finland)                                                     |  24.5 MB |
| [kerner-lab/fieldscapes-sweden](https://source.coop/kerner-lab/fieldscapes-sweden)                                                       |  23.8 MB |
| [cholmes/s2-grid](https://source.coop/cholmes/s2-grid)                                                                                   |  23.0 MB |
| [kerner-lab/fieldscapes-netherlands](https://source.coop/kerner-lab/fieldscapes-netherlands)                                             |  21.7 MB |
| [kerner-lab/fieldscapes-cambodia](https://source.coop/kerner-lab/fieldscapes-cambodia)                                                   |  19.3 MB |
| [kerner-lab/fieldscapes-france](https://source.coop/kerner-lab/fieldscapes-france)                                                       |  18.8 MB |
| [kerner-lab/fieldscapes-belgium](https://source.coop/kerner-lab/fieldscapes-belgium)                                                     |  17.7 MB |
| [kerner-lab/fieldscapes-luxembourg](https://source.coop/kerner-lab/fieldscapes-luxembourg)                                               |  16.2 MB |
| [kerner-lab/fieldscapes-slovenia](https://source.coop/kerner-lab/fieldscapes-slovenia)                                                   |  15.1 MB |
| [kerner-lab/fieldscapes-vietnam](https://source.coop/kerner-lab/fieldscapes-vietnam)                                                     |  10.5 MB |
| [kerner-lab/fieldscapes-india](https://source.coop/kerner-lab/fieldscapes-india)                                                         |   7.8 MB |
| [kerner-lab/fieldscapes-germany](https://source.coop/kerner-lab/fieldscapes-germany)                                                     |   6.0 MB |
| [dnwaeze/kenol-section](https://source.coop/dnwaeze/kenol-section)                                                                       |   5.8 MB |
| [tyler/iucn-get-vocabularies](https://source.coop/tyler/iucn-get-vocabularies)                                                           |   5.4 MB |
| [cholmes/gur-shadow-fleet](https://source.coop/cholmes/gur-shadow-fleet)                                                                 |   3.7 MB |
| [tyler/maxar-opendata-v1-1](https://source.coop/tyler/maxar-opendata-v1-1)                                                               |   3.6 MB |
| [mcgeo/testing-diligence](https://source.coop/mcgeo/testing-diligence)                                                                   |   3.2 MB |
| [kerner-lab/fieldscapes-portugal](https://source.coop/kerner-lab/fieldscapes-portugal)                                                   |   3.0 MB |
| [kerner-lab/fieldscapes](https://source.coop/kerner-lab/fieldscapes)                                                                     |   2.9 MB |
| [csaybar/3dclouds](https://source.coop/csaybar/3dclouds)                                                                                 |   2.8 MB |
| [val/test-prod-vp](https://source.coop/val/test-prod-vp)                                                                                 |   2.6 MB |
| [source/source-stats](https://source.coop/source/source-stats)                                                                           |   2.3 MB |
| [tyler/test-tiff-not-cloud-optimized](https://source.coop/tyler/test-tiff-not-cloud-optimized)                                           |   2.2 MB |
| [kerner-lab/fieldscapes-southafrica](https://source.coop/kerner-lab/fieldscapes-southafrica)                                             |   2.0 MB |
| [kerner-lab/fieldscapes-corsica](https://source.coop/kerner-lab/fieldscapes-corsica)                                                     |   2.0 MB |
| [amitbajaj/canada-natural-gas-imports-exports](https://source.coop/amitbajaj/canada-natural-gas-imports-exports)                         |   2.0 MB |
| [kerner-lab/fieldscapes-brazil](https://source.coop/kerner-lab/fieldscapes-brazil)                                                       |   1.4 MB |
| [michelle/test-v3](https://source.coop/michelle/test-v3)                                                                                 |   1.4 MB |
| [eeholmes/chlaz](https://source.coop/eeholmes/chlaz)                                                                                     |   1.2 MB |
| [pangeo/earth-data-examples](https://source.coop/pangeo/earth-data-examples)                                                             |   1.1 MB |
| [streambatch/usda-county-boundaries-2017](https://source.coop/streambatch/usda-county-boundaries-2017)                                   | 931.4 KB |
| [rti/rwanda-crop-landcover-labels](https://source.coop/rti/rwanda-crop-landcover-labels)                                                 | 475.7 KB |
| [source/cmr-metadata](https://source.coop/source/cmr-metadata)                                                                           | 354.3 KB |
| [idi/idi-source-coop-test01](https://source.coop/idi/idi-source-coop-test01)                                                             | 348.0 KB |
| [rsignell/liveocean](https://source.coop/rsignell/liveocean)                                                                             | 235.8 KB |
| [rti-international/2023-002](https://source.coop/rti-international/2023-002)                                                             | 218.2 KB |
| [rti-international/2023-001](https://source.coop/rti-international/2023-001)                                                             | 163.1 KB |
| [kerner-lab/fieldscapes-rwanda](https://source.coop/kerner-lab/fieldscapes-rwanda)                                                       | 140.4 KB |
| [kerner-lab/fieldscapes-kenya](https://source.coop/kerner-lab/fieldscapes-kenya)                                                         |  92.5 KB |
| [auspatious/lulc-sids](https://source.coop/auspatious/lulc-sids)                                                                         |  89.5 KB |
| [notoncebut2x/youthmappers](https://source.coop/notoncebut2x/youthmappers)                                                               |  71.8 KB |
| [youthmappers/ym-tz-crop-survey-2023](https://source.coop/youthmappers/ym-tz-crop-survey-2023)                                           |  71.8 KB |
| [source/sites.source.coop](https://source.coop/source/sites.source.coop)                                                                 |  21.5 KB |

</details>

<details><summary>no_prober — 11 datasets (18.0 TB)</summary>

| repo                                                                                                                           |    bytes |
| ------------------------------------------------------------------------------------------------------------------------------ | -------: |
| [harvard-lil/gov-data](https://source.coop/harvard-lil/gov-data)                                                               |  17.9 TB |
| [dataforcanada/d4c-datapkg-field-imagery](https://source.coop/dataforcanada/d4c-datapkg-field-imagery)                         |  10.9 GB |
| [taco/darktom](https://source.coop/taco/darktom)                                                                               |   3.0 GB |
| [symbotic-computing-lab/chesapeake-land-cover-subset](https://source.coop/symbotic-computing-lab/chesapeake-land-cover-subset) |   2.2 GB |
| [jianbo/gndc-higlass-ls20](https://source.coop/jianbo/gndc-higlass-ls20)                                                       | 720.9 MB |
| [troyschmidt/hurrevac-storm-advisories](https://source.coop/troyschmidt/hurrevac-storm-advisories)                             | 321.4 MB |
| [fiboa/br-ba-lem](https://source.coop/fiboa/br-ba-lem)                                                                         |   7.3 MB |
| [youssef-harby/overture-maps-stac](https://source.coop/youssef-harby/overture-maps-stac)                                       | 718.0 KB |
| [asterisk-labs/cozip](https://source.coop/asterisk-labs/cozip)                                                                 |  98.5 KB |
| [fish-pace/chla-z](https://source.coop/fish-pace/chla-z)                                                                       |  12.0 KB |
| [cboettig/glen](https://source.coop/cboettig/glen)                                                                             |  10.9 KB |

</details>

<details><summary>test_repo — 7 datasets (2.0 TB)</summary>

| repo                                                                                   |    bytes |
| -------------------------------------------------------------------------------------- | -------: |
| [rseg/long-lfmc-test](https://source.coop/rseg/long-lfmc-test)                         |   2.0 TB |
| [mcox/testkrillswarm](https://source.coop/mcox/testkrillswarm)                         | 983.6 MB |
| [cholmes/gpio-test](https://source.coop/cholmes/gpio-test)                             | 239.2 MB |
| [nlebovits/moldova-test-data](https://source.coop/nlebovits/moldova-test-data)         | 215.6 MB |
| [tyler/test-files](https://source.coop/tyler/test-files)                               |  16.0 MB |
| [severo/apache-parquet-testing](https://source.coop/severo/apache-parquet-testing)     |   4.1 MB |
| [severo/csv-papaparse-test-files](https://source.coop/severo/csv-papaparse-test-files) |  72.4 KB |

</details>

<details><summary>tiny — 25 datasets (33.4 KB)</summary>

| repo                                                                                               |   bytes |
| -------------------------------------------------------------------------------------------------- | ------: |
| [tabaqat/riyadh-places-geoparquet](https://source.coop/tabaqat/riyadh-places-geoparquet)           |  5.8 KB |
| [tomr/gri-datapkg](https://source.coop/tomr/gri-datapkg)                                           |  5.6 KB |
| [carbonplan/ccarbonplan-ocr](https://source.coop/carbonplan/ccarbonplan-ocr)                       |  5.4 KB |
| [opsis-oxford/global-econ-data](https://source.coop/opsis-oxford/global-econ-data)                 |  3.1 KB |
| [wherobots/human-modification](https://source.coop/wherobots/human-modification)                   |  2.6 KB |
| [iceberg/s3_access_logs](https://source.coop/iceberg/s3_access_logs)                               |  2.6 KB |
| [quadrature-earth/inyo-county-test](https://source.coop/quadrature-earth/inyo-county-test)         |  2.2 KB |
| [iceberg/s3_logs_hourly_stats](https://source.coop/iceberg/s3_logs_hourly_stats)                   |  1.7 KB |
| [nlebovits/philadelphia-aerial-imagery](https://source.coop/nlebovits/philadelphia-aerial-imagery) |  1.2 KB |
| [fiboa/spain](https://source.coop/fiboa/spain)                                                     |  1.2 KB |
| [forestsignal/forestsignal-ca](https://source.coop/forestsignal/forestsignal-ca)                   | 598.0 B |
| [tyler/tylers-test-product-id](https://source.coop/tyler/tylers-test-product-id)                   | 548.0 B |
| [saraka/test-1](https://source.coop/saraka/test-1)                                                 | 343.0 B |
| [bkr/gmgsi](https://source.coop/bkr/gmgsi)                                                         | 209.0 B |
| [kbgg/auth-test](https://source.coop/kbgg/auth-test)                                               | 122.0 B |
| [opsis-oxford/test](https://source.coop/opsis-oxford/test)                                         |  35.0 B |
| [alukach/alukach-experimentation](https://source.coop/alukach/alukach-experimentation)             |  20.0 B |
| [berkeley-dse/california-ace](https://source.coop/berkeley-dse/california-ace)                     |  18.0 B |
| [major-tom/core-s2l1c](https://source.coop/major-tom/core-s2l1c)                                   |   3.0 B |
| [geovibes/embedding-ftw](https://source.coop/geovibes/embedding-ftw)                               |   0.0 B |
| [harvard-lil/staging-gov-data](https://source.coop/harvard-lil/staging-gov-data)                   |   0.0 B |
| [jacobsn/amos-v1](https://source.coop/jacobsn/amos-v1)                                             |   0.0 B |
| [jcushman/test](https://source.coop/jcushman/test)                                                 |   0.0 B |
| [kbgg/foobar](https://source.coop/kbgg/foobar)                                                     |   0.0 B |
| [ncar/eol](https://source.coop/ncar/eol)                                                           |   0.0 B |

</details>

### MISMATCHES

<details><summary>stowaways (S3 data, no source.coop product) — 42 datasets (951.4 TB)</summary>

| repo                                                      |    bytes |
| --------------------------------------------------------- | -------: |
| tge-labs/ftw-global-data                                  | 368.6 TB |
| ncar/corona                                               | 259.5 TB |
| tge-labs/aef-mosaic-backfill                              | 122.6 TB |
| ncar/mlso                                                 |  65.0 TB |
| ncar/gdex                                                 |  62.6 TB |
| mlcommons/unsupervised-peoples-speech                     |  47.6 TB |
| tge-labs/ftw-aef-mosaic                                   |  12.1 TB |
| bkr/icon-global-raw                                       |   9.2 TB |
| dynamical/noaa-hrrr-analysis                              |   2.8 TB |
| google-research-open-buildings/fgb-s2                     | 487.0 GB |
| google-research-open-buildings/v2                         | 240.6 GB |
| geovibes/experiments                                      | 163.8 GB |
| google-research-open-buildings/geoparquet-by-country      | 161.1 GB |
| google-research-open-buildings/geoparquet-s2-more-columns | 150.2 GB |
| harvard-lil/batch-operations                              |  44.9 GB |
| nlebovits/gpq-tiles-demo                                  |  31.4 GB |
| harvard-lil/inventories                                   |  25.8 GB |
| vnp46a1_thermal_anomaly/classification                    |  23.9 GB |
| nlebovits/landsat-lst                                     |   9.0 GB |
| vnp46a1_thermal_anomaly/anomaly_det                       |   6.6 GB |
| pangeo/esip2025                                           |   5.3 GB |
| source/inventory                                          |   3.0 GB |
| tabaqat/riyadh-sentinel-pmtiles                           |   1.1 GB |
| sarahgamal/riyadh-satellite-cog                           | 964.8 MB |
| nlebovits/clone-test-147                                  | 416.1 MB |
| nlebovits/nlebovits                                       | 416.1 MB |
| tabaqat/riyadh-roads-pmtiles                              | 268.6 MB |
| nlebovits/usgs-naip-philly-test                           | 185.2 MB |
| krishnaglodha/krsac                                       | 160.2 MB |
| krishnaglodha/ksrcas-gis                                  | 160.2 MB |
| fiboa/repo                                                | 153.8 MB |
| nlebovits/arg-censo                                       |  42.0 MB |
| krishnaglodha/karnataka                                   |  41.1 MB |
| nlebovits/den-haag-roundtrip                              |  38.9 MB |
| ausantarctic/mdstest                                      |  13.0 MB |
| nlebovits/pasda-flat                                      |   8.0 MB |
| mdsumner/mdstest                                          |   2.8 MB |
| nlebovits/landsat-lst-test                                |   2.0 MB |
| sarahgamal/riyadh-places                                  | 455.4 KB |
| benchmark/tasks                                           | 430.9 KB |
| benchmark/uploads                                         | 210.0 KB |
| ecovoice/test-repo                                        |  21.9 KB |

</details>

<details><summary>ghosts (catalog entry, no S3 data) — 50 datasets (29.8 TB)</summary>

| repo                                                                                                                                                   | state   | catalog claims |
| ------------------------------------------------------------------------------------------------------------------------------------------------------ | ------- | -------------: |
| [agentmorris/lila-wildlife-snapshotserengeti-unzipped](https://source.coop/agentmorris/lila-wildlife-snapshotserengeti-unzipped)                       | drafted |         6.1 TB |
| [agentmorris/lila-wildlife-snapshot-safari-2024-expansion](https://source.coop/agentmorris/lila-wildlife-snapshot-safari-2024-expansion)               | drafted |         5.0 TB |
| [agentmorris/lila-wildlife-idaho-camera-traps](https://source.coop/agentmorris/lila-wildlife-idaho-camera-traps)                                       | drafted |         3.1 TB |
| [agentmorris/lila-wildlife-swg-camera-traps](https://source.coop/agentmorris/lila-wildlife-swg-camera-traps)                                           | drafted |         2.8 TB |
| [agentmorris/lila-wildlife-nz-trailcams](https://source.coop/agentmorris/lila-wildlife-nz-trailcams)                                                   | drafted |         2.1 TB |
| [agentmorris/lila-wildlife-noaa-kotz](https://source.coop/agentmorris/lila-wildlife-noaa-kotz)                                                         | drafted |         1.7 TB |
| [agentmorris/lila-wildlife-nacti-unzipped](https://source.coop/agentmorris/lila-wildlife-nacti-unzipped)                                               | drafted |         1.5 TB |
| [agentmorris/lila-wildlife-lcmcvpr2019](https://source.coop/agentmorris/lila-wildlife-lcmcvpr2019)                                                     | drafted |       886.7 GB |
| [agentmorris/lila-wildlife-california-small-animals](https://source.coop/agentmorris/lila-wildlife-california-small-animals)                           | drafted |       790.5 GB |
| [agentmorris/lila-wildlife-geolifeclef-2020](https://source.coop/agentmorris/lila-wildlife-geolifeclef-2020)                                           | drafted |       780.3 GB |
| [agentmorris/lila-wildlife-nz-thermal](https://source.coop/agentmorris/lila-wildlife-nz-thermal)                                                       | drafted |       677.4 GB |
| [agentmorris/lila-wildlife-wcs-unzipped](https://source.coop/agentmorris/lila-wildlife-wcs-unzipped)                                                   | drafted |       594.6 GB |
| [agentmorris/lila-wildlife-snapshot-safari](https://source.coop/agentmorris/lila-wildlife-snapshot-safari)                                             | drafted |       542.3 GB |
| [agentmorris/lila-wildlife-nkhotakota-camera-traps](https://source.coop/agentmorris/lila-wildlife-nkhotakota-camera-traps)                             | drafted |       337.5 GB |
| [agentmorris/lila-wildlife-seattleish-camera-traps](https://source.coop/agentmorris/lila-wildlife-seattleish-camera-traps)                             | drafted |       321.2 GB |
| [agentmorris/lila-wildlife-izembek-lagoon-birds](https://source.coop/agentmorris/lila-wildlife-izembek-lagoon-birds)                                   | drafted |       265.4 GB |
| [agentmorris/lila-wildlife-community-fish-detection-dataset](https://source.coop/agentmorris/lila-wildlife-community-fish-detection-dataset)           | drafted |       261.1 GB |
| [agentmorris/lila-wildlife-lindenthal-camera-traps](https://source.coop/agentmorris/lila-wildlife-lindenthal-camera-traps)                             | drafted |       213.1 GB |
| [agentmorris/lila-wildlife-wni-giraffes](https://source.coop/agentmorris/lila-wildlife-wni-giraffes)                                                   | drafted |       200.7 GB |
| [agentmorris/lila-wildlife-wellington-unzipped](https://source.coop/agentmorris/lila-wildlife-wellington-unzipped)                                     | drafted |       198.4 GB |
| [agentmorris/lila-wildlife-channel-islands-camera-traps](https://source.coop/agentmorris/lila-wildlife-channel-islands-camera-traps)                   | drafted |       186.4 GB |
| [agentmorris/lila-wildlife-islandconservationcameratraps](https://source.coop/agentmorris/lila-wildlife-islandconservationcameratraps)                 | drafted |       164.0 GB |
| [agentmorris/lila-wildlife-desert-lion-camera-traps](https://source.coop/agentmorris/lila-wildlife-desert-lion-camera-traps)                           | drafted |       154.7 GB |
| [agentmorris/lila-wildlife-orinoquia-camera-traps](https://source.coop/agentmorris/lila-wildlife-orinoquia-camera-traps)                               | drafted |       154.5 GB |
| [agentmorris/lila-wildlife-unsw-predators](https://source.coop/agentmorris/lila-wildlife-unsw-predators)                                               | drafted |       130.4 GB |
| [agentmorris/lila-wildlife-caltech-unzipped](https://source.coop/agentmorris/lila-wildlife-caltech-unzipped)                                           | drafted |       112.4 GB |
| [agentmorris/lila-wildlife-conservationdrones](https://source.coop/agentmorris/lila-wildlife-conservationdrones)                                       | drafted |        98.3 GB |
| [agentmorris/lila-wildlife-icimod-glacier-mapping](https://source.coop/agentmorris/lila-wildlife-icimod-glacier-mapping)                               | drafted |        73.9 GB |
| [agentmorris/lila-wildlife-biome-health-project-maasai-mara-2018](https://source.coop/agentmorris/lila-wildlife-biome-health-project-maasai-mara-2018) | drafted |        64.0 GB |
| [agentmorris/lila-wildlife-boise-state-vegetation](https://source.coop/agentmorris/lila-wildlife-boise-state-vegetation)                               | drafted |        62.9 GB |
| [agentmorris/lila-wildlife-osu-small-animals](https://source.coop/agentmorris/lila-wildlife-osu-small-animals)                                         | drafted |        60.8 GB |
| [agentmorris/lila-wildlife-wild-me](https://source.coop/agentmorris/lila-wildlife-wild-me)                                                             | drafted |        29.6 GB |
| [ftw/financial-times](https://source.coop/ftw/financial-times)                                                                                         | seed    |        22.8 GB |
| [agentmorris/lila-wildlife-missouricameratraps](https://source.coop/agentmorris/lila-wildlife-missouricameratraps)                                     | drafted |        20.5 GB |
| [agentmorris/lila-wildlife-ena24](https://source.coop/agentmorris/lila-wildlife-ena24)                                                                 | drafted |         7.8 GB |
| [agentmorris/lila-wildlife-noaa-psnf](https://source.coop/agentmorris/lila-wildlife-noaa-psnf)                                                         | drafted |         7.7 GB |
| [harvard-lil/duckdb-test](https://source.coop/harvard-lil/duckdb-test)                                                                                 | seed    |         5.3 GB |
| [agentmorris/lila-wildlife-cvwc2019](https://source.coop/agentmorris/lila-wildlife-cvwc2019)                                                           | drafted |         4.4 GB |
| [dataforcanada/ca-orthoimagery-labs](https://source.coop/dataforcanada/ca-orthoimagery-labs)                                                           | seed    |         4.3 GB |
| [agentmorris/lila-wildlife-larch-casebearer](https://source.coop/agentmorris/lila-wildlife-larch-casebearer)                                           | drafted |         3.5 GB |
| [agentmorris/lila-wildlife-aerial-birds-west-africa](https://source.coop/agentmorris/lila-wildlife-aerial-birds-west-africa)                           | drafted |         2.4 GB |
| [agentmorris/lila-wildlife-boxes-on-bees](https://source.coop/agentmorris/lila-wildlife-boxes-on-bees)                                                 | drafted |         2.1 GB |
| [agentmorris/lila-wildlife-sea-star-re-id](https://source.coop/agentmorris/lila-wildlife-sea-star-re-id)                                               | drafted |         1.9 GB |
| [tge-labs/tessera](https://source.coop/tge-labs/tessera)                                                                                               | seed    |         1.1 GB |
| [agentmorris/lila-wildlife-uas-imagery-of-migratory-waterfowl](https://source.coop/agentmorris/lila-wildlife-uas-imagery-of-migratory-waterfowl)       | drafted |       337.8 MB |
| [agentmorris/lila-wildlife-adkres-invasive](https://source.coop/agentmorris/lila-wildlife-adkres-invasive)                                             | drafted |       158.7 MB |
| [tge-labs/trazo-fiboa](https://source.coop/tge-labs/trazo-fiboa)                                                                                       | drafted |        22.1 MB |
| [major-tom/copernicusdem](https://source.coop/major-tom/copernicusdem)                                                                                 | seed    |        13.1 MB |
| [tge-labs/terrabit](https://source.coop/tge-labs/terrabit)                                                                                             | seed    |         6.6 MB |
| [dataforcanada/ca-foundation-labs](https://source.coop/dataforcanada/ca-foundation-labs)                                                               | seed    |        86.9 KB |

</details>

<details><summary>stale (catalog bytes ≠ S3; fixed by <code>make process-all</code>) — 43 datasets (7.3 TB)</summary>

| repo                                                                                                                             | updated    |        catalog → S3 |
| -------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------: |
| [walkthru-earth/opensensor-space](https://source.coop/walkthru-earth/opensensor-space)                                           | 2026-08-23 |     1.5 GB → 1.5 GB |
| [dynamical/noaa-gefs-analysis](https://source.coop/dynamical/noaa-gefs-analysis)                                                 | 2026-08-23 |     1.1 TB → 1.1 TB |
| [dynamical/asos-parquet](https://source.coop/dynamical/asos-parquet)                                                             | 2026-08-23 |   20.2 GB → 20.2 GB |
| [dataforcanada/d4c-datapkg-environment-climate-health](https://source.coop/dataforcanada/d4c-datapkg-environment-climate-health) | 2026-08-23 | 226.9 MB → 239.9 MB |
| [dynamical/noaa-gfs-analysis](https://source.coop/dynamical/noaa-gfs-analysis)                                                   | 2026-08-23 | 655.8 GB → 658.3 GB |
| [dynamical/noaa-mrms-conus-analysis-hourly](https://source.coop/dynamical/noaa-mrms-conus-analysis-hourly)                       | 2026-08-23 | 252.0 GB → 252.4 GB |
| [alukach/firesmoke](https://source.coop/alukach/firesmoke)                                                                       | 2026-08-23 | 907.1 MB → 990.4 MB |
| [ausantarctic/ghrsst-mur-v2](https://source.coop/ausantarctic/ghrsst-mur-v2)                                                     | 2026-08-23 |     4.3 TB → 4.3 TB |
| [giswqs/opengeos](https://source.coop/giswqs/opengeos)                                                                           | 2026-08-22 |   19.2 GB → 19.2 GB |
| [portolan/portolan-pipeline](https://source.coop/portolan/portolan-pipeline)                                                     | 2026-08-22 |   45.4 MB → 86.1 MB |
| [tristangruppwri/mapbiomas](https://source.coop/tristangruppwri/mapbiomas)                                                       | 2026-08-22 |    3.1 GB → 14.7 GB |
| [source/metadata-catalog](https://source.coop/source/metadata-catalog)                                                           | 2026-08-22 |     4.4 MB → 5.3 MB |
| [earthgenome/storm-events-db](https://source.coop/earthgenome/storm-events-db)                                                   | 2026-08-20 | 373.7 MB → 373.7 MB |
| [earthgenome/amazon-mining-watch](https://source.coop/earthgenome/amazon-mining-watch)                                           | 2026-08-20 |     3.3 GB → 1.8 GB |
| [tristangruppwri/cadastral](https://source.coop/tristangruppwri/cadastral)                                                       | 2026-08-20 |     3.6 GB → 3.6 GB |
| [tristangruppwri/soft-commodity-infrastructure](https://source.coop/tristangruppwri/soft-commodity-infrastructure)               | 2026-08-20 |   14.4 MB → 13.9 MB |
| [cboettig/usgs-wbd](https://source.coop/cboettig/usgs-wbd)                                                                       | 2026-08-20 |   15.2 GB → 12.1 GB |
| [cboettig/usgs-nhd](https://source.coop/cboettig/usgs-nhd)                                                                       | 2026-08-20 |  149.1 GB → 49.7 GB |
| [cboettig/usfws](https://source.coop/cboettig/usfws)                                                                             | 2026-08-20 | 447.2 MB → 330.2 MB |
| [cboettig/trails](https://source.coop/cboettig/trails)                                                                           | 2026-08-20 | 923.5 MB → 542.2 MB |
| [cboettig/social-vulnerability](https://source.coop/cboettig/social-vulnerability)                                               | 2026-08-20 |   13.3 GB → 13.0 GB |
| [cboettig/rivers](https://source.coop/cboettig/rivers)                                                                           | 2026-08-20 |     4.0 GB → 2.7 GB |
| [cboettig/padus](https://source.coop/cboettig/padus)                                                                             | 2026-08-20 |   46.7 GB → 35.2 GB |
| [cboettig/overturemaps](https://source.coop/cboettig/overturemaps)                                                               | 2026-08-20 |   69.8 GB → 64.6 GB |
| [cboettig/mappinginequality](https://source.coop/cboettig/mappinginequality)                                                     | 2026-08-20 |   32.7 MB → 28.2 MB |
| [cboettig/indigenous](https://source.coop/cboettig/indigenous)                                                                   | 2026-08-20 |   22.8 GB → 20.2 GB |
| [cboettig/inat](https://source.coop/cboettig/inat)                                                                               | 2026-08-20 |    13.1 GB → 6.5 GB |
| [cboettig/high-seas](https://source.coop/cboettig/high-seas)                                                                     | 2026-08-20 |   40.5 GB → 47.3 GB |
| [cboettig/hazard](https://source.coop/cboettig/hazard)                                                                           | 2026-08-20 |   40.7 GB → 40.7 GB |
| [cboettig/gfw](https://source.coop/cboettig/gfw)                                                                                 | 2026-08-20 |     2.8 GB → 1.7 GB |
| [cboettig/gbif](https://source.coop/cboettig/gbif)                                                                               | 2026-08-20 | 169.0 GB → 169.0 GB |
| [cboettig/fire](https://source.coop/cboettig/fire)                                                                               | 2026-08-20 |     6.7 GB → 3.2 GB |
| [cboettig/facts](https://source.coop/cboettig/facts)                                                                             | 2026-08-20 |   22.7 GB → 15.1 GB |
| [cboettig/epa-water](https://source.coop/cboettig/epa-water)                                                                     | 2026-08-20 |     2.8 GB → 1.6 GB |
| [cboettig/ecoregion](https://source.coop/cboettig/ecoregion)                                                                     | 2026-08-20 |     3.3 GB → 3.3 GB |
| [cboettig/cpad](https://source.coop/cboettig/cpad)                                                                               | 2026-08-20 |     1.4 GB → 1.4 GB |
| [cboettig/connectivity](https://source.coop/cboettig/connectivity)                                                               | 2026-08-20 |   1.5 GB → 222.7 MB |
| [cboettig/cgs](https://source.coop/cboettig/cgs)                                                                                 | 2026-08-20 | 228.4 MB → 135.2 MB |
| [cboettig/census](https://source.coop/cboettig/census)                                                                           | 2026-08-20 |   44.3 GB → 42.8 GB |
| [cboettig/ca-dac](https://source.coop/cboettig/ca-dac)                                                                           | 2026-08-20 |     1.6 GB → 1.4 GB |
| [smartmaps/cogenerate](https://source.coop/smartmaps/cogenerate)                                                                 | 2026-08-19 | 415.7 GB → 427.7 GB |
| [hdx/cod-ab](https://source.coop/hdx/cod-ab)                                                                                     | 2026-08-19 |   26.6 GB → 27.3 GB |
| [cboettig/fishbase](https://source.coop/cboettig/fishbase)                                                                       | 2026-08-18 |     4.1 GB → 4.3 GB |

</details>

## Upload activity

_Live objects by upload date, from the 2026-08-23 inventory snapshot (`make activity` refreshes)._

### Top uploaders (30 days, 2026-07-25 to 2026-08-23)
| account                                            | uploaded |      files | repos | % of bytes |
| -------------------------------------------------- | -------: | ---------: | ----: | ---------: |
| [tessera](https://source.coop/tessera)             |   1.0 PB | 21,372,314 |     1 |      71.5% |
| [bkr](https://source.coop/bkr)                     | 108.5 TB | 33,448,831 |    11 |       7.6% |
| [dynamical](https://source.coop/dynamical)         | 102.3 TB | 11,614,757 |    13 |       7.2% |
| [geoai-ucph](https://source.coop/geoai-ucph)       | 101.7 TB |  1,822,779 |     1 |       7.1% |
| [mvrl](https://source.coop/mvrl)                   |  53.5 TB |    280,577 |     1 |       3.8% |
| [tge-labs](https://source.coop/tge-labs)           |  15.7 TB |    272,209 |     3 |       1.1% |
| [carbonplan](https://source.coop/carbonplan)       |   8.7 TB |     39,974 |     2 |       0.6% |
| [harvard-lil](https://source.coop/harvard-lil)     |   6.0 TB |  2,513,968 |     4 |       0.4% |
| [e4drr-project](https://source.coop/e4drr-project) |   5.0 TB |  1,774,933 |     1 |       0.4% |
| [uos-shiver](https://source.coop/uos-shiver)       |   1.4 TB |  2,635,861 |     2 |       0.1% |
| **top 10 total**                                   |   1.4 PB | 75,776,203 |    39 |      99.8% |
| **other 36 accounts**                              |   2.6 TB |  3,979,987 |    91 |       0.2% |
| **all 46 accounts**                                |   1.4 PB | 79,756,190 |   130 |     100.0% |

_130 repos — 35 new (166.7 TB), 95 updated (1.3 PB)_

### By month (last 12)
| month   | accounts | repos | new repos | uploaded | into new repos |
| ------- | -------: | ----: | --------: | -------: | -------------: |
| 2026-08 |       40 |   120 |        20 |   1.3 PB |       102.0 TB |
| 2026-07 |       44 |   114 |        42 | 772.1 TB |        31.9 TB |
| 2026-06 |       47 |   118 |        64 | 465.2 TB |       306.0 TB |
| 2026-05 |       44 |    78 |        24 | 256.6 TB |        57.6 TB |
| 2026-04 |       37 |    77 |        30 | 260.2 TB |       211.9 TB |
| 2026-03 |       23 |    63 |        26 | 905.7 TB |       689.9 TB |
| 2026-02 |       28 |    54 |        21 | 580.8 TB |       436.4 TB |
| 2026-01 |       24 |    49 |        17 | 139.6 TB |        16.4 TB |
| 2025-12 |       23 |    35 |         9 | 144.7 TB |        85.2 GB |
| 2025-11 |       20 |    37 |        17 |   1.4 PB |         1.3 PB |
| 2025-10 |       16 |    36 |        20 |  68.2 TB |        47.5 TB |
| 2025-09 |       10 |    16 |         8 |  35.3 TB |        32.2 TB |

