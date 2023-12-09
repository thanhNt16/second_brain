---
name: Pandas
site: https://github.com/pandas-dev/pandas
status: [adopt]
topic:
 - processing engine
 - python
 - dataframe
history:
  - 2023-12-09: adopt
---

# Pandas
**pandas** is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, **real world** data analysis in Python. Additionally, it has the broader goal of becoming **the most powerful and flexible open source data analysis / manipulation tool available in any language**. It is already well on its way towards this goal.
## Installation
```python
pip install pandas
```
## Features
- Easy handling of [**missing data**](https://pandas.pydata.org/pandas-docs/stable/user_guide/missing_data.html) (represented as `NaN`, `NA`, or `NaT`) in floating point as well as non-floating point data
- Size mutability: columns can be [**inserted and deleted**](https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html#column-selection-addition-deletion) from DataFrame and higher dimensional objects
- Automatic and explicit [**data alignment**](https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html?highlight=alignment#intro-to-data-structures): objects can be explicitly aligned to a set of labels, or the user can simply ignore the labels and let `Series`, `DataFrame`, etc. automatically align the data for you in computations
- Powerful, flexible [**group by**](https://pandas.pydata.org/pandas-docs/stable/user_guide/groupby.html#group-by-split-apply-combine) functionality to perform split-apply-combine operations on data sets, for both aggregating and transforming data
- Make it [**easy to convert**](https://pandas.pydata.org/pandas-docs/stable/user_guide/dsintro.html#dataframe) ragged, differently-indexed data in other Python and NumPy data structures into DataFrame objects
- Intelligent label-based [**slicing**](https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#slicing-ranges), [**fancy indexing**](https://pandas.pydata.org/pandas-docs/stable/user_guide/advanced.html#advanced), and [**subsetting**](https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#boolean-indexing) of large data sets
- Intuitive [**merging**](https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html#database-style-dataframe-or-named-series-joining-merging) and [**joining**](https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html#joining-on-index) data sets
- Flexible [**reshaping**](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html) and [**pivoting**](https://pandas.pydata.org/pandas-docs/stable/user_guide/reshaping.html) of data sets
- [**Hierarchical**](https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#hierarchical-indexing-multiindex) labeling of axes (possible to have multiple labels per tick)
- Robust IO tools for loading data from [**flat files**](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#csv-text-files) (CSV and delimited), [**Excel files**](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#excel-files), [**databases**](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#sql-queries), and saving/loading data from the ultrafast [**HDF5 format**](https://pandas.pydata.org/pandas-docs/stable/user_guide/io.html#hdf5-pytables)
- [**Time series**](https://pandas.pydata.org/pandas-docs/stable/user_guide/timeseries.html#time-series-date-functionality)-specific functionality: date range generation and frequency conversion, moving window statistics, date shifting and lagging

## Drawbacks
- NO parallelization of tasks
- NO distributed computing
- NOT memory efficient 