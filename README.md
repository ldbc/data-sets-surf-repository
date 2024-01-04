# LDBC benchmark data sets

The LDBC benchmark data sets are stored under [SURF's CWI repositories](https://repository.surfsara.nl/community/cwi).

## Usage

The data sets are [stored on tape](https://servicedesk.surfsara.nl/wiki/display/WIKI/Data+Archive#DataArchive-What?-Thetapeback-endandtheDataMigrationFacility(DMF)), therefore, you may have to stage them before they can be downloaded.
To do so, visit the repository of the data set and click "Request" for offline files. Staging a 20 GB file takes approx. 3-5 minutes, while staging a 200 GB one takes approx. 10-15 minutes.

To decompress, use [zstd](https://github.com/facebook/zstd).

```bash
tar -xv --use-compress-program=unzstd file.tar.zst
```

We provide the [`download-data-set.sh`](https://github.com/ldbc/data-sets-surf-repository/blob/main/download-data-set.sh) script, which attempts to download the data set and stages it to disk if necessary. Replace the `data_set_url` with one of the URLs linked below in this README (right click and select Copy Link Address).

```bash
./download-data-set.sh data_set_url
```

Example:

```bash
./download-data-set.sh https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf0.1.tar.zst
```

## Data sets

* [Financial Benchmark (FinBench)](finbench)
* [Graphalytics](graphalytics)
* [Labeled Subgraph Query Benchmark (LSQB)](lsqb)
* [SIGMOD 2014 Programming Contest](sigmod-2014-programming-contest)
* [SNB Business Intelligence (BI)](snb-business-intelligence)
* [SNB Interactive v1 (Datagen v0.3.5)](snb-interactive-v1-datagen-v035)
* [SNB Interactive v1 (Datagen v1.0.0)](snb-interactive-v1-datagen-v100)
* [SNB Interactive v2 updates](snb-interactive-v2-updates)
* [SNB factor tables](snb-factor-tables)
