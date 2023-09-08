---
title: Algorithms
draft: false
tags: []
---

> Generic algorithms for Julia.

## Resources

- [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) : a curated list of awesome places to learn and/or practice algorithms.
- [BeautifulAlgorithms.jl](https://github.com/mossr/BeautifulAlgorithms.jl) : Concise and beautiful algorithms written in Julia.
- [Project_Euler_Julia.ipynb](https://nbviewer.org/github/punkrockpolly/Playing-with-Julia/blob/master/Project_Euler_Julia.ipynb) : Solutions to [Project Euler](https://projecteuler.net) Problems, algorithm & math puzzles.

## Sorting

[Wikipedia: Sorting algorithm](https://en.wikipedia.org/wiki/Sorting_algorithm)

- [NaturalSort.jl](https://github.com/JuliaStrings/NaturalSort.jl) : [Natural sort order](https://en.wikipedia.org/wiki/Natural_sort_order).
- [SortingAlgorithms.jl](https://github.com/JuliaCollections/SortingAlgorithms.jl) : extra sorting algorithms extending Julia's sorting API.
- [SortingLab.jl](https://github.com/xiaodaigh/SortingLab.jl) : Experimental faster sorting algorithms.

## Pattern Matching

- [BlossomV.jl](https://github.com/mlewe/BlossomV.jl) : An interface for the Blossom V perfect (graph) matching algorithm. (**paid license**)
- [Loess.jl](https://github.com/JuliaStats/Loess.jl) : is a [loess implementation](https://en.wikipedia.org/wiki/Local_regression) based on the fast kd-tree based approximation algorithm, a space-partitioning data structure for organizing points in a k-dimensional space.
- [Match.jl](https://github.com/JuliaServices/Match.jl) : Advanced Pattern Matching for Julia.
- [MLStyle.jl](https://github.com/thautwarm/MLStyle.jl) : Julia functional programming infrastructures and metaprogramming facilities.
- [SimpleMatch.jl](https://github.com/jolin-io/SimpleMatch.jl) : a simple Julia pattern matching package providing only the `@match` macro.

## NP-complete Problems

[Wikipedia: NP-complete](https://en.wikipedia.org/wiki/Category:NP-complete_problems) problems cannot be solved in polynomial time complexity and often have to be inexactly solved using heuristics.

### Traveling salesman problem

[Wikipedia: Traveling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem)

- [TravelingSalesmanHeuristics.jl](https://github.com/evanfields/TravelingSalesmanHeuristics.jl) : Julia package for simple traveling salesman problem heuristics.

### Boolean satisfiability problem (SAT)

[Wikipedia: SAT](https://en.wikipedia.org/wiki/Satisfiability_modulo_theories) is a kind of NP-complete (NPC) problems.

- [PicoSAT.jl](https://github.com/sisl/PicoSAT.jl) : Provides Julia bindings to the popular SAT solver [picosat](http://fmv.jku.at/picosat/) by Armin Biere.
- [SimpleSATSolver.jl](https://github.com/dpsanders/SimpleSATSolver.jl) : A (very) simple SAT solver in pure Julia.

## Genetic algorithm

[Wikipedia: Genetic algorithm](https://en.wikipedia.org/wiki/Genetic_algorithm)

- [Evolutionary.jl](https://github.com/wildart/Evolutionary.jl) : Evolutionary & genetic algorithms for Julia.
