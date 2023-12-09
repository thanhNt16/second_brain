---
name: Polars
site: https://github.com/pola-rs/polars
status: [assess]
topic:
 - processing engine
 - python
 - rust
 - dataframe
 - nodejs
 - R
 - SQL
history:
  - 2023-12-09: assess
---

# Polars
Polars is a DataFrame interface on top of an OLAP Query Engine implemented in Rust using [Apache Arrow Columnar Format](https://arrow.apache.org/docs/format/Columnar.html) as the memory model.

## Installation
```python
pip install polars
```
## Features
- Lazy | eager execution
- Multi-threaded
- SIMD
- Query optimization
- Powerful expression API
- Hybrid Streaming (larger than RAM datasets)
- Rust | Python | NodeJS | R | ...
## Performance 🚀🚀

### [](https://github.com/pola-rs/polars#blazingly-fast)Blazingly fast

Polars is very fast. In fact, it is one of the best performing solutions available. See the results in [DuckDB's db-benchmark](https://duckdblabs.github.io/db-benchmark/).

In the [TPCH benchmarks](https://www.pola.rs/benchmarks.html) Polars is orders of magnitudes faster than pandas, dask, modin and vaex on full queries (including IO).

### [](https://github.com/pola-rs/polars#lightweight)Lightweight

Polars is also very lightweight. It comes with zero required dependencies, and this shows in the import times:

- polars: 70ms
- numpy: 104ms
- pandas: 520ms

### [](https://github.com/pola-rs/polars#handles-larger-than-ram-data)Handles larger than RAM data

If you have data that does not fit into memory, polars lazy is able to process your query (or parts of your query) in a streaming fashion, this drastically reduces memory requirements so you might be able to process your 250GB dataset on your laptop. Collect with `collect(streaming=True)` to run the query streaming. (This might be a little slower, but it is still very fast!)

## [](https://github.com/pola-rs/polars#setup)

## Drawbacks
- NO distributed computing