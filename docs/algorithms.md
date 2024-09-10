---
title: Algorithms
---

> Generic algorithms for Julia.

## Resources

- [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) : a curated list of awesome places to learn and/or practice algorithms.
- [BeautifulAlgorithms.jl](https://github.com/mossr/BeautifulAlgorithms.jl) : Concise and beautiful algorithms written in Julia.
- [Project_Euler_Julia.ipynb](https://nbviewer.org/github/punkrockpolly/Playing-with-Julia/blob/master/Project_Euler_Julia.ipynb) : Solutions to [Project Euler](https://projecteuler.net) Problems, algorithm & math puzzles.

## Sorting

[Wikipedia: Sorting algorithm](https://en.wikipedia.org/wiki/Sorting_algorithm)

- https://github.com/JuliaCollections/SortingAlgorithms.jl : extra sorting algorithms extending Julia's sorting API.
- https://github.com/JuliaStrings/NaturalSort.jl : [Natural sort order](https://en.wikipedia.org/wiki/Natural_sort_order).
- https://github.com/xiaodaigh/SortingLab.jl : Experimental faster sorting algorithms.

## NP-complete Problems

[Wikipedia: NP-complete](https://en.wikipedia.org/wiki/Category:NP-complete_problems) problems cannot be solved in polynomial time complexity and often have to be inexactly solved using heuristics.

### Traveling salesman problem

[Wikipedia: Traveling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem)

- https://github.com/evanfields/TravelingSalesmanHeuristics.jl : Julia package for simple traveling salesman problem heuristics.

### Boolean satisfiability problem (SAT)

[Wikipedia: SAT](https://en.wikipedia.org/wiki/Satisfiability_modulo_theories) is a kind of NP-complete (NPC) problems.

- https://github.com/dpsanders/SimpleSATSolver.jl : A (very) simple SAT solver in pure Julia.
- https://github.com/sisl/PicoSAT.jl : Provides Julia bindings to the popular SAT solver [picosat](http://fmv.jku.at/picosat/) by Armin Biere.

## Genetic algorithm

[Wikipedia: Genetic algorithm](https://en.wikipedia.org/wiki/Genetic_algorithm). See also the [[optimization]] section.

- https://github.com/wildart/Evolutionary.jl : Evolutionary & genetic algorithms for Julia.

## Homomorphic encryption

[Wikipedia: Homomorphic encryption](https://en.wikipedia.org/wiki/Homomorphic_encryption)

- https://github.com/hpsc-lab/SecureArithmetic.jl : Secure arithmetic operations using fully homomorphic encryption.
- https://github.com/hpsc-lab/OpenFHE.jl : Fully homomorphic encryption in Julia using [OpenFHE](https://github.com/openfheorg/openfhe-development).
