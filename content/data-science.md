---
title: Data Science
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:46:27
---

> Data retrieval, manipulation, and storage in Julia.

## Organizations

- [Julia ML](https://github.com/JuliaML)
- [Julia Data](https://github.com/JuliaData)
- [Julia Databases](https://github.com/JuliaDatabases)
- [Julia Stats](https://github.com/JuliaStats)

## Resources

- Blog on [The Lesser Known Normal Forms of Database Design](http://www.johnmyleswhite.com/notebook/2014/09/10/the-lesser-known-normal-forms/)
- [Database-like ops benchmark](https://h2oai.github.io/db-benchmark/) of different languages and libraries.
- [Julia-data-science](https://github.com/tirthajyoti/Julia-data-science) : Notebooks on DS basics with Julia and why it is suitable for data science.
- [Julia DataFrames Tutorial](https://github.com/bkamins/Julia-DataFrames-Tutorial) by Bogumił Kamiński.

## General purpose

- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) : In-memory tabular data in Julia.
  - [DataFrameMacros.jl](https://github.com/jkrumbiegel/DataFrameMacros.jl) : an opinionated take on DataFrame manipulation in Julia with a syntax geared towards clarity, brevity and convenience.
  - [DataFramesMeta.jl](https://github.com/JuliaData/DataFramesMeta.jl) : Metaprogramming tools for `DataFrame`s and `AbstractDict` objects. These macros improve performance and provide more convenient syntax.
- [Cleaner.jl](https://github.com/TheRoniOne/Cleaner.jl) : A toolbox of simple solutions for common data cleaning problems.
- [InMemoryDatasets.jl](https://github.com/sl-solution/InMemoryDatasets.jl) : Multithreaded package for working with tabular data in Julia.
- [Kezdi.jl](https://github.com/codedthinking/Kezdi.jl) : Julia package for data manipulation and analysis. [Juliacon 2024](https://www.youtube.com/watch?v=JklbLwgePis)
- [Pandas.jl](https://github.com/JuliaPy/Pandas.jl) : A Julia front-end to Python's `pandas` package.
- [TableOperations.](https://github.com/JuliaData/TableOperations.jl) : Common table operations on `Tables.jl` interface implementations.
- [Tables.jl](https://github.com/JuliaData/Tables.jl) : An generic interface for tables in Julia.
- [TableWidgets.jl](https://github.com/piever/TableWidgets.jl) : Interactive widgets to work with tabular data in Julia.

## Tabular Data

See also [[data-science]]

- [Arrow.jl](https://github.com/apache/arrow-julia) : Pure Julia implementation of the Apache [arrow data format](https://arrow.apache.org/).
- [Schemata.jl](https://github.com/JockLawrie/Schemata.jl) : Schema (specification of a data set) for tabular data sets in Julia.
- [Feather.jl](https://github.com/JuliaData/Feather.jl) : Julia library for working with feather(v1)-formatted files.
- [JuliaDB.jl](https://github.com/JuliaData/JuliaDB.jl) : JuliaDB is a package for working with large persistent data sets.
- [Tables.jl](https://github.com/JuliaData/Tables.jl) : This package provides four useful interface functions for working with tabular data in a variety of formats.
- [MAT.jl](https://github.com/JuliaIO/MAT.jl) : Julia module for reading MATLAB files.
- [StatFiles.jl](https://github.com/queryverse/StatFiles.jl) : `FileIO.jl` integration for Stata, SPSS, and SAS files.
- [ReadStat.jl](https://github.com/queryverse/ReadStat.jl) : Read files from Stata, SAS, and SPSS.

### CSV files

Reading and writing `csv` files.

- [CSV.jl](https://github.com/JuliaData/CSV.jl) : Utility library for working with CSV and other delimited files in the Julia programming language.
- [DelimitedFiles.jl](https://github.com/JuliaData/DelimitedFiles.jl) : A package for reading and writing files with delimited values (Originally a Julia stdlib).
- [CSVFiles.jl](https://github.com/queryverse/CSVFiles.jl) : `FileIO.jl` integration for CSV files.
- [ReadWriteDlm2.jl](https://github.com/strickek/ReadWriteDlm2.jl) : CSV IO. Works like readdlm/writedlm, but using decimal comma by default. Additional supporting Date, DateTime, Time, Complex, Missing and Rational types.

### Parquet files

[Apache parquet format](https://en.wikipedia.org/wiki/Apache_Parquet)

- [Parquet.jl](https://github.com/JuliaIO/Parquet.jl) : Julia implementation of parquet columnar file format reader and writer.
- [Parquet2.jl](https://gitlab.com/ExpandingMan/Parquet2.jl) : (another) pure Julia implementation of the parquet tabular data binary format.

### HDF5 files

[HDF5](https://www.hdfgroup.org/solutions/hdf5/) format supports tables as well as heterogeneous data.

- [HDF5.jl](https://github.com/JuliaIO/HDF5.jl) : Lib to read HDF5 format files, a widely-used file format for general data.
- [HDF5Logger.jl](https://github.com/tuckermcclure/HDF5Logger.jl) : Allows logging individual frames of data to an HDF5 file over time.

## Database API

- [DBInterface](https://github.com/JuliaDatabases/DBInterface.jl) : An abstract DBI interface to provide a database-independent API protocol that all database drivers can be expected to comply with.
- [IndexedTables.jl](https://github.com/JuliaData/IndexedTables.jl) : Tabular data structures where some of the columns form a sorted index. It provides the backend to `JuliaDB.jl`.
- [JDBC.j](https://github.com/JuliaDatabases/JDBC.jl) : Julia interface to Java database drivers.
- [LevelDB.jl](https://github.com/jerryzhenleicai/LevelDB.jl) : Julia interface to Google's LevelDB key value database.
- [Memcache.jl](https://github.com/tanmaykm/Memcache.jl) : Julia [memcached](https://github.com/memcached/memcached/wiki/Commands) client.
- [ODBC.jl](https://github.com/JuliaDatabases/ODBC.jl) : A low-level ODBC interface for the Julia programming language. [Tabular Data I/O in Julia](https://randyzwitch.com/julia-import-data/).
- [QuandlAccess.jl](https://github.com/tk3369/QuandlAccess.jl) : convenient access to [Quandl](https://www.quandl.com/) data service.

## Accessing datasets

For tabular data file, see [[fileio]]

- [DataDeps.jl](https://github.com/oxinabox/DataDeps.jl) : reproducible data setup for reproducible science.
- [DataToolkit.jl](https://github.com/tecosaur/DataToolkit.jl) : Reproducible, flexible, and convenient data management.
- [FaceDatasets.jl](https://github.com/dfdx/FaceDatasets.jl) : A package for easy access to face-related datasets.
- [Faker.jl](https://github.com/neomatrixcode/Faker.jl) : A package that generates fake data.
- [RDatasets.jl](https://github.com/JuliaStats/RDatasets.jl) : Julia package for loading many of the datasets available in R.
- [WorldBankData.jl](https://github.com/4gh/WorldBankData.jl) : The [World Bank](https://data.worldbank.org/) data.

## SQL and Relational Database Management Systems

[Wikipedia: SQL](https://en.wikipedia.org/wiki/SQL)

- [duckdb](https://github.com/duckdb/duckdb) : an in-process SQL OLAP Database Management System with a Julia API.
- [DataKnots.j](https://github.com/MechanicalRabbit/DataKnots.jl) : An extensible, practical and coherent algebra of [query combinators](https://arxiv.org/abs/1702.08409).
- [LibPQ.j](https://github.com/invenia/LibPQ.jl) : A Julia wrapper for the PostgreSQL [libpq](https://www.postgresql.org/docs/current/libpq.html) C library.
- [MySQL.j](https://github.com/JuliaDatabases/MySQL.jl) : Julia bindings and helper functions for MariaDB/MySQL C library.
- [Octo.jl](https://github.com/wookay/Octo.jl) : an SQL Query DSL in Julia to be used with other SQL drivers.
- [SparkSQL.jl](https://github.com/propelledanalytics/SparkSQL.jl) : working with Apache Spark data using just SQL.
- [SQLite.j](https://github.com/JuliaDatabases/SQLite.jl) : Julia interface to the SQLite library with support for operations on DataFrames.
- [SQLStrings.jl](https://github.com/JuliaComputing/SQLStrings.jl) : `@sql_cmd` macro for SQL query strings.

## NOSQL databases

[Wikipedia: NOSQL](https://en.wikipedia.org/wiki/NoSQL)

- [CQLdriver.jl](https://github.com/r3tex/CQLdriver.jl) : Interfacing with CQL compliant databases. Used with `DataFrames.jl`.
- [LMDB.jl](https://github.com/wildart/LMDB.jl) : A wrapper interface to [Lightning Memory-Mapped Database](https://en.wikipedia.org/wiki/Lightning_Memory-Mapped_Database) (LMDB) key-value embedded data store.
- [Mongoc.jl](https://github.com/felipenoris/Mongoc.jl) : [MongoDB](http://www.mongodb.org/) bindings (newer) and a wrapper around libbson, for the Julia language.
- [Mongo.jl](https://github.com/ScottPJones/Mongo.jl) : [MongoDB](http://www.mongodb.org/) bindings for the Julia programming language.
- [Redis.jl](https://github.com/JuliaDatabases/Redis.jl) : A fully-featured [Redis](https://redis.io/) client for the Julia programming language.