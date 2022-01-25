# Data-Analysis-Tricks
Doing data analysis easily


## 1. Set Max Number of Rows

`pd.options.display.max_rows`

`pd.options.display.max_rows = 100`

## 2. Set Max Number of Columns

`pd.options.display.max_columns`

`pd.options.display.max_columns = 50`

## 3. Set Max Width of Cell

By default, Pandas only display content in a cell with a maximum width of 50. That is, a cell with more than 50 characters will be truncated.
`pd.options.display.max_colwidth`

## 4. Set Max Number of Columns Shown in info()

`pd.options.display.max_info_columns`

`pd.options.display.max_info_columns = 150`

`df.info()`

## 5. Set Display Precision

`pd.options.display.precision`

`pd.options.display.precision = 15`

**Pandas profiling and D-tale**

## 6. Set Decimal Format

`pd.options.display.float_format = '{:.2f}%'.format`

