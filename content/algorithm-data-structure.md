---
title: Algorithms and Data Structures
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:44:05
---

> Generic algorithms and data structures.

See also:
- [[cryptography]]
- [[graph]] theory
- [[optimization]]
- [[mathematics]]
- [[text-string]] and string
- [[dsp]]

## Organizations

- [Julia Collections](https://github.com/JuliaCollections) organization
- [Julia ArbTypes](https://github.com/JuliaArbTypes) organization

## Resources

- [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) : a curated list of awesome places to learn and/or practice algorithms.
- [BeautifulAlgorithms.jl](https://github.com/mossr/BeautifulAlgorithms.jl) : Concise and beautiful algorithms written in Julia.
- [Project_Euler_Julia.ipynb](https://nbviewer.org/github/punkrockpolly/Playing-with-Julia/blob/master/Project_Euler_Julia.ipynb) : Solutions to [Project Euler](https://projecteuler.net) Problems, algorithm & math puzzles.
- [Youtube: The State of the Type System](https://www.youtube.com/watch?v=Z2LtJUe1q8c) at JuliaCon 2017 by Jeff Bezanson
- [Youtube: The Unreasonable Effectiveness of Multiple Dispatch](https://youtu.be/kc9HwsxE1OY)  at JuliaCon 2019 by Stefan Karpinski

## Sorting

[Wikipedia: Sorting algorithm](https://en.wikipedia.org/wiki/Sorting_algorithm)

- [NaturalSort.jl](https://github.com/JuliaStrings/NaturalSort.jl) : [Natural sort order](https://en.wikipedia.org/wiki/Natural_sort_order).
- [SortingAlgorithms.jl](https://github.com/JuliaCollections/SortingAlgorithms.jl) : extra sorting algorithms extending Julia's sorting API.
- [SortingLab.jl](https://github.com/xiaodaigh/SortingLab.jl) : Experimental faster sorting algorithms.

## NP-complete Problems

[Wikipedia: NP-complete](https://en.wikipedia.org/wiki/Category:NP-complete_problems) problems cannot be solved in polynomial time complexity and often have to be inexactly solved using heuristics.

### Traveling salesman problem

[Wikipedia: Traveling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem)

- [SortingLab.jl](https://github.com/evanfields/TravelingSalesmanHeuristics.jl) : Julia package for simple traveling salesman problem heuristics.

### Boolean satisfiability problem (SAT)

[Wikipedia: SAT](https://en.wikipedia.org/wiki/Satisfiability_modulo_theories) is a kind of NP-complete (NPC) problems.

- [PicoSAT.jl](https://github.com/sisl/PicoSAT.jl) : Provides Julia bindings to the popular SAT solver [picosat](http://fmv.jku.at/picosat/) by Armin Biere.
- [SimpleSATSolver.jl](https://github.com/dpsanders/SimpleSATSolver.jl) : A (very) simple SAT solver in pure Julia.

## General data structures

- [Air.jl](https://github.com/noahbenson/Air.jl) : an immutable data structure and software transactional memory tool for Julia.
- [DataStructures.jl](https://github.com/JuliaCollections/DataStructures.jl) : Julia implementation of Data structures.
- [Interfaces.jl](https://github.com/rafaqz/Interfaces.jl) : Macros to define and implement interfaces, to ensure they are checked and correct. [JuliaCon 2024 video](https://youtu.be/TbBrFg8BT-w)
- [LRUCache.jl](https://github.com/JuliaCollections/LRUCache.jl) : An implementation of a Least Recently Used (LRU) Cache.
- [RingBuffers.jl](https://github.com/JuliaAudio/RingBuffers.jl) : A simple non-allocating circular RingBuffer type, with configurable overflow and underflow handling.
- [TypeSortedCollections.jl](https://github.com/tkoolen/TypeSortedCollections.jl) : It provides the `TypeSortedCollection` type, which can be used to store type-heterogeneous data in a way that allows operations on the data to be performed in a type-stable manner.

### Function object

- [FunctionalCollections.jl](https://github.com/JuliaCollections/FunctionalCollections.jl) : Functional and and persistent data structures for Julia.

### Result types

- [ResultTypes.jl](https://github.com/iamed2/ResultTypes.jl) : A Result type for returning a value or an error in a type-stable manner without throwing an exception.
- [ErrorTypes.jl](https://github.com/jakobnissen/ErrorTypes.jl) : A simple implementation of Rust-like error handling in Julia.

## Composite Data Types

[Wikipedia: Composite Data Types](https://en.wikipedia.org/wiki/Category:Composite_data_types)

- [`Base.@kwdef`](https://discourse.julialang.org/t/what-does-kwdef-do/51973) : a concise struct construction in the Julia base.

---

- [Bijections.jl](https://github.com/scheinerman/Bijections.jl) : Bijection datatype for Julia that blocks assigning the same value to two different keys.
- [ConcreteStructs.jl](https://github.com/jonniedie/ConcreteStructs.jl) : `@concrete` can be used to make non-concrete structs concrete without the boilerplate of adding type parameters.
- [DictArrays.jl](https://github.com/JuliaAPlavin/DictArrays.jl) : Efficient wide columnar tables: like `StructArrays`, but dict-based. [JuliaCon 2025](https://youtu.be/xFi2jnG3ohQ)
- [Dictionaries.jl](https://github.com/andyferris/Dictionaries.jl) : An alternative interface for dictionaries `Dict` in Julia, for improved productivity and performance.
- [DispatchedTuples.jl](https://github.com/charleskawczynski/DispatchedTuples.jl) : `Dispatched Tuples` are like immutable dictionaries (so, they're technically more like `NamedTuples`) except that the keys are instances of types. Also, because DispatchedTuples are backed by tuples, they are GPU-friendly.
- [OrderedCollections.jl](https://github.com/JuliaCollections/OrderedCollections.jl): Julia implementation of associative containers that preserve insertion order.
- [TypeParams.jl](https://github.com/synchronoustechnologies/TypeParams.jl) : keeping compile-time type information in `struct` for better performance.

### Accessing elements

- [Accessors.jl](https://github.com/JuliaObjects/Accessors.jl) : updating immutable data simple. It is the successor of [Setfield.jl](https://github.com/jw3126/Setfield.jl). [JuliaCon 2025 video](https://youtu.be/QxrlgVx0KnM?si=r4m4Ze7LRUqnfU-O)
- [Parameters.jl](https://github.com/mauro3/Parameters.jl) : Types with default field values, keyword constructors and (un-)pack macros.
- [SimpleUnPack.jl](https://github.com/devmotion/SimpleUnPack.jl) : Lightweight Julia macro for destructuring properties and fields, similar to `UnPack.jl`. (Requires Julia >= 1.7)
- [UnPack.jl](https://github.com/mauro3/UnPack.jl) : `@unpack` some or all of the fields of a type, and `@pack`, in the case of mutable data types.
