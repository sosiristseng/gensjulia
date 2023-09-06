---
title: Data Science
draft: false
tags: []
---

> Data retrieval, manipulation, and storage in Julia.

## Organizations

- [Julia ML](https://github.com/JuliaML)
- [Julia Data](https://github.com/JuliaData)
- [Julia Databases](https://github.com/JuliaDatabases)
- [Julia stats](https://github.com/JuliaStats)

## Resources

- Blog on [The Lesser Known Normal Forms of Database Design](http://www.johnmyleswhite.com/notebook/2014/09/10/the-lesser-known-normal-forms/)
- [Database-like ops benchmark](https://h2oai.github.io/db-benchmark/) of different languages and libraries.
- [Julia-data-science](https://github.com/tirthajyoti/Julia-data-science) : Notebooks on DS basics with Julia and why it is suitable for data science.
- [Julia DataFrames Tutorial](https://github.com/bkamins/Julia-DataFrames-Tutorial) by Bogumił Kamiński.

## General purpose

- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) : In-memory tabular data in Julia.
- [Tables.jl](https://github.com/JuliaData/Tables.jl) : An generic interface for tables in Julia.


## Data Manipulation

- [Cleaner.jl](https://github.com/TheRoniOne/Cleaner.jl) : A toolbox of simple solutions for common data cleaning problems.
- [DataFrameMacros.jl](https://github.com/jkrumbiegel/DataFrameMacros.jl) : an opinionated take on DataFrame manipulation in Julia with a syntax geared towards clarity, brevity and convenience.
- [DataFramesMeta.jl](https://github.com/JuliaData/DataFramesMeta.jl) : Metaprogramming tools for `DataFrame`s and `AbstractDict` objects. These macros improve performance and provide more convenient syntax.
- [InMemoryDatasets.jl](https://github.com/sl-solution/InMemoryDatasets.jl) : Multithreaded package for working with tabular data in Julia.
- [Pandas.jl](https://github.com/JuliaPy/Pandas.jl) : A Julia front-end to Python's `pandas` package.
- [TableOperations.jl](https://github.com/JuliaData/TableOperations.jl) : Common table operations on `Tables.jl` interface implementations.

## DataBase API

- [DBInterface.jl](https://github.com/JuliaDatabases/DBInterface.jl) : An abstract DBI interface to provide a database-independent API protocol that all database drivers can be expected to comply with.
- [IndexedTables.jl](https://github.com/JuliaData/IndexedTables.jl) : Tabular data structures where some of the columns form a sorted index. It provides the backend to `JuliaDB.jl`.
- [JDBC.jl](https://github.com/JuliaDatabases/JDBC.jl) : Julia interface to Java database drivers.
- [JuliaDB.jl](https://github.com/JuliaData/JuliaDB.jl) : working with large persistent data sets.
- [LevelDB.jl](https://github.com/jerryzhenleicai/LevelDB.jl) : Julia interface to Google's LevelDB key value database.
- [Memcache.jl](https://github.com/tanmaykm/Memcache.jl) : Julia [memcached](https://github.com/memcached/memcached/wiki/Commands) client.
- [ODBC.jl](https://github.com/JuliaDatabases/ODBC.jl) : A low-level ODBC interface for the Julia programming language. [Tabular Data I/O in Julia](https://randyzwitch.com/julia-import-data/).

## SQL and Relational Database Management Systems

- [DataKnots.jl](https://github.com/MechanicalRabbit/DataKnots.jl) : An extensible, practical and coherent algebra of [query combinators](https://arxiv.org/abs/1702.08409).
- [duckdb](https://github.com/duckdb/duckdb) : an in-process SQL OLAP Database Management System with a Julia API.
- [LibPQ.jl](https://github.com/invenia/LibPQ.jl) : A Julia wrapper for the PostgreSQL [libpq](https://www.postgresql.org/docs/current/libpq.html) C library.
- [MySQL.jl](https://github.com/JuliaDatabases/MySQL.jl) : Julia bindings and helper functions for MariaDB/MySQL C library.
- [Octo.jl](https://github.com/wookay/Octo.jl) : an SQL Query DSL in Julia to be used with other SQL drivers.
- [SparkSQL.jl](https://github.com/propelledanalytics/SparkSQL.jl) : working with Apache Spark data using just SQL.
- [SQLite.jl](https://github.com/JuliaDatabases/SQLite.jl) : Julia interface to the SQLite library with support for operations on DataFrames.
- [SQLStrings.jl](https://github.com/JuliaComputing/SQLStrings.jl) : `@sql_cmd` macro for SQL query strings.

## NOSQL databases

- [CQLdriver.jl](https://github.com/r3tex/CQLdriver.jl) : Interfacing with CQL compliant databases. Used with `DataFrames.jl`.
- [LMDB.jl](https://github.com/wildart/LMDB.jl) : A wrapper interface to [Lightning Memory-Mapped Database](https://en.wikipedia.org/wiki/Lightning_Memory-Mapped_Database) (LMDB) key-value embedded data store.
- [Mongo.jl](https://github.com/ScottPJones/Mongo.jl) : [MongoDB](http://www.mongodb.org/) bindings for the Julia programming language.
- [Mongoc.jl](https://github.com/felipenoris/Mongoc.jl) : [MongoDB](http://www.mongodb.org/) bindings (newer) and a wrapper around libbson, for the Julia language.
- [Redis.jl](https://github.com/JuliaDatabases/Redis.jl) : A fully-featured [Redis](https://redis.io/) client for the Julia programming language.

## Accessing datasets

- [DataDeps.jl](https://github.com/oxinabox/DataDeps.jl): reproducible data setup for reproducible science.
- [FaceDatasets.jl](https://github.com/dfdx/FaceDatasets.jl) : A package for easy access to face-related datasets.
- [Faker.jl](https://github.com/neomatrixcode/Faker.jl) : A package that generates fake data.
- [RDatasets.jl](https://github.com/JuliaStats/RDatasets.jl) : Julia package for loading many of the datasets available in R.
- [WorldBankData.jl](https://github.com/4gh/WorldBankData.jl) : The [World Bank](https://data.worldbank.org/) data.
