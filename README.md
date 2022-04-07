# data-sets-surf-repository

The LDBC benchmark data sets are stored under [SURF's CWI repositories](https://repository.surfsara.nl/community/cwi).

## Usage

The data sets are [stored on tape](https://servicedesk.surfsara.nl/wiki/display/WIKI/Data+Archive#DataArchive-What?-Thetapeback-endandtheDataMigrationFacility(DMF)), therefore, you may have to stage them before transfer. To do so, visit the repository of the data set and click "Request" for offline files. Staging a 20 GB file takes approx. 3-5 minutes, while staging a 200 GB one takes approx. 10-15 minutes.

To decompress, use curl and [zstd](https://github.com/facebook/zstd).

```bash
curl --silent --fail set_url_here | tar -xv -I zstd
```


## Graphalytics

[Repository](https://hdl.handle.net/11112/7ec6a51e-6fdb-bf8d-4507-456ccadc9291)

### Graph and validation data sets

* [`cit-Patents.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/cit-Patents.tar.zst) – vertices: 3774768, edges: 16518947
* [`com-friendster.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/com-friendster.tar.zst) – vertices: 65608366, edges: 1806067135
* [`datagen-7_5-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-7_5-fb.tar.zst) – vertices: 633432, edges: 34185747
* [`datagen-7_6-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-7_6-fb.tar.zst) – vertices: 754147, edges: 42162988
* [`datagen-7_7-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-7_7-zf.tar.zst) – vertices: 13180508, edges: 32791267
* [`datagen-7_8-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-7_8-zf.tar.zst) – vertices: 16521886, edges: 41025255
* [`datagen-7_9-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-7_9-fb.tar.zst) – vertices: 1387587, edges: 85670523
* [`datagen-8_0-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_0-fb.tar.zst) – vertices: 1706561, edges: 107507376
* [`datagen-8_1-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_1-fb.tar.zst) – vertices: 2072117, edges: 134267822
* [`datagen-8_2-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_2-zf.tar.zst) – vertices: 43734497, edges: 106440188
* [`datagen-8_3-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_3-zf.tar.zst) – vertices: 53525014, edges: 130579909
* [`datagen-8_4-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_4-fb.tar.zst) – vertices: 3809084, edges: 269479177
* [`datagen-8_5-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_5-fb.tar.zst) – vertices: 4599739, edges: 332026902
* [`datagen-8_6-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_6-fb.tar.zst) – vertices: 5667674, edges: 421988619
* [`datagen-8_7-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_7-zf.tar.zst) – vertices: 145050709, edges: 340157363
* [`datagen-8_8-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_8-zf.tar.zst) – vertices: 168308893, edges: 413354288
* [`datagen-8_9-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-8_9-fb.tar.zst) – vertices: 10572901, edges: 848681908
* [`datagen-9_0-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-9_0-fb.tar.zst) – vertices: 12857671, edges: 1049527225
* [`datagen-9_1-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-9_1-fb.tar.zst) – vertices: 16087483, edges: 1342158397
* [`datagen-9_2-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-9_2-zf.tar.zst) – vertices: 434943376, edges: 1042340732
* [`datagen-9_3-zf.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-9_3-zf.tar.zst) – vertices: 555270053, edges: 1309998551
* [`datagen-9_4-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-9_4-fb.tar.zst) – vertices: 29310565, edges: 2588948669
* [`datagen-sf10k-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-sf10k-fb.tar.zst) – vertices: 33484375, edges: 2912009743
* [`datagen-sf3k-fb.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/datagen-sf3k-fb.tar.zst) – vertices: 100218750, edges: 9404822538
* [`dota-league.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/dota-league.tar.zst) – vertices: 61170, edges: 50870313
* [`example-directed.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/example-directed.tar.zst) – vertices: 10, edges: 17
* [`example-undirected.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/example-undirected.tar.zst) – vertices: 9, edges: 12
* [`graph500-22.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-22.tar.zst) – vertices: 2396657, edges: 64155735
* [`graph500-23.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-23.tar.zst) – vertices: 4610222, edges: 129333677
* [`graph500-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-24.tar.zst) – vertices: 8870942, edges: 260379520
* [`graph500-25.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-25.tar.zst) – vertices: 17062472, edges: 523602831
* [`graph500-26.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-26.tar.zst) – vertices: 32804978, edges: 1051922853
* [`graph500-27.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-27.tar.zst) – vertices: 63081040, edges: 2111642032
* [`graph500-28.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-28.tar.zst) – vertices: 121242388, edges: 4236163958
* [`graph500-29.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-29.tar.zst) – vertices: 232999630, edges: 8493569115
* [`graph500-30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/graph500-30.tar.zst) – vertices: 447797986, edges: 17022117362
* [`kgs.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/kgs.tar.zst) – vertices: 832247, edges: 17891698
* [`twitter_mpi.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/twitter_mpi.tar.zst) – vertices: 52579678, edges: 1963263508
* [`wiki-Talk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-graph-data-sets/wiki-Talk.tar.zst) – vertices: 2394385, edges: 5021410

### Graphs as sparse matrices in Matrix Market format

* [`matrix-market/cit-Patents.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/cit-Patents.tar.zst) – vertices: 3774768, edges: 16518947
* [`matrix-market/com-friendster.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/com-friendster.tar.zst) – vertices: 65608366, edges: 1806067135
* [`matrix-market/datagen-7_5-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_5-fb-bool.tar.zst) – vertices: 633432, edges: 34185747
* [`matrix-market/datagen-7_5-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_5-fb-fp64.tar.zst) – vertices: 633432, edges: 34185747
* [`matrix-market/datagen-7_6-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_6-fb-bool.tar.zst) – vertices: 754147, edges: 42162988
* [`matrix-market/datagen-7_6-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_6-fb-fp64.tar.zst) – vertices: 754147, edges: 42162988
* [`matrix-market/datagen-7_7-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_7-zf-bool.tar.zst) – vertices: 13180508, edges: 32791267
* [`matrix-market/datagen-7_7-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_7-zf-fp64.tar.zst) – vertices: 13180508, edges: 32791267
* [`matrix-market/datagen-7_8-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_8-zf-bool.tar.zst) – vertices: 16521886, edges: 41025255
* [`matrix-market/datagen-7_8-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_8-zf-fp64.tar.zst) – vertices: 16521886, edges: 41025255
* [`matrix-market/datagen-7_9-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_9-fb-bool.tar.zst) – vertices: 1387587, edges: 85670523
* [`matrix-market/datagen-7_9-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-7_9-fb-fp64.tar.zst) – vertices: 1387587, edges: 85670523
* [`matrix-market/datagen-8_0-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_0-fb-bool.tar.zst) – vertices: 1706561, edges: 107507376
* [`matrix-market/datagen-8_0-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_0-fb-fp64.tar.zst) – vertices: 1706561, edges: 107507376
* [`matrix-market/datagen-8_1-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_1-fb-bool.tar.zst) – vertices: 2072117, edges: 134267822
* [`matrix-market/datagen-8_1-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_1-fb-fp64.tar.zst) – vertices: 2072117, edges: 134267822
* [`matrix-market/datagen-8_2-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_2-zf-bool.tar.zst) – vertices: 43734497, edges: 106440188
* [`matrix-market/datagen-8_2-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_2-zf-fp64.tar.zst) – vertices: 43734497, edges: 106440188
* [`matrix-market/datagen-8_3-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_3-zf-bool.tar.zst) – vertices: 53525014, edges: 130579909
* [`matrix-market/datagen-8_3-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_3-zf-fp64.tar.zst) – vertices: 53525014, edges: 130579909
* [`matrix-market/datagen-8_4-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_4-fb-bool.tar.zst) – vertices: 3809084, edges: 269479177
* [`matrix-market/datagen-8_4-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_4-fb-fp64.tar.zst) – vertices: 3809084, edges: 269479177
* [`matrix-market/datagen-8_5-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_5-fb-bool.tar.zst) – vertices: 4599739, edges: 332026902
* [`matrix-market/datagen-8_5-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_5-fb-fp64.tar.zst) – vertices: 4599739, edges: 332026902
* [`matrix-market/datagen-8_6-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_6-fb-bool.tar.zst) – vertices: 5667674, edges: 421988619
* [`matrix-market/datagen-8_6-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_6-fb-fp64.tar.zst) – vertices: 5667674, edges: 421988619
* [`matrix-market/datagen-8_7-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_7-zf-bool.tar.zst) – vertices: 145050709, edges: 340157363
* [`matrix-market/datagen-8_7-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_7-zf-fp64.tar.zst) – vertices: 145050709, edges: 340157363
* [`matrix-market/datagen-8_8-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_8-zf-bool.tar.zst) – vertices: 168308893, edges: 413354288
* [`matrix-market/datagen-8_8-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_8-zf-fp64.tar.zst) – vertices: 168308893, edges: 413354288
* [`matrix-market/datagen-8_9-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_9-fb-bool.tar.zst) – vertices: 10572901, edges: 848681908
* [`matrix-market/datagen-8_9-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-8_9-fb-fp64.tar.zst) – vertices: 10572901, edges: 848681908
* [`matrix-market/datagen-9_0-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_0-fb-bool.tar.zst) – vertices: 12857671, edges: 1049527225
* [`matrix-market/datagen-9_0-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_0-fb-fp64.tar.zst) – vertices: 12857671, edges: 1049527225
* [`matrix-market/datagen-9_1-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_1-fb-bool.tar.zst) – vertices: 16087483, edges: 1342158397
* [`matrix-market/datagen-9_1-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_1-fb-fp64.tar.zst) – vertices: 16087483, edges: 1342158397
* [`matrix-market/datagen-9_2-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_2-zf-bool.tar.zst) – vertices: 434943376, edges: 1042340732
* [`matrix-market/datagen-9_2-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_2-zf-fp64.tar.zst) – vertices: 434943376, edges: 1042340732
* [`matrix-market/datagen-9_3-zf-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_3-zf-bool.tar.zst) – vertices: 555270053, edges: 1309998551
* [`matrix-market/datagen-9_3-zf-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_3-zf-fp64.tar.zst) – vertices: 555270053, edges: 1309998551
* [`matrix-market/datagen-9_4-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_4-fb-bool.tar.zst) – vertices: 29310565, edges: 2588948669
* [`matrix-market/datagen-9_4-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-9_4-fb-fp64.tar.zst) – vertices: 29310565, edges: 2588948669
* [`matrix-market/datagen-sf10k-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-sf10k-fb-bool.tar.zst) – vertices: 33484375, edges: 2912009743
* [`matrix-market/datagen-sf10k-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-sf10k-fb-fp64.tar.zst) – vertices: 33484375, edges: 2912009743
* [`matrix-market/datagen-sf3k-fb-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-sf3k-fb-bool.tar.zst) – vertices: 100218750, edges: 9404822538
* [`matrix-market/datagen-sf3k-fb-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/datagen-sf3k-fb-fp64.tar.zst) – vertices: 100218750, edges: 9404822538
* [`matrix-market/dota-league-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/dota-league-bool.tar.zst) – vertices: 61170, edges: 50870313
* [`matrix-market/dota-league-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/dota-league-fp64.tar.zst) – vertices: 61170, edges: 50870313
* [`matrix-market/example-directed-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/example-directed-bool.tar.zst) – vertices: 10, edges: 17
* [`matrix-market/example-directed-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/example-directed-fp64.tar.zst) – vertices: 10, edges: 17
* [`matrix-market/example-undirected-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/example-undirected-bool.tar.zst) – vertices: 9, edges: 12
* [`matrix-market/example-undirected-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/example-undirected-fp64.tar.zst) – vertices: 9, edges: 12
* [`matrix-market/graph500-22.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-22.tar.zst) – vertices: 2396657, edges: 64155735
* [`matrix-market/graph500-23.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-23.tar.zst) – vertices: 4610222, edges: 129333677
* [`matrix-market/graph500-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-24.tar.zst) – vertices: 8870942, edges: 260379520
* [`matrix-market/graph500-25.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-25.tar.zst) – vertices: 17062472, edges: 523602831
* [`matrix-market/graph500-26.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-26.tar.zst) – vertices: 32804978, edges: 1051922853
* [`matrix-market/graph500-27.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-27.tar.zst) – vertices: 63081040, edges: 2111642032
* [`matrix-market/graph500-28.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-28.tar.zst) – vertices: 121242388, edges: 4236163958
* [`matrix-market/graph500-29.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-29.tar.zst) – vertices: 232999630, edges: 8493569115
* [`matrix-market/graph500-30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/graph500-30.tar.zst) – vertices: 447797986, edges: 17022117362
* [`matrix-market/kgs-bool.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/kgs-bool.tar.zst) – vertices: 832247, edges: 17891698
* [`matrix-market/kgs-fp64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/kgs-fp64.tar.zst) – vertices: 832247, edges: 17891698
* [`matrix-market/twitter_mpi.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/twitter_mpi.tar.zst) – vertices: 52579678, edges: 1963263508
* [`matrix-market/wiki-Talk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/graphalytics/files/graphalytics-sparse-matrices-matrix-market/wiki-Talk.tar.zst) – vertices: 2394385, edges: 5021410

## Social Network Benchmark (SNB) Interactive

[Repository](https://hdl.handle.net/11112/e6e00558-a2c3-9214-473e-04a16de09bf8)

### Social network with the CsvBasic serializer using LongDateFormatter

* [`social_network-csv_basic-longdateformatter-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf0.1.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf0.3.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf1.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf3.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf10.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf30.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf100.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf300.tar.zst)
* [`social_network-csv_basic-longdateformatter-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic-longdateformatter/social_network-csv_basic-longdateformatter-sf1000.tar.zst)

### Social network with the CsvBasic serializer using StringDateFormatter

* [`social_network-csv_basic-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf0.1.tar.zst)
* [`social_network-csv_basic-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf0.3.tar.zst)
* [`social_network-csv_basic-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf1.tar.zst)
* [`social_network-csv_basic-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf3.tar.zst)
* [`social_network-csv_basic-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf10.tar.zst)
* [`social_network-csv_basic-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf30.tar.zst)
* [`social_network-csv_basic-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf100.tar.zst)
* [`social_network-csv_basic-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf300.tar.zst)
* [`social_network-csv_basic-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_basic/social_network-csv_basic-sf1000.tar.zst)

### Social network with the CsvCompositeMergeForeign serializer using LongDateFormatter

* [`social_network-csv_composite_merge_foreign-longdateformatter-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf0.1.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf0.3.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf1.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf3.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf10.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf30.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf100.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf300.tar.zst)
* [`social_network-csv_composite_merge_foreign-longdateformatter-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign-longdateformatter/social_network-csv_composite_merge_foreign-longdateformatter-sf1000.tar.zst)

### Social network with the CsvCompositeMergeForeign serializer using StringDateFormatter

* [`social_network-csv_composite_merge_foreign-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf0.1.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf0.3.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf1.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf3.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf10.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf30.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf100.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf300.tar.zst)
* [`social_network-csv_composite_merge_foreign-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite_merge_foreign/social_network-csv_composite_merge_foreign-sf1000.tar.zst)

### Social network with the CsvComposite serializer using LongDateFormatter

* [`social_network-csv_composite-longdateformatter-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf0.1.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf0.3.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf1.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf3.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf10.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf30.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf100.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf300.tar.zst)
* [`social_network-csv_composite-longdateformatter-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite-longdateformatter/social_network-csv_composite-longdateformatter-sf1000.tar.zst)

### Social network with the CsvComposite serializer using StringDateFormatter

* [`social_network-csv_composite-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf0.1.tar.zst)
* [`social_network-csv_composite-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf0.3.tar.zst)
* [`social_network-csv_composite-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf1.tar.zst)
* [`social_network-csv_composite-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf3.tar.zst)
* [`social_network-csv_composite-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf10.tar.zst)
* [`social_network-csv_composite-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf30.tar.zst)
* [`social_network-csv_composite-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf100.tar.zst)
* [`social_network-csv_composite-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf300.tar.zst)
* [`social_network-csv_composite-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_composite/social_network-csv_composite-sf1000.tar.zst)

### Social network with the CsvMergeForeign serializer using LongDateFormatter

* [`social_network-csv_merge_foreign-longdateformatter-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf0.1.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf0.3.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf1.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf3.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf10.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf30.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf100.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf300.tar.zst)
* [`social_network-csv_merge_foreign-longdateformatter-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign-longdateformatter/social_network-csv_merge_foreign-longdateformatter-sf1000.tar.zst)

### Social network with the CsvMergeForeign serializer using StringDateFormatter

* [`social_network-csv_merge_foreign-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf0.1.tar.zst)
* [`social_network-csv_merge_foreign-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf0.3.tar.zst)
* [`social_network-csv_merge_foreign-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf1.tar.zst)
* [`social_network-csv_merge_foreign-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf3.tar.zst)
* [`social_network-csv_merge_foreign-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf10.tar.zst)
* [`social_network-csv_merge_foreign-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf30.tar.zst)
* [`social_network-csv_merge_foreign-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf100.tar.zst)
* [`social_network-csv_merge_foreign-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf300.tar.zst)
* [`social_network-csv_merge_foreign-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-csv_merge_foreign/social_network-csv_merge_foreign-sf1000.tar.zst)

### Social network with the TTL serializer

* [`social_network_ttl_sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf0.1.tar.zst)
* [`social_network_ttl_sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf0.3.tar.zst)
* [`social_network_ttl_sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf1.tar.zst)
* [`social_network_ttl_sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf3.tar.zst)
* [`social_network_ttl_sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf10.tar.zst)
* [`social_network_ttl_sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf30.tar.zst)
* [`social_network_ttl_sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf100.tar.zst)
* [`social_network_ttl_sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf300.tar.zst)
* [`social_network_ttl_sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/social_network-ttl/social_network_ttl_sf1000.tar.zst)

### Substitution parameters

All: [`substitution_parameters/substitution_parameters.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters.tar.zst)

* [`substitution_parameters-sf0.1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf0.1.tar.zst)
* [`substitution_parameters-sf0.3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf0.3.tar.zst)
* [`substitution_parameters-sf1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf1.tar.zst)
* [`substitution_parameters-sf3.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf3.tar.zst)
* [`substitution_parameters-sf10.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf10.tar.zst)
* [`substitution_parameters-sf30.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf30.tar.zst)
* [`substitution_parameters-sf100.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf100.tar.zst)
* [`substitution_parameters-sf300.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf300.tar.zst)
* [`substitution_parameters-sf1000.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/substitution_parameters/substitution_parameters-sf1000.tar.zst)

### Update streams

#### SF0.1

* [`social_network-sf0.1-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-1.tar.zst)
* [`social_network-sf0.1-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-2.tar.zst)
* [`social_network-sf0.1-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-4.tar.zst)
* [`social_network-sf0.1-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-8.tar.zst)
* [`social_network-sf0.1-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-16.tar.zst)
* [`social_network-sf0.1-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-24.tar.zst)
* [`social_network-sf0.1-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-32.tar.zst)
* [`social_network-sf0.1-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-48.tar.zst)
* [`social_network-sf0.1-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-64.tar.zst)
* [`social_network-sf0.1-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-96.tar.zst)
* [`social_network-sf0.1-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-128.tar.zst)
* [`social_network-sf0.1-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-192.tar.zst)
* [`social_network-sf0.1-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-256.tar.zst)
* [`social_network-sf0.1-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-384.tar.zst)
* [`social_network-sf0.1-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-512.tar.zst)
* [`social_network-sf0.1-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-768.tar.zst)
* [`social_network-sf0.1-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.1/social_network-sf0.1-numpart-1024.tar.zst)

#### SF0.3

* [`social_network-sf0.3-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-1.tar.zst)
* [`social_network-sf0.3-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-2.tar.zst)
* [`social_network-sf0.3-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-4.tar.zst)
* [`social_network-sf0.3-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-8.tar.zst)
* [`social_network-sf0.3-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-16.tar.zst)
* [`social_network-sf0.3-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-24.tar.zst)
* [`social_network-sf0.3-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-32.tar.zst)
* [`social_network-sf0.3-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-48.tar.zst)
* [`social_network-sf0.3-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-64.tar.zst)
* [`social_network-sf0.3-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-96.tar.zst)
* [`social_network-sf0.3-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-128.tar.zst)
* [`social_network-sf0.3-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-192.tar.zst)
* [`social_network-sf0.3-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-256.tar.zst)
* [`social_network-sf0.3-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-384.tar.zst)
* [`social_network-sf0.3-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-512.tar.zst)
* [`social_network-sf0.3-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-768.tar.zst)
* [`social_network-sf0.3-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf0.3/social_network-sf0.3-numpart-1024.tar.zst)

#### SF1

* [`social_network-sf1-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-1.tar.zst)
* [`social_network-sf1-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-2.tar.zst)
* [`social_network-sf1-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-4.tar.zst)
* [`social_network-sf1-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-8.tar.zst)
* [`social_network-sf1-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-16.tar.zst)
* [`social_network-sf1-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-24.tar.zst)
* [`social_network-sf1-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-32.tar.zst)
* [`social_network-sf1-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-48.tar.zst)
* [`social_network-sf1-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-64.tar.zst)
* [`social_network-sf1-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-96.tar.zst)
* [`social_network-sf1-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-128.tar.zst)
* [`social_network-sf1-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-192.tar.zst)
* [`social_network-sf1-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-256.tar.zst)
* [`social_network-sf1-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-384.tar.zst)
* [`social_network-sf1-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-512.tar.zst)
* [`social_network-sf1-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-768.tar.zst)
* [`social_network-sf1-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1/social_network-sf1-numpart-1024.tar.zst)

#### SF3

* [`social_network-sf3-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-1.tar.zst)
* [`social_network-sf3-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-2.tar.zst)
* [`social_network-sf3-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-4.tar.zst)
* [`social_network-sf3-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-8.tar.zst)
* [`social_network-sf3-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-16.tar.zst)
* [`social_network-sf3-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-24.tar.zst)
* [`social_network-sf3-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-32.tar.zst)
* [`social_network-sf3-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-48.tar.zst)
* [`social_network-sf3-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-64.tar.zst)
* [`social_network-sf3-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-96.tar.zst)
* [`social_network-sf3-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-128.tar.zst)
* [`social_network-sf3-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-192.tar.zst)
* [`social_network-sf3-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-256.tar.zst)
* [`social_network-sf3-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-384.tar.zst)
* [`social_network-sf3-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-512.tar.zst)
* [`social_network-sf3-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-768.tar.zst)
* [`social_network-sf3-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf3/social_network-sf3-numpart-1024.tar.zst)

#### SF10

* [`social_network-sf10-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-1.tar.zst)
* [`social_network-sf10-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-2.tar.zst)
* [`social_network-sf10-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-4.tar.zst)
* [`social_network-sf10-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-8.tar.zst)
* [`social_network-sf10-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-16.tar.zst)
* [`social_network-sf10-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-24.tar.zst)
* [`social_network-sf10-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-32.tar.zst)
* [`social_network-sf10-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-48.tar.zst)
* [`social_network-sf10-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-64.tar.zst)
* [`social_network-sf10-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-96.tar.zst)
* [`social_network-sf10-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-128.tar.zst)
* [`social_network-sf10-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-192.tar.zst)
* [`social_network-sf10-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-256.tar.zst)
* [`social_network-sf10-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-384.tar.zst)
* [`social_network-sf10-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-512.tar.zst)
* [`social_network-sf10-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-768.tar.zst)
* [`social_network-sf10-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf10/social_network-sf10-numpart-1024.tar.zst)

#### SF30

* [`social_network-sf30-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-1.tar.zst)
* [`social_network-sf30-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-2.tar.zst)
* [`social_network-sf30-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-4.tar.zst)
* [`social_network-sf30-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-8.tar.zst)
* [`social_network-sf30-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-16.tar.zst)
* [`social_network-sf30-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-24.tar.zst)
* [`social_network-sf30-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-32.tar.zst)
* [`social_network-sf30-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-48.tar.zst)
* [`social_network-sf30-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-64.tar.zst)
* [`social_network-sf30-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-96.tar.zst)
* [`social_network-sf30-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-128.tar.zst)
* [`social_network-sf30-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-192.tar.zst)
* [`social_network-sf30-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-256.tar.zst)
* [`social_network-sf30-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-384.tar.zst)
* [`social_network-sf30-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-512.tar.zst)
* [`social_network-sf30-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-768.tar.zst)
* [`social_network-sf30-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf30/social_network-sf30-numpart-1024.tar.zst)

#### SF100

* [`social_network-sf100-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-1.tar.zst)
* [`social_network-sf100-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-2.tar.zst)
* [`social_network-sf100-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-4.tar.zst)
* [`social_network-sf100-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-8.tar.zst)
* [`social_network-sf100-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-16.tar.zst)
* [`social_network-sf100-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-24.tar.zst)
* [`social_network-sf100-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-32.tar.zst)
* [`social_network-sf100-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-48.tar.zst)
* [`social_network-sf100-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-64.tar.zst)
* [`social_network-sf100-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-96.tar.zst)
* [`social_network-sf100-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-128.tar.zst)
* [`social_network-sf100-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-192.tar.zst)
* [`social_network-sf100-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-256.tar.zst)
* [`social_network-sf100-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-384.tar.zst)
* [`social_network-sf100-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-512.tar.zst)
* [`social_network-sf100-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-768.tar.zst)
* [`social_network-sf100-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf100/social_network-sf100-numpart-1024.tar.zst)

#### SF300

* [`social_network-sf300-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-1.tar.zst)
* [`social_network-sf300-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-2.tar.zst)
* [`social_network-sf300-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-4.tar.zst)
* [`social_network-sf300-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-8.tar.zst)
* [`social_network-sf300-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-16.tar.zst)
* [`social_network-sf300-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-24.tar.zst)
* [`social_network-sf300-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-32.tar.zst)
* [`social_network-sf300-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-48.tar.zst)
* [`social_network-sf300-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-64.tar.zst)
* [`social_network-sf300-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-96.tar.zst)
* [`social_network-sf300-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-128.tar.zst)
* [`social_network-sf300-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-192.tar.zst)
* [`social_network-sf300-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-256.tar.zst)
* [`social_network-sf300-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-384.tar.zst)
* [`social_network-sf300-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-512.tar.zst)
* [`social_network-sf300-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-768.tar.zst)
* [`social_network-sf300-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf300/social_network-sf300-numpart-1024.tar.zst)

#### SF1000

* [`social_network-sf1000-numpart-1.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-1.tar.zst)
* [`social_network-sf1000-numpart-2.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-2.tar.zst)
* [`social_network-sf1000-numpart-4.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-4.tar.zst)
* [`social_network-sf1000-numpart-8.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-8.tar.zst)
* [`social_network-sf1000-numpart-16.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-16.tar.zst)
* [`social_network-sf1000-numpart-24.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-24.tar.zst)
* [`social_network-sf1000-numpart-32.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-32.tar.zst)
* [`social_network-sf1000-numpart-48.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-48.tar.zst)
* [`social_network-sf1000-numpart-64.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-64.tar.zst)
* [`social_network-sf1000-numpart-96.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-96.tar.zst)
* [`social_network-sf1000-numpart-128.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-128.tar.zst)
* [`social_network-sf1000-numpart-192.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-192.tar.zst)
* [`social_network-sf1000-numpart-256.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-256.tar.zst)
* [`social_network-sf1000-numpart-384.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-384.tar.zst)
* [`social_network-sf1000-numpart-512.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-512.tar.zst)
* [`social_network-sf1000-numpart-768.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-768.tar.zst)
* [`social_network-sf1000-numpart-1024.tar.zst`](https://repository.surfsara.nl/datasets/cwi/snb/files/updatestreams/sf1000/social_network-sf1000-numpart-1024.tar.zst)

## Labelled Subgraph Query Benchmark (LSQB)

[Repository](https://hdl.handle.net/11112/9fa972d6-dec4-983a-4e6a-83809f39b7fe)

### Merged FK

* [`lsqb-merged/social-network-sf0.1-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf0.1-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf0.3-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf0.3-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf1-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf1-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf3-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf3-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf10-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf10-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf30-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf30-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf100-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf100-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf300-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf300-merged-fk.tar.zst)
* [`lsqb-merged/social-network-sf1000-merged-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-merged/social-network-sf1000-merged-fk.tar.zst)

### Projected FK

* [`lsqb-projected/social-network-sf0.1-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf0.1-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf0.3-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf0.3-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf1-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf1-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf3-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf3-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf10-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf10-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf30-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf30-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf100-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf100-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf300-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf300-projected-fk.tar.zst)
* [`lsqb-projected/social-network-sf1000-projected-fk.tar.zst`](https://repository.surfsara.nl/datasets/cwi/lsqb/files/lsqb-projected/social-network-sf1000-projected-fk.tar.zst)

## SIGMOD 2014 Programming Contest

[Repository](https://hdl.handle.net/11112/dde63984-08bb-848c-4f00-bfdad71ed649)

### Data sets used in the original contest

* [`o1k.tar.zst`](https://repository.surfsara.nl/datasets/cwi/ldbc-sigmod-data-sets/files/o1k.tar.zst)
* [`o10k.tar.zst`](https://repository.surfsara.nl/datasets/cwi/ldbc-sigmod-data-sets/files/o10k.tar.zst)

### New data sets

* [`p1k.tar.zst`](https://repository.surfsara.nl/datasets/cwi/ldbc-sigmod-data-sets/files/p1k.tar.zst)
* [`p10k.tar.zst`](https://repository.surfsara.nl/datasets/cwi/ldbc-sigmod-data-sets/files/p10k.tar.zst)
* [`p100k.tar.zst`](https://repository.surfsara.nl/datasets/cwi/ldbc-sigmod-data-sets/files/p100k.tar.zst)
* [`p1000k.tar.zst`](https://repository.surfsara.nl/datasets/cwi/ldbc-sigmod-data-sets/files/p1000k.tar.zst)
