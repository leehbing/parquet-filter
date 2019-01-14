# parquet-filter

This project comes from [parquet-index](https://github.com/lightcopy/parquet-index)


##Parts of changes
- `create index for incremental files`

Index created by parquet-index is for all parquet files belongs to one parquet table, and once such index is created, we can't create other index for the new files which were added to the parquet table, that is, we can't create incremental index for incremental parquet files

- `index saved in HDFS or HBase or ElasticSearch`

- `...`

