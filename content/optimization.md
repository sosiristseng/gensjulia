---
title: Optimization
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:49:02
---

> [Mathematical Optimization](https://en.wikipedia.org/wiki/Category:Mathematical_optimization) packages in Julia.

## Organizations

- [Julia Smooth Optimizers](https://github.com/JuliaSmoothOptimizers)
- [JuMP-dev](https://github.com/jump-dev)
- [Julia for Dynamic Optimization](https://github.com/JuDO-dev)
- [JuliaNLSolvers](https://github.com/JuliaNLSolvers)
- [SciML](https://github.com/SciML)

## JuMP

[JuMP.jl](https://github.com/jump-dev/JuMP.jl) : Modeling Mathematical Optimization (linear, mixed-integer, conic, semidefinite, nonlinear).

- [JuDO.jl](https://github.com/JuDO-dev/JuDO.jl): solving optimal control problems. See also
- [MathOptInterface.jl](https://github.com/jump-dev/MathOptInterface.jl): An abstraction layer for mathematical optimization solvers.
- [PolyJuMP.jl](https://github.com/jump-dev/PolyJuMP.jl) : A JuMP extension for Polynomial Optimization.
- [Progradio.jl](https://github.com/JuDO-dev/Progradio.jl) : Projected Gradient Optimization. [Julia Con 2023 video](https://www.youtube.com/watch?v=EZ2kq0Obaio)
- [SDDP.jl](https://github.com/odow/SDDP.jl): A JuMP extension for Stochastic Dual Dynamic Programming.
- [StructJuMP.jl](https://github.com/StructJuMP/StructJuMP.jl) : A block-structured optimization framework for JuMP.
- [SumOfSquares.jl](https://github.com/jump-dev/SumOfSquares.jl) : Sum of Squares Programming for Julia.

### External solvers

> Some of them require paid license to work.

- [AmplNLWriter.jl](https://github.com/jump-dev/AmplNLWriter.jl) : an interface between `MathOptInterface.jl` and [AMPL](http://ampl.com/products/solvers/all-solvers-for-ampl/)-enabled solvers.
- [BARON.jl](https://github.com/jump-dev/BARON.jl) : A wrapper for the [BARON](https://minlp.com/baron-solver) mixed-integer nonlinear programming solver.
- [Cbc.jl](https://github.com/jump-dev/Cbc.jl) : Interface to the Coin-OR Cbc solver for mixed-integer programming.
- [Clp.jl](https://github.com/jump-dev/Clp.jl) : Interface to the Coin-OR Linear Programming solver (CLP)
- [CPLEX.jl](https://github.com/jump-dev/CPLEX.jl) : An interface for using IBM's [CPLEX Optimizer](https://www.ibm.com/products/ilog-cplex-optimization-studio)™ from the Julia language.
- [CSDP.jl](https://github.com/jump-dev/CSDP.jl) : Julia wrapper to [CSDP](https://github.com/coin-or/Csdp/) semidefinite programming solver.
- [ECOS.jl](https://github.com/jump-dev/ECOS.jl) : Julia wrapper for the [ECOS](https://github.com/embotech/ecos) conic optimization solver.
- [GLPK.jl](https://github.com/jump-dev/GLPK.jl) : [GLPK](https://www.gnu.org/software/glpk) wrapper module for Julia.
- [Gurobi.j](https://github.com/jump-dev/Gurobi.jl) : a Julia interface for the commercial [Gurobi](https://www.gurobi.com/) Optimizer.
- [Ipopt.jl](https://github.com/jump-dev/Ipopt.jl) : Julia interface to the [Ipopt](https://coin-or.github.io/Ipopt/) nonlinear solver.
- [KNITRO.jl](https://github.com/jump-dev/KNITRO.jl) : Julia interface for [KNITRO solver](https://www.artelys.com/solvers/knitro/).
- [Mosek.jl](https://github.com/MOSEK/Mosek.jl) : Interface to the [Mosek](https://www.mosek.com/) solver in Julia. The interface to JuMP is [MosekTools.jl](https://github.com/jump-dev/MosekTools.jl)
- [NEOSServer.jl](https://github.com/jump-dev/NEOSServer.jl) : A Julia interface for the [NEOS](http://www.neos-server.org/neos) Optimisation Server.
- [SCS.jl](https://github.com/jump-dev/SCS.jl) : Julia Wrapper for [SCS](https://github.com/cvxgrp/scs).
- [Xpress.jl](https://github.com/jump-dev/Xpress.jl) : A Julia interface for the [FICO Xpress solver](https://www.fico.com/en/products/fico-xpress-solver).

## Optimization.jl

[Optimization.jl](https://github.com/SciML/Optimization.jl) : brings together all of the optimization packages it can find, local and global, into one unified Julia interface. The following list comes from it [README](https://github.com/SciML/Optimization.jl#installation).

- `OptimizationBBO`: for [BlackBoxOptim.jl](https://github.com/robertfeldt/BlackBoxOptim.jl) : An experimental, work-in-progress global optimization framework for Julia, supporting both multiand single-objective optimization problems, focused on (meta-)heuristic/stochastic algorithms (DE, PSO, CMA-ES etc).
- `OptimizationEvolutionary`: for [Evolutionary.jl](https://github.com/wildart/Evolutionary.jl) : Evolutionary & genetic algorithms for Julia. [Wikipedia: Genetic algorithm](https://en.wikipedia.org/wiki/Genetic_algorithm)
- `OptimizationGCMAES` for  [GCMAES.jl](https://github.com/AStupidBear/GCMAES.jl): Gradient-based Covariance Matrix Adaptation Evolutionary Strategy for Real Blackbox Optimization.
- `OptimizationIpopt` for [Ipopt.jl](https://github.com/jump-dev/Ipopt.jl)
- `OptimizationLBFGSB` for [LBFGSB.jl](https://github.com/Gnimuc/LBFGSB.jl): Julia wrapper for L-BFGS-B Nonlinear Optimization Code.
- `OptimizationMadNLP` for [MadNLP.jl](https://github.com/MadNLP/MadNLP.jl): a solver for nonlinear programming with GPU support
- `OptimizationManopt` for [Manopt.jl](https://github.com/JuliaManifolds/Manopt.jl) : Optimization on Manifolds in Julia.
- `OptimizationMetaheuristics` for [Metaheuristics.jl](https://github.com/jmejia8/Metaheuristics.jl) : High performance metaheuristics for global optimization.
- `OptimizationMOI` for [MathOptInterface.jl](https://github.com/jump-dev/MathOptInterface.jl)
- `OptimizationMultistartOptimization` for [MultistartOptimization.jl](https://github.com/tpapp/MultistartOptimization.jl)
- `OptimizationNLopt` for [NLopt.jl](https://github.com/JuliaOpt/NLopt.jl) : Package to call the [NLopt](https://nlopt.readthedocs.io/en/latest/) nonlinear-optimization library from the Julia language.
- `OptimizationNLPModels` for [NLPModels.jl](https://github.com/JuliaSmoothOptimizers/NLPModels.jl)
- `OptimizationNOMAD` for [NOMAD.jl](https://github.com/bbopt/NOMAD.jl): a Julia interface for [NOMAD](https://www.gerad.ca/en/software/nomad/), which is a C++ implementation of the Mesh Adaptive Direct Search algorithm (MADS), designed for difficult blackbox optimization problems.
- `OptimizationOptimJL` for [Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl) : Univariate and multivariate optimization solvers in Julia.
- `OptimizationOptimisers` for FluxML's [Optimisers.jl](https://github.com/FluxML/Optimisers.jl).
- `OptimizationPRIMA` for  [PRIMA.jl](https://github.com/libprima/PRIMA.jl): a Julia interface to the [PRIMA library](https://github.com/libprima/prima).
- `OptimizationQuadDIRECT` for [QuadDIRECT.jl](https://github.com/timholy/QuadDIRECT.jl): Global optimization without derivatives.
- `OptimizationSophia` for Sophia optimizer (second-order stochastic optimizer).
- `OptimizationSpeedMapping` for [SpeedMapping.jl](https://github.com/NicolasL-S/SpeedMapping.jl): General fixed point mapping acceleration and optimization in Julia.

## Linear Programming and Optimization

[Wikipedia: Linear Programming-Optimization](https://en.wikipedia.org/wiki/Linear_programming)

- [PiecewiseLinearOpt.jl](https://github.com/joehuchette/PiecewiseLinearOpt.jl) : Optimizing over piecewise linear functions.
- [Tulip.jl](https://github.com/ds4dm/Tulip.jl) : is an open-source interior-point solver for linear optimization, written in pure Julia. It implements the homogeneous primal-dual interior-point algorithm with multiple centrality corrections, and therefore handles unbounded and infeasible problems.

## Nonlinear Programming

[Wikipedia: Nonlinear Programming](https://en.wikipedia.org/wiki/Nonlinear_programming):  some of the constraints are not [linear equalities](https://en.wikipedia.org/wiki/Linear_inequality "Linear inequality") or the objective function is not a [linear function](https://en.wikipedia.org/wiki/Linear_function "Linear function").

- [Convex.jl](https://github.com/jump-dev/Convex.jl) : [Disciplined Convex Programming](http://dcp.stanford.edu/) (DCP).
- [EAGO.jl](https://github.com/PSORLab/EAGO.jl) : A development environment for robust and global optimization. EAGO stands for Easy-Advanced Global Optimization.
- [MadNLP.jl](https://github.com/MadNLP/MadNLP.jl): a solver for nonlinear programming with GPU support

### Julia smooth solvers

[OptimizationProblems.jl](https://github.com/JuliaSmoothOptimizers/OptimizationProblems.jl): This package provides a collection of optimization problems in [JuMP](https://github.com/JuliaOpt/JuMP.jl) and [ADNLPModels](https://github.com/JuliaSmoothOptimizers/ADNLPModels.jl) syntax.

- [AmplNLReader.jl](https://github.com/JuliaSmoothOptimizers/AmplNLReader.jl) : A Julia Interface to [AMPL](http://www.ampl.com/).
- [CUTEst.jl](https://github.com/JuliaSmoothOptimizers/CUTEst.jl) : Julia interface for [CUTEst](https://github.com/ralna/CUTEst/wiki), a repository of constrained and unconstrained nonlinear programming problems for testing and comparing optimization algorithms.
- [HSL.jl](https://github.com/JuliaSmoothOptimizers/HSL.jl) : Julia interface to the HSL Mathematical Software Library.
- [JSOSuite.jl](https://github.com/JuliaSmoothOptimizers/JSOSuite.jl) : accessing all the solvers available in the [JuliaSmoothOptimizers](https://github.com/JuliaSmoothOptimizers) organization.
- [LinearOperators.jl](https://github.com/JuliaSmoothOptimizers/LinearOperators.jl) : Linear Operators for Julia. Operators behave like matrices but are defined by their effect when applied to a vector.
- [NLPModels.jl](https://github.com/JuliaSmoothOptimizers/NLPModels.jl) : Data Structures for non-linear programming (NLP) problems in Julia.

## Misc

- [Hyperopt.jl](https://github.com/baggepinnen/Hyperopt.jl) : A package to perform hyperparameter optimization. Currently supports random search, Latin hypercube sampling and Bayesian optimization.
- [InfiniteOpt.jl](https://github.com/infiniteopt/InfiniteOpt.jl) : An interface for infinite-dimensional optimization problems. e.g. stochastic programming, dynamic programming, space-time optimization. See also the [YouTube video](https://www.youtube.com/watch?v=q5ETFLZbxiU).
- [IntervalConstraintProgramming.jl](https://github.com/JuliaIntervals/IntervalConstraintProgramming.jl) : Calculates the feasible region for a set of real-valued inequalities with Julia.
- [MetaheuristicsAlgorithms.jl](https://github.com/AbdelazimHussien/MetaheuristicsAlgorithms.jl) : a collection of Metaheuristics Algorithms written in Julia. [YT video](https://www.youtube.com/watch?v=WxyuBafDloU)
- [OSQP.jl](https://github.com/osqp/OSQP.jl) : A Julia wrapper for the Operator Splitting Quadratic Program ([OSQP](https://osqp.org/)) solver, a numerical optimization package.
- [SMM.jl](https://github.com/floswald/SMM.jl) : [Simulated Method of Moments](https://en.wikipedia.org/wiki/Method_of_simulated_moments) for Julia.
