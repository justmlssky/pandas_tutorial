# Pandas Tutorial
## [Pandas: 10 Common mistakes while reading data](https://pandas.pydata.org/pandas-docs/stable/reference/io.html)

### Why wrong datatype choice make life miserable? 
File Encoding
- Unicode vs ASCII

Data Types
- bool vs boolean, string vs object
- Infered Data Type
  - CSV
  - JSON
  - XML
- Well-formed typed files
  - Excel
  - XML
- Unconventional data loads
  - HTML (URL)
  - Clipboard
- High Performance file formats
  - Parquet
  - ORC
- Less used
  - STATA
  - Latex
  - SAS
  - SPSS

Performance
- Single Machine
  - Chunking
  - PyArrow
  - Feather

- Distributed Systems(we can use tools like below)
   - Dask
   - Kartothek
   - Intake
   - SQL Databases(Google BQ, SQL Alchemy, BlazingSQL)

Checkpointing
  - Pickle and HDF5 for check pointing


Conclusion

Stay tuned for next

[Bonus: Official Pandas Cheat Sheet](https://github.com/pandas-dev/pandas/blob/master/doc/cheatsheet/Pandas_Cheat_Sheet.pdf)
