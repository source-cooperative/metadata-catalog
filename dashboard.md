# Source Cooperative catalog — status

_Updated 2026-07-19 09:31 UTC by the nightly pipeline._

**324 datasets cataloged**  ·  **18 queued for next run**  ·  last run handled **10**

## Last run

<details><summary>✅ drafted — 6 datasets</summary>

| repo                                                                                                                             |
| -------------------------------------------------------------------------------------------------------------------------------- |
| [cboettig/land-cover](https://source.coop/cboettig/land-cover)                                                                   |
| [dataforcanada/d4c-datapkg-environment-climate-health](https://source.coop/dataforcanada/d4c-datapkg-environment-climate-health) |
| [dynamical/asos-parquet](https://source.coop/dynamical/asos-parquet)                                                             |
| [giswqs/opengeos](https://source.coop/giswqs/opengeos)                                                                           |
| [rseg/sentinel1-lfmc](https://source.coop/rseg/sentinel1-lfmc)                                                                   |
| [walkthru-earth/opensensor-space](https://source.coop/walkthru-earth/opensensor-space)                                           |

</details>

<details><summary>⏭️ incomplete (gap) — 3 datasets</summary>

| repo                                                                                                                                                 | why            |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [alliance-bioversity-international-ciat/sample-earth-2026-co-gh](https://source.coop/alliance-bioversity-international-ciat/sample-earth-2026-co-gh) | no_probe .gpkg |
| [forestsignal/forestsignal-ca](https://source.coop/forestsignal/forestsignal-ca)                                                                     | no_files .tif  |
| [harvard-lil/smithsonian-open-access](https://source.coop/harvard-lil/smithsonian-open-access)                                                       | no_probe .jpg  |

</details>

<details><summary>⚠️ probe failed (issue filed) — 1 dataset</summary>

| repo                                                       | why              |
| ---------------------------------------------------------- | ---------------- |
| [alukach/firesmoke](https://source.coop/alukach/firesmoke) | all_failed .zarr |

</details>


See [open probe-failure issues](https://github.com/source-cooperative/metadata-catalog/issues?q=is%3Aissue+is%3Aopen+label%3Aprobe-failure).

## Recent runs

| run                                                                                                    | outcome   | drafted | failed | queued | cataloged |
| ------------------------------------------------------------------------------------------------------ | --------- | ------: | -----: | -----: | --------: |
| [2026-07-19](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/29680931533) | ✅ success |       6 |      1 |     18 |       324 |
| [2026-07-18](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/29638344163) | ✅ success |       7 |      0 |     25 |       324 |
| [2026-07-17](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/29568722047) | ✅ success |       7 |      0 |     32 |       324 |
| [2026-07-16](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/29485933223) | ✅ success |       7 |      0 |     39 |       324 |
| [2026-07-15](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/29403217926) | ✅ success |       7 |      0 |     46 |       324 |
| [2026-07-14](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/29320375956) | ✅ success |       7 |      1 |     54 |       324 |
| [2026-07-12](https://github.com/source-cooperative/metadata-catalog-pipeline/actions/runs/29186862502) | ✅ success |       8 |      1 |     51 |       324 |

## Persistent failures

**19 datasets failing**  ·  19 open issues  ·  oldest **38d**  ·  **15** ≥30d  ·  [all open issues](https://github.com/source-cooperative/metadata-catalog/issues?q=is%3Aissue+is%3Aopen+label%3Aprobe-failure)

<details><summary>the 19 open issues, oldest first</summary>

| repo                                                | age (d) | issue |
| --------------------------------------------------- | ------: | ----: |
| bkr/cams                                            |      38 |    #1 |
| smartmaps/uppsala-conflict                          |      36 |   #16 |
| smartmaps/next-ksj                                  |      36 |   #15 |
| smartmaps/h3ys-worldpop                             |      36 |   #14 |
| smartmaps/dem1a                                     |      36 |   #13 |
| smartmaps/dem10a                                    |      36 |   #12 |
| rsignell/ncei-estuarine-bathymetry                  |      36 |   #11 |
| pfrost/climacell-monthly                            |      36 |   #10 |
| geovibes/geometries                                 |      36 |    #9 |
| fiboa/data                                          |      36 |    #8 |
| dynamical/dwd-icon-eu-forecast-5-day                |      36 |    #7 |
| cboettig/obis                                       |      36 |    #6 |
| cboettig/habitat-corridors                          |      36 |    #5 |
| caires-tudelft/tokyo-13999-fcb                      |      36 |    #4 |
| caires-tudelft/plateau-tokyo-fcb-2                  |      36 |    #3 |
| cboettig/wetlands                                   |      19 |  #122 |
| dynamical/dwd-icon-grib                             |       6 |  #125 |
| dynamical/ecmwf-ifs-ens-forecast-15-day-0-25-degree |       4 |  #126 |
| alukach/firesmoke                                   |       ? |  #128 |

</details>

## 13 datasets need a prober

<details><summary>by format — ranked by bytes unlocked if built</summary>

<details><summary>.jpg — 1 dataset · 827.7 TB</summary>

| repo                                                                                           |    bytes |
| ---------------------------------------------------------------------------------------------- | -------: |
| [harvard-lil/smithsonian-open-access](https://source.coop/harvard-lil/smithsonian-open-access) | 827.7 TB |

</details>

<details><summary>.nc — 2 datasets · 167.7 GB</summary>

| repo                                                                                         |    bytes |
| -------------------------------------------------------------------------------------------- | -------: |
| [pfrost/climacell-monthly](https://source.coop/pfrost/climacell-monthly)                     | 162.4 GB |
| [rsignell/ncei-estuarine-bathymetry](https://source.coop/rsignell/ncei-estuarine-bathymetry) |   5.3 GB |

</details>

<details><summary>.pmtiles — 4 datasets · 4.3 GB</summary>

| repo                                                                         |    bytes |
| ---------------------------------------------------------------------------- | -------: |
| [smartmaps/dem1a](https://source.coop/smartmaps/dem1a)                       |   2.6 GB |
| [smartmaps/h3ys-worldpop](https://source.coop/smartmaps/h3ys-worldpop)       | 777.5 MB |
| [smartmaps/dem10a](https://source.coop/smartmaps/dem10a)                     | 698.5 MB |
| [smartmaps/uppsala-conflict](https://source.coop/smartmaps/uppsala-conflict) | 136.2 MB |

</details>

<details><summary>.fcb — 2 datasets · 4.2 GB</summary>

| repo                                                                                         |    bytes |
| -------------------------------------------------------------------------------------------- | -------: |
| [caires-tudelft/plateau-tokyo-fcb-2](https://source.coop/caires-tudelft/plateau-tokyo-fcb-2) |   4.1 GB |
| [caires-tudelft/tokyo-13999-fcb](https://source.coop/caires-tudelft/tokyo-13999-fcb)         | 122.2 MB |

</details>

<details><summary>.fgb — 1 dataset · 962.3 MB</summary>

| repo                                                         |    bytes |
| ------------------------------------------------------------ | -------: |
| [smartmaps/next-ksj](https://source.coop/smartmaps/next-ksj) | 962.3 MB |

</details>

<details><summary>.shp — 1 dataset · 69.4 MB</summary>

| repo                                                                         |   bytes |
| ---------------------------------------------------------------------------- | ------: |
| [cboettig/habitat-corridors](https://source.coop/cboettig/habitat-corridors) | 69.4 MB |

</details>

<details><summary>.gpkg — 1 dataset · 24.6 MB</summary>

| repo                                                                                                                                                 |   bytes |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------: |
| [alliance-bioversity-international-ciat/sample-earth-2026-co-gh](https://source.coop/alliance-bioversity-international-ciat/sample-earth-2026-co-gh) | 24.6 MB |

</details>

<details><summary>.geojson — 1 dataset · 22.1 MB</summary>

| repo                                                           |   bytes |
| -------------------------------------------------------------- | ------: |
| [geovibes/geometries](https://source.coop/geovibes/geometries) | 22.1 MB |

</details>

</details>

## Catalog funnel

_Each bucket links to its datasets under [Datasets per category](#datasets-per-category)._

| group                         | agg count | agg bytes | count |    bytes |
| ----------------------------- | --------: | --------: | ----: | -------: |
| [CATALOGED](#cataloged)       |       320 |    3.6 PB |       |          |
|   drafted                     |           |           |   320 |   3.6 PB |
| [BACKLOG](#backlog)           |        15 |   41.1 TB |       |          |
|   error step=gather-probe     |           |           |     1 |  39.0 TB |
|   all_failed .icechunk        |           |           |     1 |   1.0 TB |
|   in s3, not yet seeded       |           |           |     6 | 735.8 GB |
|   all_failed .filegdb         |           |           |     1 | 187.6 GB |
|   amended (no format)         |           |           |     1 |  65.7 GB |
|   all_failed .parquet         |           |           |     1 |  61.6 GB |
|   no_probe .fcb               |           |           |     2 |   4.2 GB |
|   all_failed .zarr            |           |           |     1 |   3.3 GB |
|   no_probe .gpkg              |           |           |     1 |  24.6 MB |
| [SKIPPED](#skipped)           |       196 |  623.8 TB |       |          |
|   unlisted                    |           |           |   148 | 560.0 TB |
|   not_geo                     |           |           |    19 |  61.8 TB |
|   test_repo                   |           |           |     7 |   1.9 TB |
|   tiny                        |           |           |    22 |  30.6 KB |
| [UNREGISTERED](#unregistered) |        40 |  924.6 TB |       |          |
|   stowaways                   |           |           |    40 | 924.6 TB |
| S3 total                      |       571 |    5.2 PB |       |          |

## Datasets per category

_Each entry expands to the datasets counted in it (collapsed by default)._

### CATALOGED

<details><summary>drafted — 320 datasets · 3.6 PB</summary>

| repo                                                                                                                               |    bytes |
| ---------------------------------------------------------------------------------------------------------------------------------- | -------: |
| [harvard-lil/smithsonian-open-access](https://source.coop/harvard-lil/smithsonian-open-access)                                     | 827.7 TB |
| [tge-labs/aef](https://source.coop/tge-labs/aef)                                                                                   | 576.6 TB |
| [tge-labs/aef-mosaic](https://source.coop/tge-labs/aef-mosaic)                                                                     | 552.9 TB |
| [bkr/icon](https://source.coop/bkr/icon)                                                                                           | 320.8 TB |
| [earthgenome/earthindeximagery](https://source.coop/earthgenome/earthindeximagery)                                                 | 171.2 TB |
| [dynamical/noaa-gefs-forecast-35-day](https://source.coop/dynamical/noaa-gefs-forecast-35-day)                                     | 165.9 TB |
| [bkr/geo](https://source.coop/bkr/geo)                                                                                             | 159.6 TB |
| [dynamical/ecmwf-ifs-grib](https://source.coop/dynamical/ecmwf-ifs-grib)                                                           | 117.8 TB |
| [govscape/eota-pdf-archive](https://source.coop/govscape/eota-pdf-archive)                                                         | 107.3 TB |
| [earthgenome/sentinel2-temporal-mosaics](https://source.coop/earthgenome/sentinel2-temporal-mosaics)                               |  76.3 TB |
| [cworthy/dor-efficiency-atlas](https://source.coop/cworthy/dor-efficiency-atlas)                                                   |  74.1 TB |
| [cworthy/oae-efficiency-atlas](https://source.coop/cworthy/oae-efficiency-atlas)                                                   |  56.6 TB |
| [dynamical/ecmwf-ifs-ens-forecast-15-day-0-25-degree](https://source.coop/dynamical/ecmwf-ifs-ens-forecast-15-day-0-25-degree)     |  46.4 TB |
| [bkr/geos](https://source.coop/bkr/geos)                                                                                           |  38.9 TB |
| [bkr/ifs](https://source.coop/bkr/ifs)                                                                                             |  36.9 TB |
| [mapterhorn/mapterhorn](https://source.coop/mapterhorn/mapterhorn)                                                                 |  26.7 TB |
| [tge-labs/meta-chm-v2](https://source.coop/tge-labs/meta-chm-v2)                                                                   |  23.8 TB |
| [dynamical/noaa-gfs-forecast](https://source.coop/dynamical/noaa-gfs-forecast)                                                     |  23.5 TB |
| [bkr/silam-dust](https://source.coop/bkr/silam-dust)                                                                               |  22.8 TB |
| [bkr/dmi](https://source.coop/bkr/dmi)                                                                                             |  19.7 TB |
| [dataforcanada/d4c-datapkg-orthoimagery](https://source.coop/dataforcanada/d4c-datapkg-orthoimagery)                               |  15.5 TB |
| [bkr/metoffice](https://source.coop/bkr/metoffice)                                                                                 |  14.9 TB |
| [fused/overture](https://source.coop/fused/overture)                                                                               |  13.8 TB |
| [dynamical/noaa-hrrr-forecast-48-hour](https://source.coop/dynamical/noaa-hrrr-forecast-48-hour)                                   |  12.5 TB |
| [bkr/marine](https://source.coop/bkr/marine)                                                                                       |  12.1 TB |
| [bkr/polar](https://source.coop/bkr/polar)                                                                                         |  10.9 TB |
| [clay/lgnd-embeddings](https://source.coop/clay/lgnd-embeddings)                                                                   |   9.6 TB |
| [earthgenome/earthindexembeddings](https://source.coop/earthgenome/earthindexembeddings)                                           |   8.5 TB |
| [clay/clay-v1-5-naip-2](https://source.coop/clay/clay-v1-5-naip-2)                                                                 |   6.6 TB |
| [wherobots/fields-of-the-world](https://source.coop/wherobots/fields-of-the-world)                                                 |   5.4 TB |
| [malariaatlas/lst](https://source.coop/malariaatlas/lst)                                                                           |   5.3 TB |
| [bkr/precipradar](https://source.coop/bkr/precipradar)                                                                             |   4.7 TB |
| [auspatious/geomad-sids](https://source.coop/auspatious/geomad-sids)                                                               |   4.5 TB |
| [ausantarctic/ghrsst-mur-v2](https://source.coop/ausantarctic/ghrsst-mur-v2)                                                       |   4.2 TB |
| [major-tom/elliot-pretrain](https://source.coop/major-tom/elliot-pretrain)                                                         |   4.2 TB |
| [dataforcanada/d4c-datapkg-web-corpus](https://source.coop/dataforcanada/d4c-datapkg-web-corpus)                                   |   4.0 TB |
| [bkr/imerg](https://source.coop/bkr/imerg)                                                                                         |   4.0 TB |
| [bkr/gmgi](https://source.coop/bkr/gmgi)                                                                                           |   3.9 TB |
| [bkr/gfs](https://source.coop/bkr/gfs)                                                                                             |   3.8 TB |
| [vida/google-microsoft-open-buildings](https://source.coop/vida/google-microsoft-open-buildings)                                   |   3.6 TB |
| [vida/google-microsoft-osm-open-buildings](https://source.coop/vida/google-microsoft-osm-open-buildings)                           |   2.8 TB |
| [malariaatlas/tcw](https://source.coop/malariaatlas/tcw)                                                                           |   2.7 TB |
| [malariaatlas/tcb](https://source.coop/malariaatlas/tcb)                                                                           |   2.7 TB |
| [malariaatlas/evi](https://source.coop/malariaatlas/evi)                                                                           |   2.6 TB |
| [bkr/mrms](https://source.coop/bkr/mrms)                                                                                           |   2.4 TB |
| [major-tom/core](https://source.coop/major-tom/core)                                                                               |   1.9 TB |
| [dynamical/ecmwf-aifs-single-forecast](https://source.coop/dynamical/ecmwf-aifs-single-forecast)                                   |   1.9 TB |
| [root-geospatial/flight-tracks](https://source.coop/root-geospatial/flight-tracks)                                                 |   1.5 TB |
| [englacial/ismip6](https://source.coop/englacial/ismip6)                                                                           |   1.3 TB |
| [smartmaps/japan-seamlessphoto](https://source.coop/smartmaps/japan-seamlessphoto)                                                 |   1.2 TB |
| [cboettig/gbif](https://source.coop/cboettig/gbif)                                                                                 |   1.2 TB |
| [wildland-almanac/conus](https://source.coop/wildland-almanac/conus)                                                               |   1.0 TB |
| [dynamical/noaa-gefs-analysis](https://source.coop/dynamical/noaa-gefs-analysis)                                                   | 972.0 GB |
| [wildland-almanac/treatment-scenarios](https://source.coop/wildland-almanac/treatment-scenarios)                                   | 894.7 GB |
| [taco/3dclouds](https://source.coop/taco/3dclouds)                                                                                 | 832.5 GB |
| [walkthru-earth/dem-terrain](https://source.coop/walkthru-earth/dem-terrain)                                                       | 831.4 GB |
| [carbonplan/carbonplan-ocr](https://source.coop/carbonplan/carbonplan-ocr)                                                         | 826.4 GB |
| [cholmes/overture](https://source.coop/cholmes/overture)                                                                           | 779.1 GB |
| [smartmaps/xing](https://source.coop/smartmaps/xing)                                                                               | 748.1 GB |
| [bkr/nsrdb](https://source.coop/bkr/nsrdb)                                                                                         | 636.9 GB |
| [geospatialml/terrabit](https://source.coop/geospatialml/terrabit)                                                                 | 626.2 GB |
| [wildland-almanac/california](https://source.coop/wildland-almanac/california)                                                     | 574.1 GB |
| [walkthru-earth/indices](https://source.coop/walkthru-earth/indices)                                                               | 568.6 GB |
| [earthgenome/food-twin](https://source.coop/earthgenome/food-twin)                                                                 | 544.1 GB |
| [fika/waternet](https://source.coop/fika/waternet)                                                                                 | 527.0 GB |
| [dataforcanada/d4c-datapkg-elevation](https://source.coop/dataforcanada/d4c-datapkg-elevation)                                     | 526.0 GB |
| [dynamical/noaa-gfs-analysis](https://source.coop/dynamical/noaa-gfs-analysis)                                                     | 508.2 GB |
| [kylebarron/usgs-landcover](https://source.coop/kylebarron/usgs-landcover)                                                         | 506.5 GB |
| [clay/lgnd-clay-v1-5-sentinel-2-l2a](https://source.coop/clay/lgnd-clay-v1-5-sentinel-2-l2a)                                       | 503.2 GB |
| [protomaps/openstreetmap](https://source.coop/protomaps/openstreetmap)                                                             | 488.7 GB |
| [giswqs/tn-imagery](https://source.coop/giswqs/tn-imagery)                                                                         | 412.5 GB |
| [bkr/weatherreal](https://source.coop/bkr/weatherreal)                                                                             | 399.2 GB |
| [abry-tudelft/eubucco](https://source.coop/abry-tudelft/eubucco)                                                                   | 395.2 GB |
| [geovibes/search](https://source.coop/geovibes/search)                                                                             | 330.6 GB |
| [eco4cast/neon4cast-forecasts](https://source.coop/eco4cast/neon4cast-forecasts)                                                   | 330.1 GB |
| [smartmaps/japan-geotiff-dem](https://source.coop/smartmaps/japan-geotiff-dem)                                                     | 318.4 GB |
| [bkr/err](https://source.coop/bkr/err)                                                                                             | 288.6 GB |
| [dynamical/noaa-mrms-conus-analysis-hourly](https://source.coop/dynamical/noaa-mrms-conus-analysis-hourly)                         | 250.0 GB |
| [smartmaps/ngs](https://source.coop/smartmaps/ngs)                                                                                 | 232.0 GB |
| [tge-labs/globalbuildingatlas-lod1](https://source.coop/tge-labs/globalbuildingatlas-lod1)                                         | 224.7 GB |
| [tge-labs/openbuildingmap](https://source.coop/tge-labs/openbuildingmap)                                                           | 208.3 GB |
| [smartmaps/gel](https://source.coop/smartmaps/gel)                                                                                 | 196.0 GB |
| [cboettig/carbon](https://source.coop/cboettig/carbon)                                                                             | 170.8 GB |
| [rseg/sentinel1-lfmc](https://source.coop/rseg/sentinel1-lfmc)                                                                     | 167.8 GB |
| [pfrost/climacell-monthly](https://source.coop/pfrost/climacell-monthly)                                                           | 162.4 GB |
| [giswqs/giw](https://source.coop/giswqs/giw)                                                                                       | 146.6 GB |
| [cboettig/rap](https://source.coop/cboettig/rap)                                                                                   | 140.4 GB |
| [nlebovits/phl-aerial-imagery](https://source.coop/nlebovits/phl-aerial-imagery)                                                   | 129.6 GB |
| [hdx/google-open-buildings](https://source.coop/hdx/google-open-buildings)                                                         | 123.4 GB |
| [wherobots/usa-structures](https://source.coop/wherobots/usa-structures)                                                           | 122.5 GB |
| [kerner-lab/fields-of-the-world](https://source.coop/kerner-lab/fields-of-the-world)                                               | 120.8 GB |
| [hdx/microsoft-open-buildings](https://source.coop/hdx/microsoft-open-buildings)                                                   | 105.1 GB |
| [dataforcanada/d4c-datapkg-statistical](https://source.coop/dataforcanada/d4c-datapkg-statistical)                                 | 101.4 GB |
| [alexgleith/tasmania-dem-2m](https://source.coop/alexgleith/tasmania-dem-2m)                                                       |  95.2 GB |
| [pacificspatial/field-polygon-jp](https://source.coop/pacificspatial/field-polygon-jp)                                             |  94.8 GB |
| [englacial/demogorgn](https://source.coop/englacial/demogorgn)                                                                     |  93.0 GB |
| [cholmes/portolan-nl](https://source.coop/cholmes/portolan-nl)                                                                     |  83.7 GB |
| [giswqs/nwi](https://source.coop/giswqs/nwi)                                                                                       |  82.4 GB |
| [planet/venezuela-earthquake-2026-06-24](https://source.coop/planet/venezuela-earthquake-2026-06-24)                               |  74.0 GB |
| [youssef-harby/egms-copernicus](https://source.coop/youssef-harby/egms-copernicus)                                                 |  73.0 GB |
| [nlebovits/jrc-glofas](https://source.coop/nlebovits/jrc-glofas)                                                                   |  70.8 GB |
| [vizzuality/hfp-100](https://source.coop/vizzuality/hfp-100)                                                                       |  70.4 GB |
| [cboettig/overturemaps](https://source.coop/cboettig/overturemaps)                                                                 |  69.3 GB |
| [pacificspatial/flateau](https://source.coop/pacificspatial/flateau)                                                               |  63.3 GB |
| [planet/rapidcrops](https://source.coop/planet/rapidcrops)                                                                         |  62.6 GB |
| [avikertesz/002](https://source.coop/avikertesz/002)                                                                               |  61.4 GB |
| [planet/eu-field-boundaries](https://source.coop/planet/eu-field-boundaries)                                                       |  61.3 GB |
| [fused/fsq-os-places](https://source.coop/fused/fsq-os-places)                                                                     |  60.3 GB |
| [bkr/aoml](https://source.coop/bkr/aoml)                                                                                           |  55.7 GB |
| [fiboa/data](https://source.coop/fiboa/data)                                                                                       |  49.9 GB |
| [reflective/geomipzarr](https://source.coop/reflective/geomipzarr)                                                                 |  47.3 GB |
| [cboettig/padus](https://source.coop/cboettig/padus)                                                                               |  46.7 GB |
| [tge-labs/mgrs](https://source.coop/tge-labs/mgrs)                                                                                 |  45.6 GB |
| [cboettig/high-seas](https://source.coop/cboettig/high-seas)                                                                       |  40.5 GB |
| [cboettig/census](https://source.coop/cboettig/census)                                                                             |  34.5 GB |
| [dataforcanada/d4c-datapkg-foundation](https://source.coop/dataforcanada/d4c-datapkg-foundation)                                   |  34.3 GB |
| [cboettig/population](https://source.coop/cboettig/population)                                                                     |  32.8 GB |
| [giswqs/depressions](https://source.coop/giswqs/depressions)                                                                       |  27.6 GB |
| [hdx/cod-ab](https://source.coop/hdx/cod-ab)                                                                                       |  26.6 GB |
| [ybyra-br/secondary-forest](https://source.coop/ybyra-br/secondary-forest)                                                         |  26.6 GB |
| [henryspatialanalysis/openpois](https://source.coop/henryspatialanalysis/openpois)                                                 |  25.9 GB |
| [smartmaps/foil4gr1](https://source.coop/smartmaps/foil4gr1)                                                                       |  25.0 GB |
| [cboettig/indigenous](https://source.coop/cboettig/indigenous)                                                                     |  23.2 GB |
| [cboettig/pad-us-3](https://source.coop/cboettig/pad-us-3)                                                                         |  21.9 GB |
| [seerai/hifld](https://source.coop/seerai/hifld)                                                                                   |  21.6 GB |
| [dynamical/asos-parquet](https://source.coop/dynamical/asos-parquet)                                                               |  20.1 GB |
| [clarkcga/hls-multi-temporal-cloud-gap-imputation](https://source.coop/clarkcga/hls-multi-temporal-cloud-gap-imputation)           |  18.1 GB |
| [giswqs/playa](https://source.coop/giswqs/playa)                                                                                   |  17.8 GB |
| [ftw/ftw-grid](https://source.coop/ftw/ftw-grid)                                                                                   |  17.8 GB |
| [opengeos/geoai](https://source.coop/opengeos/geoai)                                                                               |  17.7 GB |
| [geovibes/embeddings](https://source.coop/geovibes/embeddings)                                                                     |  17.5 GB |
| [vizzuality/lg-land-carbon-data](https://source.coop/vizzuality/lg-land-carbon-data)                                               |  17.2 GB |
| [youssef-harby/exiobase-3](https://source.coop/youssef-harby/exiobase-3)                                                           |  16.3 GB |
| [smartmaps/amx-2024-04](https://source.coop/smartmaps/amx-2024-04)                                                                 |  16.2 GB |
| [cboettig/sahara-trees](https://source.coop/cboettig/sahara-trees)                                                                 |  15.7 GB |
| [cboettig/inat](https://source.coop/cboettig/inat)                                                                                 |  15.1 GB |
| [giswqs/opengeos](https://source.coop/giswqs/opengeos)                                                                             |  14.8 GB |
| [youssef-harby/geoparquet-overviews](https://source.coop/youssef-harby/geoparquet-overviews)                                       |  14.4 GB |
| [cboettig/land-cover](https://source.coop/cboettig/land-cover)                                                                     |  14.2 GB |
| [zluo43/citibike](https://source.coop/zluo43/citibike)                                                                             |  14.1 GB |
| [cboettig/social-vulnerability](https://source.coop/cboettig/social-vulnerability)                                                 |  13.1 GB |
| [nlebovits/microsoft-ml-road-detections](https://source.coop/nlebovits/microsoft-ml-road-detections)                               |  11.4 GB |
| [planet/agroforestry-individual-tree-detection-india](https://source.coop/planet/agroforestry-individual-tree-detection-india)     |  11.3 GB |
| [ausantarctic/gebco](https://source.coop/ausantarctic/gebco)                                                                       |  11.1 GB |
| [planet/philippines-earthquake-2026-06-08](https://source.coop/planet/philippines-earthquake-2026-06-08)                           |  10.3 GB |
| [terrafloww/aef-v1-annual-rasteret](https://source.coop/terrafloww/aef-v1-annual-rasteret)                                         |   8.6 GB |
| [eco4cast/neon4cast-scores](https://source.coop/eco4cast/neon4cast-scores)                                                         |   7.7 GB |
| [clarkcga/multi-temporal-crop-classification](https://source.coop/clarkcga/multi-temporal-crop-classification)                     |   7.2 GB |
| [fiboa/japan](https://source.coop/fiboa/japan)                                                                                     |   6.7 GB |
| [cboettig/fire](https://source.coop/cboettig/fire)                                                                                 |   6.7 GB |
| [pacificspatial/vegetation-jp](https://source.coop/pacificspatial/vegetation-jp)                                                   |   6.7 GB |
| [fiboa/france-ec](https://source.coop/fiboa/france-ec)                                                                             |   6.5 GB |
| [planet/agroforestry-tree-species-identification-india](https://source.coop/planet/agroforestry-tree-species-identification-india) |   5.5 GB |
| [planet/disasterdata](https://source.coop/planet/disasterdata)                                                                     |   5.4 GB |
| [fiboa/us-usda-cropland](https://source.coop/fiboa/us-usda-cropland)                                                               |   5.3 GB |
| [rsignell/ncei-estuarine-bathymetry](https://source.coop/rsignell/ncei-estuarine-bathymetry)                                       |   5.3 GB |
| [alexgleith/gebco-2024](https://source.coop/alexgleith/gebco-2024)                                                                 |   4.6 GB |
| [fish-pace/pace-oci](https://source.coop/fish-pace/pace-oci)                                                                       |   4.5 GB |
| [cboettig/rivers](https://source.coop/cboettig/rivers)                                                                             |   4.4 GB |
| [fiboa/es-cl](https://source.coop/fiboa/es-cl)                                                                                     |   4.2 GB |
| [cboettig/fishbase](https://source.coop/cboettig/fishbase)                                                                         |   4.1 GB |
| [fused/hex](https://source.coop/fused/hex)                                                                                         |   3.6 GB |
| [clay/clay-model-v0-embeddings](https://source.coop/clay/clay-model-v0-embeddings)                                                 |   3.6 GB |
| [cboettig/ecoregion](https://source.coop/cboettig/ecoregion)                                                                       |   3.6 GB |
| [fiboa/at-crop](https://source.coop/fiboa/at-crop)                                                                                 |   3.4 GB |
| [fiboa/es-cm](https://source.coop/fiboa/es-cm)                                                                                     |   3.4 GB |
| [fiboa/es-vc](https://source.coop/fiboa/es-vc)                                                                                     |   3.2 GB |
| [nlebovits/eurosat-ms](https://source.coop/nlebovits/eurosat-ms)                                                                   |   3.2 GB |
| [englacial/bedmap](https://source.coop/englacial/bedmap)                                                                           |   3.2 GB |
| [avikertesz/001](https://source.coop/avikertesz/001)                                                                               |   3.1 GB |
| [ksa/kenol-section](https://source.coop/ksa/kenol-section)                                                                         |   3.0 GB |
| [cboettig/epa-water](https://source.coop/cboettig/epa-water)                                                                       |   2.8 GB |
| [cboettig/gfw](https://source.coop/cboettig/gfw)                                                                                   |   2.8 GB |
| [geographyis/wb-gad](https://source.coop/geographyis/wb-gad)                                                                       |   2.8 GB |
| [smartmaps/dem1a](https://source.coop/smartmaps/dem1a)                                                                             |   2.6 GB |
| [ganzk/ads](https://source.coop/ganzk/ads)                                                                                         |   2.5 GB |
| [fiboa/portugal](https://source.coop/fiboa/portugal)                                                                               |   2.4 GB |
| [fiboa/es-ar](https://source.coop/fiboa/es-ar)                                                                                     |   2.4 GB |
| [fiboa/es-an](https://source.coop/fiboa/es-an)                                                                                     |   2.3 GB |
| [fiboa/es-ex](https://source.coop/fiboa/es-ex)                                                                                     |   2.3 GB |
| [fiboa/es-cat](https://source.coop/fiboa/es-cat)                                                                                   |   2.2 GB |
| [fiboa/nl-crop](https://source.coop/fiboa/nl-crop)                                                                                 |   2.0 GB |
| [scar/distant](https://source.coop/scar/distant)                                                                                   |   1.9 GB |
| [fiboa/es-ga](https://source.coop/fiboa/es-ga)                                                                                     |   1.8 GB |
| [nlebovits/ign-argentina](https://source.coop/nlebovits/ign-argentina)                                                             |   1.8 GB |
| [pangeo/example-tiff](https://source.coop/pangeo/example-tiff)                                                                     |   1.6 GB |
| [cboettig/ca-dac](https://source.coop/cboettig/ca-dac)                                                                             |   1.6 GB |
| [englacial/zagg](https://source.coop/englacial/zagg)                                                                               |   1.5 GB |
| [fiboa/estonia-ec](https://source.coop/fiboa/estonia-ec)                                                                           |   1.4 GB |
| [walkthru-earth/opensensor-space](https://source.coop/walkthru-earth/opensensor-space)                                             |   1.4 GB |
| [cboettig/cpad](https://source.coop/cboettig/cpad)                                                                                 |   1.4 GB |
| [earthblox/cciwr](https://source.coop/earthblox/cciwr)                                                                             |   1.3 GB |
| [cboettig/taxadb](https://source.coop/cboettig/taxadb)                                                                             |   1.2 GB |
| [boston-university/bu-glance](https://source.coop/boston-university/bu-glance)                                                     |   1.2 GB |
| [tabaqat/riyadh-satellite-pmtiles](https://source.coop/tabaqat/riyadh-satellite-pmtiles)                                           |   1.1 GB |
| [ordnancesurvey/ngd-boundaries](https://source.coop/ordnancesurvey/ngd-boundaries)                                                 |   1.0 GB |
| [tabaqat/riyadh-sentinel-rgb](https://source.coop/tabaqat/riyadh-sentinel-rgb)                                                     | 964.8 MB |
| [smartmaps/next-ksj](https://source.coop/smartmaps/next-ksj)                                                                       | 962.3 MB |
| [cboettig/justice40](https://source.coop/cboettig/justice40)                                                                       | 937.8 MB |
| [youssef-harby/weather-station-realtime-parquet](https://source.coop/youssef-harby/weather-station-realtime-parquet)               | 925.8 MB |
| [cboettig/trails](https://source.coop/cboettig/trails)                                                                             | 923.2 MB |
| [fiboa/ec-lv](https://source.coop/fiboa/ec-lv)                                                                                     | 864.9 MB |
| [fiboa/austria](https://source.coop/fiboa/austria)                                                                                 | 831.3 MB |
| [tabaqat/geocoding-cng](https://source.coop/tabaqat/geocoding-cng)                                                                 | 820.0 MB |
| [fiboa/ireland](https://source.coop/fiboa/ireland)                                                                                 | 805.5 MB |
| [smartmaps/h3ys-worldpop](https://source.coop/smartmaps/h3ys-worldpop)                                                             | 777.5 MB |
| [fiboa/be-vlg](https://source.coop/fiboa/be-vlg)                                                                                   | 719.2 MB |
| [planet/esri-tutorial-data](https://source.coop/planet/esri-tutorial-data)                                                         | 716.6 MB |
| [smartmaps/dem10a](https://source.coop/smartmaps/dem10a)                                                                           | 698.5 MB |
| [smartmaps/mobility-gtfs-pmtiles](https://source.coop/smartmaps/mobility-gtfs-pmtiles)                                             | 685.2 MB |
| [fiboa/latvia](https://source.coop/fiboa/latvia)                                                                                   | 684.4 MB |
| [fiboa/nl-ref](https://source.coop/fiboa/nl-ref)                                                                                   | 676.2 MB |
| [englacial/ice-sheet-temperature](https://source.coop/englacial/ice-sheet-temperature)                                             | 676.1 MB |
| [nlebovits/censo-argentino](https://source.coop/nlebovits/censo-argentino)                                                         | 649.4 MB |
| [cboettig/us-boundaries](https://source.coop/cboettig/us-boundaries)                                                               | 644.7 MB |
| [tge-labs/admin-boundaries](https://source.coop/tge-labs/admin-boundaries)                                                         | 622.0 MB |
| [fiboa/es-pm](https://source.coop/fiboa/es-pm)                                                                                     | 612.0 MB |
| [fiboa/denmark](https://source.coop/fiboa/denmark)                                                                                 | 570.1 MB |
| [smartmaps/opencellid](https://source.coop/smartmaps/opencellid)                                                                   | 559.6 MB |
| [fiboa/finland](https://source.coop/fiboa/finland)                                                                                 | 558.1 MB |
| [fiboa/es-cb](https://source.coop/fiboa/es-cb)                                                                                     | 551.1 MB |
| [nlebovits/gaul-l2-admin](https://source.coop/nlebovits/gaul-l2-admin)                                                             | 509.1 MB |
| [fiboa/sweden](https://source.coop/fiboa/sweden)                                                                                   | 502.7 MB |
| [major-tom/index](https://source.coop/major-tom/index)                                                                             | 498.7 MB |
| [woodwell-climate/rangelands-raster-1](https://source.coop/woodwell-climate/rangelands-raster-1)                                   | 486.3 MB |
| [fiboa/croatia](https://source.coop/fiboa/croatia)                                                                                 | 481.2 MB |
| [cboettig/calenviroscreen](https://source.coop/cboettig/calenviroscreen)                                                           | 475.9 MB |
| [fiboa/slovakia](https://source.coop/fiboa/slovakia)                                                                               | 468.2 MB |
| [fiboa/czech](https://source.coop/fiboa/czech)                                                                                     | 458.2 MB |
| [cecil/forest-carbon-boundaries](https://source.coop/cecil/forest-carbon-boundaries)                                               | 453.5 MB |
| [cboettig/usfws](https://source.coop/cboettig/usfws)                                                                               | 447.2 MB |
| [fiboa/switzerland](https://source.coop/fiboa/switzerland)                                                                         | 445.3 MB |
| [cboettig/ncp](https://source.coop/cboettig/ncp)                                                                                   | 420.6 MB |
| [fiboa/slovenia-ec](https://source.coop/fiboa/slovenia-ec)                                                                         | 393.3 MB |
| [earthgenome/storm-events-db](https://source.coop/earthgenome/storm-events-db)                                                     | 373.7 MB |
| [fiboa/es-md](https://source.coop/fiboa/es-md)                                                                                     | 356.3 MB |
| [fiboa/slovenia](https://source.coop/fiboa/slovenia)                                                                               | 354.6 MB |
| [alukach/firesmoke](https://source.coop/alukach/firesmoke)                                                                         | 346.0 MB |
| [addresscloud/epc](https://source.coop/addresscloud/epc)                                                                           | 302.5 MB |
| [fiboa/es-nc](https://source.coop/fiboa/es-nc)                                                                                     | 293.8 MB |
| [fiboa/de-nrw](https://source.coop/fiboa/de-nrw)                                                                                   | 273.9 MB |
| [tabaqat/roads-overture-pmtiles](https://source.coop/tabaqat/roads-overture-pmtiles)                                               | 268.6 MB |
| [fiboa/de-nds](https://source.coop/fiboa/de-nds)                                                                                   | 252.2 MB |
| [cboettig/cgs](https://source.coop/cboettig/cgs)                                                                                   | 228.4 MB |
| [smartmaps/nagasaki-mago](https://source.coop/smartmaps/nagasaki-mago)                                                             | 220.7 MB |
| [earthgenome/amazon-mining-watch](https://source.coop/earthgenome/amazon-mining-watch)                                             | 213.3 MB |
| [fiboa/es-pv](https://source.coop/fiboa/es-pv)                                                                                     | 203.7 MB |
| [fiboa/us-ca-scm](https://source.coop/fiboa/us-ca-scm)                                                                             | 201.6 MB |
| [fiboa/de-th](https://source.coop/fiboa/de-th)                                                                                     | 179.7 MB |
| [fiboa/es-cn](https://source.coop/fiboa/es-cn)                                                                                     | 179.6 MB |
| [dataforcanada/d4c-datapkg-environment-climate-health](https://source.coop/dataforcanada/d4c-datapkg-environment-climate-health)   | 160.6 MB |
| [krishnaglodha/ksrsac-gis](https://source.coop/krishnaglodha/ksrsac-gis)                                                           | 160.2 MB |
| [smartmaps/toshik](https://source.coop/smartmaps/toshik)                                                                           | 159.9 MB |
| [fiboa/de-mv](https://source.coop/fiboa/de-mv)                                                                                     | 150.8 MB |
| [smartmaps/uppsala-conflict](https://source.coop/smartmaps/uppsala-conflict)                                                       | 136.2 MB |
| [fiboa/de-sax](https://source.coop/fiboa/de-sax)                                                                                   | 127.2 MB |
| [fiboa/be-wa](https://source.coop/fiboa/be-wa)                                                                                     | 126.2 MB |
| [nlebovits/pergamino-ide](https://source.coop/nlebovits/pergamino-ide)                                                             | 117.6 MB |
| [fiboa/lacunalabels](https://source.coop/fiboa/lacunalabels)                                                                       | 109.6 MB |
| [fiboa/de-bb](https://source.coop/fiboa/de-bb)                                                                                     | 102.8 MB |
| [streambatch/worldcereal](https://source.coop/streambatch/worldcereal)                                                             | 100.0 MB |
| [kerner-lab/fields-of-the-world-spain](https://source.coop/kerner-lab/fields-of-the-world-spain)                                   |  93.1 MB |
| [joshmoore/idr-ome-ngff-samples](https://source.coop/joshmoore/idr-ome-ngff-samples)                                               |  92.3 MB |
| [fiboa/de-sh](https://source.coop/fiboa/de-sh)                                                                                     |  87.6 MB |
| [cholmes/admin-boundaries](https://source.coop/cholmes/admin-boundaries)                                                           |  77.2 MB |
| [pangeo/geozarr-examples](https://source.coop/pangeo/geozarr-examples)                                                             |  75.7 MB |
| [cboettig/habitat-corridors](https://source.coop/cboettig/habitat-corridors)                                                       |  69.4 MB |
| [hdx/hapi](https://source.coop/hdx/hapi)                                                                                           |  66.3 MB |
| [kerner-lab/fields-of-the-world-latvia](https://source.coop/kerner-lab/fields-of-the-world-latvia)                                 |  57.6 MB |
| [rcejudo/000002](https://source.coop/rcejudo/000002)                                                                               |  54.3 MB |
| [fiboa/ai4sf](https://source.coop/fiboa/ai4sf)                                                                                     |  53.3 MB |
| [fiboa/de-sl](https://source.coop/fiboa/de-sl)                                                                                     |  47.5 MB |
| [tabaqat/gdelt-sa](https://source.coop/tabaqat/gdelt-sa)                                                                           |  47.0 MB |
| [kerner-lab/fields-of-the-world-estonia](https://source.coop/kerner-lab/fields-of-the-world-estonia)                               |  46.6 MB |
| [kerner-lab/fields-of-the-world-austria](https://source.coop/kerner-lab/fields-of-the-world-austria)                               |  43.9 MB |
| [kerner-lab/fields-of-the-world-croatia](https://source.coop/kerner-lab/fields-of-the-world-croatia)                               |  41.7 MB |
| [fiboa/luxembourg](https://source.coop/fiboa/luxembourg)                                                                           |  39.3 MB |
| [cboettig/mappinginequality](https://source.coop/cboettig/mappinginequality)                                                       |  28.7 MB |
| [kerner-lab/fields-of-the-world-slovakia](https://source.coop/kerner-lab/fields-of-the-world-slovakia)                             |  26.4 MB |
| [kerner-lab/fields-of-the-world-lithuania](https://source.coop/kerner-lab/fields-of-the-world-lithuania)                           |  26.2 MB |
| [kerner-lab/fields-of-the-world-finland](https://source.coop/kerner-lab/fields-of-the-world-finland)                               |  24.5 MB |
| [kerner-lab/fields-of-the-world-sweden](https://source.coop/kerner-lab/fields-of-the-world-sweden)                                 |  23.8 MB |
| [nlebovits/philly-zoning](https://source.coop/nlebovits/philly-zoning)                                                             |  23.7 MB |
| [fiboa/newzealand](https://source.coop/fiboa/newzealand)                                                                           |  23.4 MB |
| [geovibes/geometries](https://source.coop/geovibes/geometries)                                                                     |  22.1 MB |
| [kerner-lab/fields-of-the-world-netherlands](https://source.coop/kerner-lab/fields-of-the-world-netherlands)                       |  21.7 MB |
| [kerner-lab/fieldscapes-denmark](https://source.coop/kerner-lab/fieldscapes-denmark)                                               |  19.9 MB |
| [kerner-lab/fields-of-the-world-denmark](https://source.coop/kerner-lab/fields-of-the-world-denmark)                               |  19.9 MB |
| [kerner-lab/fields-of-the-world-cambodia](https://source.coop/kerner-lab/fields-of-the-world-cambodia)                             |  19.3 MB |
| [kerner-lab/fields-of-the-world-france](https://source.coop/kerner-lab/fields-of-the-world-france)                                 |  18.8 MB |
| [cboettig/conservation-policy](https://source.coop/cboettig/conservation-policy)                                                   |  18.3 MB |
| [kerner-lab/fields-of-the-world-belgium](https://source.coop/kerner-lab/fields-of-the-world-belgium)                               |  17.7 MB |
| [ecovoice/canada-energy-supply-and-demand](https://source.coop/ecovoice/canada-energy-supply-and-demand)                           |  17.1 MB |
| [kerner-lab/fields-of-the-world-luxembourg](https://source.coop/kerner-lab/fields-of-the-world-luxembourg)                         |  16.2 MB |
| [kerner-lab/fields-of-the-world-slovenia](https://source.coop/kerner-lab/fields-of-the-world-slovenia)                             |  15.1 MB |
| [cassiebuhler/30x30-state-policy](https://source.coop/cassiebuhler/30x30-state-policy)                                             |  15.0 MB |
| [kerner-lab/fields-of-the-world-vietnam](https://source.coop/kerner-lab/fields-of-the-world-vietnam)                               |  10.5 MB |
| [englacial/xopr](https://source.coop/englacial/xopr)                                                                               |   8.5 MB |
| [kerner-lab/fields-of-the-world-india](https://source.coop/kerner-lab/fields-of-the-world-india)                                   |   7.8 MB |
| [avikertesz/004](https://source.coop/avikertesz/004)                                                                               |   7.7 MB |
| [ecovoice/canada-solar-maps](https://source.coop/ecovoice/canada-solar-maps)                                                       |   6.2 MB |
| [kerner-lab/fields-of-the-world-germany](https://source.coop/kerner-lab/fields-of-the-world-germany)                               |   6.0 MB |
| [avikertesz/003](https://source.coop/avikertesz/003)                                                                               |   5.6 MB |
| [maxar/maxar-opendata](https://source.coop/maxar/maxar-opendata)                                                                   |   5.0 MB |
| [tabaqat/riyadh-places](https://source.coop/tabaqat/riyadh-places)                                                                 |   4.7 MB |
| [cholmes/nyc-taxi-zones](https://source.coop/cholmes/nyc-taxi-zones)                                                               |   3.5 MB |
| [mdsumner/mdstest2](https://source.coop/mdsumner/mdstest2)                                                                         |   3.2 MB |
| [kerner-lab/fields-of-the-world-portugal](https://source.coop/kerner-lab/fields-of-the-world-portugal)                             |   3.0 MB |
| [sarahgamal/overture-places-riyadh](https://source.coop/sarahgamal/overture-places-riyadh)                                         |   2.8 MB |
| [kerner-lab/fields-of-the-world-southafrica](https://source.coop/kerner-lab/fields-of-the-world-southafrica)                       |   2.0 MB |
| [kerner-lab/fields-of-the-world-corsica](https://source.coop/kerner-lab/fields-of-the-world-corsica)                               |   2.0 MB |
| [ecovoice/canada-natural-gas-imports-exports](https://source.coop/ecovoice/canada-natural-gas-imports-exports)                     |   2.0 MB |
| [geovibes/geovibes-datasets](https://source.coop/geovibes/geovibes-datasets)                                                       |   1.8 MB |
| [kerner-lab/fields-of-the-world-brazil](https://source.coop/kerner-lab/fields-of-the-world-brazil)                                 |   1.6 MB |
| [mdsumner/product](https://source.coop/mdsumner/product)                                                                           |   1.2 MB |
| [000123/000001](https://source.coop/000123/000001)                                                                                 | 773.3 KB |
| [ftw/ftw-inference-input](https://source.coop/ftw/ftw-inference-input)                                                             | 342.9 KB |
| [kerner-lab/fields-of-the-world-rwanda](https://source.coop/kerner-lab/fields-of-the-world-rwanda)                                 | 140.4 KB |
| [kerner-lab/fields-of-the-world-kenya](https://source.coop/kerner-lab/fields-of-the-world-kenya)                                   |  92.5 KB |
| [forestsignal/forestsignal-ca](https://source.coop/forestsignal/forestsignal-ca)                                                   |  598.0 B |

</details>

### BACKLOG

<details><summary>error step=gather-probe — 1 dataset · 39.0 TB</summary>

| repo                                                                   |   bytes |
| ---------------------------------------------------------------------- | ------: |
| [dynamical/dwd-icon-grib](https://source.coop/dynamical/dwd-icon-grib) | 39.0 TB |

</details>

<details><summary>all_failed .icechunk — 1 dataset · 1.0 TB</summary>

| repo                                     |  bytes |
| ---------------------------------------- | -----: |
| [bkr/cams](https://source.coop/bkr/cams) | 1.0 TB |

</details>

<details><summary>in s3, not yet seeded — 6 datasets · 735.8 GB</summary>

| repo                                                                                                                                     |    bytes |
| ---------------------------------------------------------------------------------------------------------------------------------------- | -------: |
| [dynamical/eccc-hrdps-grib](https://source.coop/dynamical/eccc-hrdps-grib)                                                               | 451.4 GB |
| [harvard-lil/nih](https://source.coop/harvard-lil/nih)                                                                                   | 220.5 GB |
| [harvard-lil/smithsonian-transcription-center](https://source.coop/harvard-lil/smithsonian-transcription-center)                         |  57.9 GB |
| [humane-intelligence/bias-bounty-mapping-equity-challenge](https://source.coop/humane-intelligence/bias-bounty-mapping-equity-challenge) |   5.7 GB |
| [hackl/euroflood-index](https://source.coop/hackl/euroflood-index)                                                                       | 138.8 MB |
| [tyler/iucn-get-vocabularies](https://source.coop/tyler/iucn-get-vocabularies)                                                           |   5.4 MB |

</details>

<details><summary>all_failed .filegdb — 1 dataset · 187.6 GB</summary>

| repo                                                       |    bytes |
| ---------------------------------------------------------- | -------: |
| [cboettig/wetlands](https://source.coop/cboettig/wetlands) | 187.6 GB |

</details>

<details><summary>amended (no format) — 1 dataset · 65.7 GB</summary>

| repo                                                       |   bytes |
| ---------------------------------------------------------- | ------: |
| [cholmes/eurocrops](https://source.coop/cholmes/eurocrops) | 65.7 GB |

</details>

<details><summary>all_failed .parquet — 1 dataset · 61.6 GB</summary>

| repo                                               |   bytes |
| -------------------------------------------------- | ------: |
| [cboettig/obis](https://source.coop/cboettig/obis) | 61.6 GB |

</details>

<details><summary>no_probe .fcb — 2 datasets · 4.2 GB</summary>

| repo                                                                                         |    bytes |
| -------------------------------------------------------------------------------------------- | -------: |
| [caires-tudelft/plateau-tokyo-fcb-2](https://source.coop/caires-tudelft/plateau-tokyo-fcb-2) |   4.1 GB |
| [caires-tudelft/tokyo-13999-fcb](https://source.coop/caires-tudelft/tokyo-13999-fcb)         | 122.2 MB |

</details>

<details><summary>all_failed .zarr — 1 dataset · 3.3 GB</summary>

| repo                                                                                             |  bytes |
| ------------------------------------------------------------------------------------------------ | -----: |
| [dynamical/dwd-icon-eu-forecast-5-day](https://source.coop/dynamical/dwd-icon-eu-forecast-5-day) | 3.3 GB |

</details>

<details><summary>no_probe .gpkg — 1 dataset · 24.6 MB</summary>

| repo                                                                                                                                                 |   bytes |
| ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------: |
| [alliance-bioversity-international-ciat/sample-earth-2026-co-gh](https://source.coop/alliance-bioversity-international-ciat/sample-earth-2026-co-gh) | 24.6 MB |

</details>

### SKIPPED

<details><summary>unlisted — 148 datasets · 560.0 TB</summary>

| repo                                                                                                                         |    bytes |
| ---------------------------------------------------------------------------------------------------------------------------- | -------: |
| [tessera/tessera](https://source.coop/tessera/tessera)                                                                       | 411.1 TB |
| [mvrl/amos-v1](https://source.coop/mvrl/amos-v1)                                                                             |  69.6 TB |
| [firststreet/aef-zarr](https://source.coop/firststreet/aef-zarr)                                                             |  54.7 TB |
| [clay/clay-v1-5-naip](https://source.coop/clay/clay-v1-5-naip)                                                               |   6.8 TB |
| [clay/clay-v1-5-sentinel2](https://source.coop/clay/clay-v1-5-sentinel2)                                                     |   3.2 TB |
| [zarr/landcovernet-zarr](https://source.coop/zarr/landcovernet-zarr)                                                         |   2.1 TB |
| [bkr/obs](https://source.coop/bkr/obs)                                                                                       |   1.7 TB |
| [harvard-lil/federal-github](https://source.coop/harvard-lil/federal-github)                                                 |   1.6 TB |
| [ftw/global-data-change](https://source.coop/ftw/global-data-change)                                                         |   1.5 TB |
| [mvrl/ftw-inference-gfm](https://source.coop/mvrl/ftw-inference-gfm)                                                         |   1.5 TB |
| [ftw/global-field-boundaries](https://source.coop/ftw/global-field-boundaries)                                               |   1.1 TB |
| [earthgenome/s2-embeddings](https://source.coop/earthgenome/s2-embeddings)                                                   | 999.7 GB |
| [vida/merged-google-microsoft-open-buildings](https://source.coop/vida/merged-google-microsoft-open-buildings)               | 843.8 GB |
| [diegovd/geo-data-test](https://source.coop/diegovd/geo-data-test)                                                           | 385.5 GB |
| [dynamical/noaa-gfs-analysis-hourly](https://source.coop/dynamical/noaa-gfs-analysis-hourly)                                 | 342.3 GB |
| [major-tom/landsatl8toa](https://source.coop/major-tom/landsatl8toa)                                                         | 337.1 GB |
| [epoch/forest-typology-2020](https://source.coop/epoch/forest-typology-2020)                                                 | 333.3 GB |
| [mlcommons/unsupservised-peoples-speech](https://source.coop/mlcommons/unsupservised-peoples-speech)                         | 258.3 GB |
| [epoch/jrc-tmf](https://source.coop/epoch/jrc-tmf)                                                                           | 125.9 GB |
| [giswqs/building-height](https://source.coop/giswqs/building-height)                                                         | 115.8 GB |
| [e4drr-project/forecasts](https://source.coop/e4drr-project/forecasts)                                                       | 104.7 GB |
| [ftw/ftw-planet](https://source.coop/ftw/ftw-planet)                                                                         | 102.3 GB |
| [cboettig/us-rivers](https://source.coop/cboettig/us-rivers)                                                                 |  99.3 GB |
| [isaaccorley/ftw-scratchpad](https://source.coop/isaaccorley/ftw-scratchpad)                                                 |  89.2 GB |
| [luddaludwig/boreal-fire-carbon](https://source.coop/luddaludwig/boreal-fire-carbon)                                         |  74.3 GB |
| [kerner-lab/fields-of-the-world-archive](https://source.coop/kerner-lab/fields-of-the-world-archive)                         |  56.8 GB |
| [wri-data-lab/trazofields](https://source.coop/wri-data-lab/trazofields)                                                     |  54.8 GB |
| [giswqs/biomass](https://source.coop/giswqs/biomass)                                                                         |  47.0 GB |
| [clay/california-naip-clay-v1](https://source.coop/clay/california-naip-clay-v1)                                             |  46.8 GB |
| [e4drr-project/observations](https://source.coop/e4drr-project/observations)                                                 |  44.0 GB |
| [ftw/ftw-inference-output](https://source.coop/ftw/ftw-inference-output)                                                     |  37.3 GB |
| [tristangruppwri/trazofields](https://source.coop/tristangruppwri/trazofields)                                               |  29.2 GB |
| [opengeos/us-buildings](https://source.coop/opengeos/us-buildings)                                                           |  28.4 GB |
| [ftw/financial-times](https://source.coop/ftw/financial-times)                                                               |  22.8 GB |
| [cholmes/fiboa-scratch](https://source.coop/cholmes/fiboa-scratch)                                                           |  21.7 GB |
| [khvzix/delineate-anything-fields](https://source.coop/khvzix/delineate-anything-fields)                                     |  21.7 GB |
| [luddaludwig/potential-agc-combustion-ssp585-v0](https://source.coop/luddaludwig/potential-agc-combustion-ssp585-v0)         |  21.4 GB |
| [fiboa/mgrs](https://source.coop/fiboa/mgrs)                                                                                 |  21.1 GB |
| [amitbajaj/testrepo401](https://source.coop/amitbajaj/testrepo401)                                                           |  21.0 GB |
| [berkeley-dse/mrcl](https://source.coop/berkeley-dse/mrcl)                                                                   |  20.2 GB |
| [epoch/global-natural-planted-forests](https://source.coop/epoch/global-natural-planted-forests)                             |  18.3 GB |
| [cholmes/nhd](https://source.coop/cholmes/nhd)                                                                               |  17.0 GB |
| [ftw/usda-csb](https://source.coop/ftw/usda-csb)                                                                             |  14.9 GB |
| [ondata/cadastral-italy-geospatial-data](https://source.coop/ondata/cadastral-italy-geospatial-data)                         |  14.7 GB |
| [ftw/aef-field-boundaries](https://source.coop/ftw/aef-field-boundaries)                                                     |  12.4 GB |
| [tge-labs/mind](https://source.coop/tge-labs/mind)                                                                           |  12.1 GB |
| [calebrob6/geospatialml](https://source.coop/calebrob6/geospatialml)                                                         |  12.0 GB |
| [avineon-tensing/england-trees-outside-woodland-tow](https://source.coop/avineon-tensing/england-trees-outside-woodland-tow) |  11.9 GB |
| [jwasserman/geoparquet-spatial-query-testing](https://source.coop/jwasserman/geoparquet-spatial-query-testing)               |  11.5 GB |
| [calebrob6/venezuela-2026-earthquake-planet-aois](https://source.coop/calebrob6/venezuela-2026-earthquake-planet-aois)       |  11.3 GB |
| [major-tom/esaworldcover](https://source.coop/major-tom/esaworldcover)                                                       |  10.9 GB |
| [cholmes/stac-geoparquet-public](https://source.coop/cholmes/stac-geoparquet-public)                                         |  10.9 GB |
| [mindearth/wsf](https://source.coop/mindearth/wsf)                                                                           |  10.7 GB |
| [source/manifests](https://source.coop/source/manifests)                                                                     |   8.0 GB |
| [cholmes/openet-demo](https://source.coop/cholmes/openet-demo)                                                               |   6.8 GB |
| [hirooimaki/vegetation-jp](https://source.coop/hirooimaki/vegetation-jp)                                                     |   6.7 GB |
| [amitbajaj/repotoday](https://source.coop/amitbajaj/repotoday)                                                               |   6.2 GB |
| [rsignell/esip2025](https://source.coop/rsignell/esip2025)                                                                   |   5.3 GB |
| [cholmes/aois](https://source.coop/cholmes/aois)                                                                             |   5.1 GB |
| [vida/dre-atlas](https://source.coop/vida/dre-atlas)                                                                         |   4.8 GB |
| [m-mohr/ftw-confidence-layers](https://source.coop/m-mohr/ftw-confidence-layers)                                             |   4.5 GB |
| [root-geospatial/flight-counts](https://source.coop/root-geospatial/flight-counts)                                           |   4.4 GB |
| [caires-tudelft/plateau-tokyo-fcb](https://source.coop/caires-tudelft/plateau-tokyo-fcb)                                     |   3.9 GB |
| [cholmes/os-opendata-cng](https://source.coop/cholmes/os-opendata-cng)                                                       |   3.9 GB |
| [brunosan/clay-model-v0-embeddings](https://source.coop/brunosan/clay-model-v0-embeddings)                                   |   3.6 GB |
| [nishadhka/aq-icechunk-store-ifs](https://source.coop/nishadhka/aq-icechunk-store-ifs)                                       |   2.7 GB |
| [espm-288/espm-288-testing](https://source.coop/espm-288/espm-288-testing)                                                   |   2.3 GB |
| [tyler/usda-nass-cdl](https://source.coop/tyler/usda-nass-cdl)                                                               |   2.1 GB |
| [tyler/gadm](https://source.coop/tyler/gadm)                                                                                 |   2.0 GB |
| [tristangruppwri/trazotraining](https://source.coop/tristangruppwri/trazotraining)                                           |   1.9 GB |
| [wri-data-lab/trazoannotations](https://source.coop/wri-data-lab/trazoannotations)                                           |   1.9 GB |
| [vdavez/usaspending-data](https://source.coop/vdavez/usaspending-data)                                                       |   1.9 GB |
| [tyler/colombia-ecosystems-map](https://source.coop/tyler/colombia-ecosystems-map)                                           |   1.4 GB |
| [harvard-lil/data-gov-metadata](https://source.coop/harvard-lil/data-gov-metadata)                                           |   1.3 GB |
| [youssef-harby/cloud-native-geocoding](https://source.coop/youssef-harby/cloud-native-geocoding)                             |   1.1 GB |
| [amitbajaj/testrepo12](https://source.coop/amitbajaj/testrepo12)                                                             |   1.1 GB |
| [idi/scout-test-repo](https://source.coop/idi/scout-test-repo)                                                               | 806.8 MB |
| [alukach/test-product](https://source.coop/alukach/test-product)                                                             | 756.1 MB |
| [ktyle/metar2024](https://source.coop/ktyle/metar2024)                                                                       | 682.4 MB |
| [cboettig/ca30x30](https://source.coop/cboettig/ca30x30)                                                                     | 457.5 MB |
| [smartmaps/sugi](https://source.coop/smartmaps/sugi)                                                                         | 395.0 MB |
| [cr458/google](https://source.coop/cr458/google)                                                                             | 392.7 MB |
| [ome/sample-images](https://source.coop/ome/sample-images)                                                                   | 340.6 MB |
| [smartmaps/rwanda10](https://source.coop/smartmaps/rwanda10)                                                                 | 337.0 MB |
| [englacial/ismip6-combined](https://source.coop/englacial/ismip6-combined)                                                   | 320.3 MB |
| [epoch/global-forest-loss-drivers](https://source.coop/epoch/global-forest-loss-drivers)                                     | 302.0 MB |
| [kbgg/test](https://source.coop/kbgg/test)                                                                                   | 290.9 MB |
| [cholmes/stac-geoparquet-s2l2a](https://source.coop/cholmes/stac-geoparquet-s2l2a)                                           | 275.1 MB |
| [cboettig/288-demo](https://source.coop/cboettig/288-demo)                                                                   | 230.0 MB |
| [smartmaps/rw-wip-2024-05-31](https://source.coop/smartmaps/rw-wip-2024-05-31)                                               | 226.5 MB |
| [roorda-tudelft/public-trees-in-nl](https://source.coop/roorda-tudelft/public-trees-in-nl)                                   | 220.9 MB |
| [smartmaps/tmet](https://source.coop/smartmaps/tmet)                                                                         | 193.1 MB |
| [zarr/geozarr-tests](https://source.coop/zarr/geozarr-tests)                                                                 | 156.6 MB |
| [eeholmes/cefi](https://source.coop/eeholmes/cefi)                                                                           | 138.5 MB |
| [m-mohr/test](https://source.coop/m-mohr/test)                                                                               | 115.3 MB |
| [alukach/alukach-experimentation](https://source.coop/alukach/alukach-experimentation)                                       | 107.7 MB |
| [michelle/test](https://source.coop/michelle/test)                                                                           | 102.8 MB |
| [kerner-lab/fieldscapes-spain](https://source.coop/kerner-lab/fieldscapes-spain)                                             |  93.1 MB |
| [kerner-lab/fieldscapes-latvia](https://source.coop/kerner-lab/fieldscapes-latvia)                                           |  57.6 MB |
| [kerner-lab/fieldscapes-estonia](https://source.coop/kerner-lab/fieldscapes-estonia)                                         |  46.6 MB |
| [kerner-lab/fieldscapes-austria](https://source.coop/kerner-lab/fieldscapes-austria)                                         |  43.9 MB |
| [kerner-lab/fieldscapes-romania](https://source.coop/kerner-lab/fieldscapes-romania)                                         |  43.4 MB |
| [kerner-lab/fieldscapes-croatia](https://source.coop/kerner-lab/fieldscapes-croatia)                                         |  41.7 MB |
| [ftw/ftw-tests](https://source.coop/ftw/ftw-tests)                                                                           |  38.4 MB |
| [kerner-lab/fieldscapes-slovakia](https://source.coop/kerner-lab/fieldscapes-slovakia)                                       |  26.4 MB |
| [kerner-lab/fieldscapes-lithuania](https://source.coop/kerner-lab/fieldscapes-lithuania)                                     |  26.2 MB |
| [kerner-lab/fieldscapes-finland](https://source.coop/kerner-lab/fieldscapes-finland)                                         |  24.5 MB |
| [kerner-lab/fieldscapes-sweden](https://source.coop/kerner-lab/fieldscapes-sweden)                                           |  23.8 MB |
| [cholmes/s2-grid](https://source.coop/cholmes/s2-grid)                                                                       |  23.0 MB |
| [kerner-lab/fieldscapes-netherlands](https://source.coop/kerner-lab/fieldscapes-netherlands)                                 |  21.7 MB |
| [kerner-lab/fieldscapes-cambodia](https://source.coop/kerner-lab/fieldscapes-cambodia)                                       |  19.3 MB |
| [kerner-lab/fieldscapes-france](https://source.coop/kerner-lab/fieldscapes-france)                                           |  18.8 MB |
| [kerner-lab/fieldscapes-belgium](https://source.coop/kerner-lab/fieldscapes-belgium)                                         |  17.7 MB |
| [kerner-lab/fieldscapes-luxembourg](https://source.coop/kerner-lab/fieldscapes-luxembourg)                                   |  16.2 MB |
| [kerner-lab/fieldscapes-slovenia](https://source.coop/kerner-lab/fieldscapes-slovenia)                                       |  15.1 MB |
| [kerner-lab/fieldscapes-vietnam](https://source.coop/kerner-lab/fieldscapes-vietnam)                                         |  10.5 MB |
| [kerner-lab/fieldscapes-india](https://source.coop/kerner-lab/fieldscapes-india)                                             |   7.8 MB |
| [kerner-lab/fieldscapes-germany](https://source.coop/kerner-lab/fieldscapes-germany)                                         |   6.0 MB |
| [dnwaeze/kenol-section](https://source.coop/dnwaeze/kenol-section)                                                           |   5.8 MB |
| [cholmes/gur-shadow-fleet](https://source.coop/cholmes/gur-shadow-fleet)                                                     |   3.7 MB |
| [tyler/maxar-opendata-v1-1](https://source.coop/tyler/maxar-opendata-v1-1)                                                   |   3.6 MB |
| [mcgeo/testing-diligence](https://source.coop/mcgeo/testing-diligence)                                                       |   3.2 MB |
| [kerner-lab/fieldscapes-portugal](https://source.coop/kerner-lab/fieldscapes-portugal)                                       |   3.0 MB |
| [kerner-lab/fieldscapes](https://source.coop/kerner-lab/fieldscapes)                                                         |   2.9 MB |
| [csaybar/3dclouds](https://source.coop/csaybar/3dclouds)                                                                     |   2.8 MB |
| [val/test-prod-vp](https://source.coop/val/test-prod-vp)                                                                     |   2.6 MB |
| [tyler/test-tiff-not-cloud-optimized](https://source.coop/tyler/test-tiff-not-cloud-optimized)                               |   2.2 MB |
| [kerner-lab/fieldscapes-southafrica](https://source.coop/kerner-lab/fieldscapes-southafrica)                                 |   2.0 MB |
| [kerner-lab/fieldscapes-corsica](https://source.coop/kerner-lab/fieldscapes-corsica)                                         |   2.0 MB |
| [source/source-stats](https://source.coop/source/source-stats)                                                               |   2.0 MB |
| [amitbajaj/canada-natural-gas-imports-exports](https://source.coop/amitbajaj/canada-natural-gas-imports-exports)             |   2.0 MB |
| [kerner-lab/fieldscapes-brazil](https://source.coop/kerner-lab/fieldscapes-brazil)                                           |   1.4 MB |
| [michelle/test-v3](https://source.coop/michelle/test-v3)                                                                     |   1.4 MB |
| [eeholmes/chlaz](https://source.coop/eeholmes/chlaz)                                                                         |   1.2 MB |
| [pangeo/earth-data-examples](https://source.coop/pangeo/earth-data-examples)                                                 |   1.1 MB |
| [streambatch/usda-county-boundaries-2017](https://source.coop/streambatch/usda-county-boundaries-2017)                       | 931.4 KB |
| [rti/rwanda-crop-landcover-labels](https://source.coop/rti/rwanda-crop-landcover-labels)                                     | 475.7 KB |
| [source/cmr-metadata](https://source.coop/source/cmr-metadata)                                                               | 354.3 KB |
| [idi/idi-source-coop-test01](https://source.coop/idi/idi-source-coop-test01)                                                 | 348.0 KB |
| [rsignell/liveocean](https://source.coop/rsignell/liveocean)                                                                 | 235.8 KB |
| [rti-international/2023-002](https://source.coop/rti-international/2023-002)                                                 | 218.2 KB |
| [rti-international/2023-001](https://source.coop/rti-international/2023-001)                                                 | 163.1 KB |
| [kerner-lab/fieldscapes-rwanda](https://source.coop/kerner-lab/fieldscapes-rwanda)                                           | 140.4 KB |
| [kerner-lab/fieldscapes-kenya](https://source.coop/kerner-lab/fieldscapes-kenya)                                             |  92.5 KB |
| [auspatious/lulc-sids](https://source.coop/auspatious/lulc-sids)                                                             |  89.5 KB |
| [notoncebut2x/youthmappers](https://source.coop/notoncebut2x/youthmappers)                                                   |  71.8 KB |
| [youthmappers/ym-tz-crop-survey-2023](https://source.coop/youthmappers/ym-tz-crop-survey-2023)                               |  71.8 KB |
| [source/sites.source.coop](https://source.coop/source/sites.source.coop)                                                     |  21.5 KB |

</details>

<details><summary>not_geo — 19 datasets · 61.8 TB</summary>

| repo                                                                                                   |    bytes |
| ------------------------------------------------------------------------------------------------------ | -------: |
| [agentmorris/lila-wildlife](https://source.coop/agentmorris/lila-wildlife)                             |  43.3 TB |
| [harvard-lil/gov-data](https://source.coop/harvard-lil/gov-data)                                       |  17.9 TB |
| [taco/methaneset](https://source.coop/taco/methaneset)                                                 | 325.0 GB |
| [wadhwani-ai/wiai-pm-open-data](https://source.coop/wadhwani-ai/wiai-pm-open-data)                     |  91.8 GB |
| [csaybar/methaneset](https://source.coop/csaybar/methaneset)                                           |  62.2 GB |
| [planet/skyscraper](https://source.coop/planet/skyscraper)                                             |  44.6 GB |
| [dataforcanada/d4c-datapkg-field-imagery](https://source.coop/dataforcanada/d4c-datapkg-field-imagery) |  10.9 GB |
| [jrc-lucas/jrc-lucas-ml](https://source.coop/jrc-lucas/jrc-lucas-ml)                                   |   3.3 GB |
| [taco/darktom](https://source.coop/taco/darktom)                                                       |   3.0 GB |
| [jianbo/gndc-higlass-ls20](https://source.coop/jianbo/gndc-higlass-ls20)                               | 720.9 MB |
| [troyschmidt/hurrevac-storm-advisories](https://source.coop/troyschmidt/hurrevac-storm-advisories)     | 321.4 MB |
| [cboettig/mobi](https://source.coop/cboettig/mobi)                                                     | 283.4 MB |
| [catalystcoop/pudl](https://source.coop/catalystcoop/pudl)                                             |  42.1 MB |
| [fiboa/br-ba-lem](https://source.coop/fiboa/br-ba-lem)                                                 |   7.3 MB |
| [source/metadata-catalog](https://source.coop/source/metadata-catalog)                                 |   3.9 MB |
| [youssef-harby/overture-maps-stac](https://source.coop/youssef-harby/overture-maps-stac)               | 718.0 KB |
| [asterisk-labs/cozip](https://source.coop/asterisk-labs/cozip)                                         |  98.5 KB |
| [fish-pace/chla-z](https://source.coop/fish-pace/chla-z)                                               |  12.0 KB |
| [cboettig/glen](https://source.coop/cboettig/glen)                                                     |  10.9 KB |

</details>

<details><summary>test_repo — 7 datasets · 1.9 TB</summary>

| repo                                                                                   |    bytes |
| -------------------------------------------------------------------------------------- | -------: |
| [rseg/long-lfmc-test](https://source.coop/rseg/long-lfmc-test)                         |   1.9 TB |
| [mcox/testkrillswarm](https://source.coop/mcox/testkrillswarm)                         | 983.6 MB |
| [cholmes/gpio-test](https://source.coop/cholmes/gpio-test)                             | 239.2 MB |
| [nlebovits/moldova-test-data](https://source.coop/nlebovits/moldova-test-data)         | 215.6 MB |
| [severo/apache-parquet-testing](https://source.coop/severo/apache-parquet-testing)     |   4.1 MB |
| [tyler/test-files](https://source.coop/tyler/test-files)                               | 701.4 KB |
| [severo/csv-papaparse-test-files](https://source.coop/severo/csv-papaparse-test-files) |  72.4 KB |

</details>

<details><summary>tiny — 22 datasets · 30.6 KB</summary>

| repo                                                                                               |   bytes |
| -------------------------------------------------------------------------------------------------- | ------: |
| [tabaqat/riyadh-places-geoparquet](https://source.coop/tabaqat/riyadh-places-geoparquet)           |  5.8 KB |
| [tomr/gri-datapkg](https://source.coop/tomr/gri-datapkg)                                           |  5.6 KB |
| [carbonplan/ccarbonplan-ocr](https://source.coop/carbonplan/ccarbonplan-ocr)                       |  5.4 KB |
| [opsis-oxford/global-econ-data](https://source.coop/opsis-oxford/global-econ-data)                 |  3.1 KB |
| [wherobots/human-modification](https://source.coop/wherobots/human-modification)                   |  2.6 KB |
| [iceberg/s3_access_logs](https://source.coop/iceberg/s3_access_logs)                               |  2.6 KB |
| [iceberg/s3_logs_hourly_stats](https://source.coop/iceberg/s3_logs_hourly_stats)                   |  1.7 KB |
| [nlebovits/philadelphia-aerial-imagery](https://source.coop/nlebovits/philadelphia-aerial-imagery) |  1.2 KB |
| [fiboa/spain](https://source.coop/fiboa/spain)                                                     |  1.2 KB |
| [tyler/tylers-test-product-id](https://source.coop/tyler/tylers-test-product-id)                   | 548.0 B |
| [saraka/test-1](https://source.coop/saraka/test-1)                                                 | 343.0 B |
| [bkr/gmgsi](https://source.coop/bkr/gmgsi)                                                         | 209.0 B |
| [kbgg/auth-test](https://source.coop/kbgg/auth-test)                                               | 122.0 B |
| [opsis-oxford/test](https://source.coop/opsis-oxford/test)                                         |  35.0 B |
| [berkeley-dse/california-ace](https://source.coop/berkeley-dse/california-ace)                     |  18.0 B |
| [major-tom/Core-S2L1C](https://source.coop/major-tom/Core-S2L1C)                                   |   3.0 B |
| [major-tom/core-s2l1c](https://source.coop/major-tom/core-s2l1c)                                   |   3.0 B |
| [geovibes/embedding-ftw](https://source.coop/geovibes/embedding-ftw)                               |   0.0 B |
| [jacobsn/amos-v1](https://source.coop/jacobsn/amos-v1)                                             |   0.0 B |
| [jcushman/test](https://source.coop/jcushman/test)                                                 |   0.0 B |
| [kbgg/foobar](https://source.coop/kbgg/foobar)                                                     |   0.0 B |
| [ncar/eol](https://source.coop/ncar/eol)                                                           |   0.0 B |

</details>

### UNREGISTERED

<details><summary>stowaways — 40 datasets · 924.6 TB</summary>

| repo                                                      |    bytes |
| --------------------------------------------------------- | -------: |
| tge-labs/ftw-global-data                                  | 353.1 TB |
| ncar/corona                                               | 257.7 TB |
| tge-labs/aef-mosaic-backfill                              | 122.6 TB |
| ncar/mlso                                                 |  65.0 TB |
| ncar/gdex                                                 |  62.6 TB |
| mlcommons/unsupervised-peoples-speech                     |  47.6 TB |
| tge-labs/ftw-aef-mosaic                                   |  12.1 TB |
| dynamical/noaa-hrrr-analysis                              |   2.7 TB |
| google-research-open-buildings/fgb-s2                     | 487.0 GB |
| google-research-open-buildings/v2                         | 240.6 GB |
| geovibes/experiments                                      | 163.8 GB |
| google-research-open-buildings/geoparquet-by-country      | 161.1 GB |
| google-research-open-buildings/geoparquet-s2-more-columns | 150.2 GB |
| harvard-lil/batch-operations                              |  38.9 GB |
| vnp46a1_thermal_anomaly/classification                    |  23.9 GB |
| harvard-lil/inventories                                   |  22.0 GB |
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
| nlebovits/landsat-lst                                     |  15.6 MB |
| ausantarctic/mdstest                                      |  13.0 MB |
| nlebovits/pasda-flat                                      |   8.0 MB |
| mdsumner/mdstest                                          |   2.8 MB |
| nlebovits/landsat-lst-test                                |   2.0 MB |
| sarahgamal/riyadh-places                                  | 455.4 KB |
| benchmark/tasks                                           | 430.9 KB |
| benchmark/uploads                                         | 210.0 KB |
| ecovoice/test-repo                                        |  21.9 KB |

</details>


## Integrity

| subreport | meaning                                          | count |    bytes |
| --------- | ------------------------------------------------ | ----: | -------: |
| ghosts    | catalog entry, no S3 data                        |    49 |  29.7 TB |
| stowaways | S3 data, no source.coop product                  |    40 | 924.6 TB |
| stale     | catalog bytes ≠ S3 (fixed by `make process-all`) |    36 |   1.4 PB |

<details><summary>ghosts — 49 datasets</summary>

| repo                                                            | state   | catalog claims |
| --------------------------------------------------------------- | ------- | -------------: |
| agentmorris/lila-wildlife-snapshotserengeti-unzipped            | seed    |         6.1 TB |
| agentmorris/lila-wildlife-snapshot-safari-2024-expansion        | seed    |         5.0 TB |
| agentmorris/lila-wildlife-idaho-camera-traps                    | seed    |         3.1 TB |
| agentmorris/lila-wildlife-swg-camera-traps                      | seed    |         2.8 TB |
| agentmorris/lila-wildlife-nz-trailcams                          | seed    |         2.1 TB |
| agentmorris/lila-wildlife-noaa-kotz                             | seed    |         1.7 TB |
| agentmorris/lila-wildlife-nacti-unzipped                        | drafted |         1.5 TB |
| agentmorris/lila-wildlife-lcmcvpr2019                           | drafted |       886.7 GB |
| agentmorris/lila-wildlife-california-small-animals              | seed    |       790.5 GB |
| agentmorris/lila-wildlife-geolifeclef-2020                      | seed    |       780.3 GB |
| agentmorris/lila-wildlife-nz-thermal                            | seed    |       677.4 GB |
| agentmorris/lila-wildlife-wcs-unzipped                          | seed    |       594.6 GB |
| agentmorris/lila-wildlife-snapshot-safari                       | seed    |       542.3 GB |
| agentmorris/lila-wildlife-nkhotakota-camera-traps               | seed    |       337.5 GB |
| agentmorris/lila-wildlife-seattleish-camera-traps               | seed    |       321.2 GB |
| agentmorris/lila-wildlife-izembek-lagoon-birds                  | seed    |       265.4 GB |
| agentmorris/lila-wildlife-community-fish-detection-dataset      | seed    |       261.1 GB |
| agentmorris/lila-wildlife-lindenthal-camera-traps               | seed    |       213.1 GB |
| agentmorris/lila-wildlife-wni-giraffes                          | seed    |       200.7 GB |
| agentmorris/lila-wildlife-wellington-unzipped                   | seed    |       198.4 GB |
| agentmorris/lila-wildlife-channel-islands-camera-traps          | seed    |       186.4 GB |
| agentmorris/lila-wildlife-islandconservationcameratraps         | seed    |       164.0 GB |
| agentmorris/lila-wildlife-desert-lion-camera-traps              | seed    |       154.7 GB |
| agentmorris/lila-wildlife-orinoquia-camera-traps                | seed    |       154.5 GB |
| agentmorris/lila-wildlife-unsw-predators                        | seed    |       130.4 GB |
| agentmorris/lila-wildlife-caltech-unzipped                      | seed    |       112.4 GB |
| agentmorris/lila-wildlife-conservationdrones                    | seed    |        98.3 GB |
| agentmorris/lila-wildlife-icimod-glacier-mapping                | seed    |        73.9 GB |
| agentmorris/lila-wildlife-biome-health-project-maasai-mara-2018 | seed    |        64.0 GB |
| agentmorris/lila-wildlife-boise-state-vegetation                | drafted |        62.9 GB |
| agentmorris/lila-wildlife-osu-small-animals                     | seed    |        60.8 GB |
| agentmorris/lila-wildlife-wild-me                               | seed    |        29.6 GB |
| agentmorris/lila-wildlife-missouricameratraps                   | seed    |        20.5 GB |
| agentmorris/lila-wildlife-ena24                                 | seed    |         7.8 GB |
| agentmorris/lila-wildlife-noaa-psnf                             | seed    |         7.7 GB |
| harvard-lil/duckdb-test                                         | seed    |         5.3 GB |
| agentmorris/lila-wildlife-cvwc2019                              | drafted |         4.4 GB |
| dataforcanada/ca-orthoimagery-labs                              | seed    |         4.3 GB |
| agentmorris/lila-wildlife-larch-casebearer                      | seed    |         3.5 GB |
| agentmorris/lila-wildlife-aerial-birds-west-africa              | drafted |         2.4 GB |
| agentmorris/lila-wildlife-boxes-on-bees                         | seed    |         2.1 GB |
| agentmorris/lila-wildlife-sea-star-re-id                        | seed    |         1.9 GB |
| tge-labs/tessera                                                | seed    |         1.1 GB |
| agentmorris/lila-wildlife-uas-imagery-of-migratory-waterfowl    | seed    |       337.8 MB |
| agentmorris/lila-wildlife-adkres-invasive                       | seed    |       158.7 MB |
| harvard-lil/staging-gov-data                                    | seed    |       157.2 MB |
| major-tom/copernicusdem                                         | seed    |        13.1 MB |
| tge-labs/terrabit                                               | seed    |         6.6 MB |
| dataforcanada/ca-foundation-labs                                | seed    |        86.9 KB |

</details>

<details><summary>stowaways — 40 datasets</summary>

| repo                                                      |    bytes |
| --------------------------------------------------------- | -------: |
| tge-labs/ftw-global-data                                  | 353.1 TB |
| ncar/corona                                               | 257.7 TB |
| tge-labs/aef-mosaic-backfill                              | 122.6 TB |
| ncar/mlso                                                 |  65.0 TB |
| ncar/gdex                                                 |  62.6 TB |
| mlcommons/unsupervised-peoples-speech                     |  47.6 TB |
| tge-labs/ftw-aef-mosaic                                   |  12.1 TB |
| dynamical/noaa-hrrr-analysis                              |   2.7 TB |
| google-research-open-buildings/fgb-s2                     | 487.0 GB |
| google-research-open-buildings/v2                         | 240.6 GB |
| geovibes/experiments                                      | 163.8 GB |
| google-research-open-buildings/geoparquet-by-country      | 161.1 GB |
| google-research-open-buildings/geoparquet-s2-more-columns | 150.2 GB |
| harvard-lil/batch-operations                              |  38.9 GB |
| vnp46a1_thermal_anomaly/classification                    |  23.9 GB |
| harvard-lil/inventories                                   |  22.0 GB |
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
| nlebovits/landsat-lst                                     |  15.6 MB |
| ausantarctic/mdstest                                      |  13.0 MB |
| nlebovits/pasda-flat                                      |   8.0 MB |
| mdsumner/mdstest                                          |   2.8 MB |
| nlebovits/landsat-lst-test                                |   2.0 MB |
| sarahgamal/riyadh-places                                  | 455.4 KB |
| benchmark/tasks                                           | 430.9 KB |
| benchmark/uploads                                         | 210.0 KB |
| ecovoice/test-repo                                        |  21.9 KB |

</details>

<details><summary>stale — 36 datasets</summary>

| repo                                                |        catalog → S3 |
| --------------------------------------------------- | ------------------: |
| tessera/tessera                                     | 227.9 TB → 411.1 TB |
| harvard-lil/smithsonian-open-access                 | 823.4 TB → 827.7 TB |
| dynamical/dwd-icon-grib                             |   37.4 TB → 39.0 TB |
| dynamical/ecmwf-ifs-ens-forecast-15-day-0-25-degree |   45.2 TB → 46.4 TB |
| forestsignal/forestsignal-ca                        |  726.4 GB → 598.0 B |
| e4drr-project/forecasts                             |  84.0 GB → 104.7 GB |
| fiboa/data                                          |   30.1 GB → 49.9 GB |
| wri-data-lab/trazofields                            |   41.4 GB → 54.8 GB |
| rseg/long-lfmc-test                                 |     1.9 TB → 1.9 TB |
| alukach/firesmoke                                   |  84.5 MB → 346.0 MB |
| mvrl/amos-v1                                        |   69.6 TB → 69.6 TB |
| alukach/test-product                                | 630.2 MB → 756.1 MB |
| ftw/ftw-inference-output                            |   37.2 GB → 37.3 GB |
| cholmes/aois                                        |     5.1 GB → 5.1 GB |
| root-geospatial/flight-counts                       |     4.4 GB → 4.4 GB |
| tabaqat/gdelt-sa                                    |   45.8 MB → 47.0 MB |
| wildland-almanac/treatment-scenarios                | 894.7 GB → 894.7 GB |
| cboettig/mappinginequality                          |   28.5 MB → 28.7 MB |
| hdx/hapi                                            |   66.4 MB → 66.3 MB |
| vida/dre-atlas                                      |     4.8 GB → 4.8 GB |
| source/source-stats                                 |     1.9 MB → 2.0 MB |
| cboettig/high-seas                                  |   40.5 GB → 40.5 GB |
| cboettig/padus                                      |   46.7 GB → 46.7 GB |
| cboettig/cpad                                       |     1.4 GB → 1.4 GB |
| cboettig/rivers                                     |     4.4 GB → 4.4 GB |
| dataforcanada/d4c-datapkg-foundation                |   34.3 GB → 34.3 GB |
| cboettig/census                                     |   34.5 GB → 34.5 GB |
| cboettig/ca-dac                                     |     1.6 GB → 1.6 GB |
| cboettig/epa-water                                  |     2.8 GB → 2.8 GB |
| cboettig/calenviroscreen                            | 475.8 MB → 475.9 MB |
| cboettig/usfws                                      | 447.2 MB → 447.2 MB |
| cboettig/trails                                     | 923.2 MB → 923.2 MB |
| cboettig/overturemaps                               |   69.3 GB → 69.3 GB |
| cboettig/ecoregion                                  |     3.6 GB → 3.6 GB |
| cholmes/portolan-nl                                 |   83.7 GB → 83.7 GB |
| wri-data-lab/trazoannotations                       |     1.9 GB → 1.9 GB |

</details>

