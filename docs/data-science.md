---
title: Data Science
---

> Data retrieval, manipulation, and storage in Julia.

- [Julia ML](https://github.com/JuliaML) organization
- [Julia Data](https://github.com/JuliaData) organization
- [Julia Databases](https://github.com/JuliaDatabases) organization
- [Julia stats](https://github.com/JuliaStats) organization

---

- Blog on [The Lesser Known Normal Forms of Database Design](http://www.johnmyleswhite.com/notebook/2014/09/10/the-lesser-known-normal-forms/)
- [Database-like ops benchmark](https://h2oai.github.io/db-benchmark/) of different languages and libraries.
- [Julia-data-science](https://github.com/tirthajyoti/Julia-data-science) : Notebooks on DS basics with Julia and why it is suitable for data science.
- [Julia DataFrames Tutorial](https://github.com/bkamins/Julia-DataFrames-Tutorial) by Bogumił Kamiński.

## General purpose

- https://github.com/JuliaData/DataFrames.jl : In-memory tabular data in Julia.
  - https://github.com/jkrumbiegel/DataFrameMacros.jl : an opinionated take on DataFrame manipulation in Julia with a syntax geared towards clarity, brevity and convenience.
  - https://github.com/JuliaData/DataFramesMeta.jl : Metaprogramming tools for `DataFrame`s and `AbstractDict` objects. These macros improve performance and provide more convenient syntax.
- https://github.com/JuliaData/Tables.jl : An generic interface for tables in Julia.
- https://github.com/JuliaPy/Pandas.jl : A Julia front-end to Python's `pandas` package.

## Data Manipulation

- https://github.com/JuliaData/TableOperations.jl : Common table operations on `Tables.jl` interface implementations.
- https://github.com/sl-solution/InMemoryDatasets.jl : Multithreaded package for working with tabular data in Julia.
- https://github.com/TheRoniOne/Cleaner.jl : A toolbox of simple solutions for common data cleaning problems.

## DataBase API

- https://github.com/jerryzhenleicai/LevelDB.jl : Julia interface to Google's LevelDB key value database.
- https://github.com/JuliaData/IndexedTables.jl : Tabular data structures where some of the columns form a sorted index. It provides the backend to `JuliaDB.jl`.
- https://github.com/JuliaDatabases/DBInterface.jl : An abstract DBI interface to provide a database-independent API protocol that all database drivers can be expected to comply with.
- https://github.com/JuliaDatabases/JDBC.jl : Julia interface to Java database drivers.
- https://github.com/JuliaDatabases/ODBC.jl : A low-level ODBC interface for the Julia programming language. [Tabular Data I/O in Julia](https://randyzwitch.com/julia-import-data/).
- https://github.com/tanmaykm/Memcache.jl : Julia [memcached](https://github.com/memcached/memcached/wiki/Commands) client.
- https://github.com/tk3369/QuandlAccess.jl : convenient access to [Quandl](https://www.quandl.com/) data service.

## SQL and Relational Database Management Systems

[Wikipedia: SQL](https://en.wikipedia.org/wiki/SQL)

- https://github.com/duckdb/duckdb : an in-process SQL OLAP Database Management System with a Julia API.
- https://github.com/invenia/LibPQ.jl : A Julia wrapper for the PostgreSQL [libpq](https://www.postgresql.org/docs/current/libpq.html) C library.
- https://github.com/JuliaComputing/SQLStrings.jl : `@sql_cmd` macro for SQL query strings.
- https://github.com/JuliaDatabases/MySQL.jl : Julia bindings and helper functions for MariaDB/MySQL C library.
- https://github.com/JuliaDatabases/SQLite.jl : Julia interface to the SQLite library with support for operations on DataFrames.
- https://github.com/MechanicalRabbit/DataKnots.jl : An extensible, practical and coherent algebra of [query combinators](https://arxiv.org/abs/1702.08409).
- https://github.com/propelledanalytics/SparkSQL.jl : working with Apache Spark data using just SQL.
- https://github.com/wookay/Octo.jl : an SQL Query DSL in Julia to be used with other SQL drivers.

## NOSQL databases

[Wikipedia: NOSQL](https://en.wikipedia.org/wiki/NoSQL)

- https://github.com/felipenoris/Mongoc.jl : [MongoDB](http://www.mongodb.org/) bindings (newer) and a wrapper around libbson, for the Julia language.
- https://github.com/JuliaDatabases/Redis.jl : A fully-featured [Redis](https://redis.io/) client for the Julia programming language.
- https://github.com/r3tex/CQLdriver.jl : Interfacing with CQL compliant databases. Used with `DataFrames.jl`.
- https://github.com/ScottPJones/Mongo.jl : [MongoDB](http://www.mongodb.org/) bindings for the Julia programming language.
- https://github.com/wildart/LMDB.jl : A wrapper interface to [Lightning Memory-Mapped Database](https://en.wikipedia.org/wiki/Lightning_Memory-Mapped_Database) (LMDB) key-value embedded data store.

## Accessing datasets

For tabular data file: [[fileio]]

- https://github.com/4gh/WorldBankData.jl : The [World Bank](https://data.worldbank.org/) data.
- https://github.com/dfdx/FaceDatasets.jl : A package for easy access to face-related datasets.
- https://github.com/JuliaStats/RDatasets.jl : Julia package for loading many of the datasets available in R.
- https://github.com/neomatrixcode/Faker.jl : A package that generates fake data.
- https://github.com/oxinabox/DataDeps.jl : reproducible data setup for reproducible science.
- https://github.com/tecosaur/DataToolkit.jl : Providing a data CLI for reproducible, flexible, and convenient data management.
- https://github.com/tecosaur/DataToolkit.jl : Reproducible, flexible, and convenient data management.
