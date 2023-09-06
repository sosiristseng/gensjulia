---
title: Optimization
draft: false
tags: []
---

[Mathematical Optimization](https://en.wikipedia.org/wiki/Category:Mathematical_optimization) packages in Julia

- [JuMP-dev](https://github.com/jump-dev)
- [Julia Opt](https://github.com/JuliaOpt)
- [Julia Smooth Optimizers](https://github.com/JuliaSmoothOptimizers)

## Frameworks

- [JuMP.jl](https://github.com/jump-dev/JuMP.jl) : Modeling Mathematical Optimization (linear, mixed-integer, conic, semidefinite, nonlinear).
- [Optimization.jl](https://github.com/SciML/Optimization.jl) : brings together all of the optimization packages it can find, local and global, into one unified Julia interface.

## Bindings for external solvers

> Some of them require paid license to work.

- [AmplNLReader.jl](https://github.com/JuliaSmoothOptimizers/AmplNLReader.jl) : A Julia Interface to [AMPL](http://www.ampl.com/).
- [AmplNLWriter.jl](https://github.com/jump-dev/AmplNLWriter.jl) : an interface between `MathOptInterface.jl` and AMPL-enabled solvers.
- [Cbc.jl](https://github.com/jump-dev/Cbc.jl) : Interface to the Coin-OR Cbc solver for mixed-integer programming.
- [CPLEX.jl](https://github.com/jump-dev/CPLEX.jl) : An interface for using IBM's [CPLEX Optimizer](https://www.ibm.com/products/ilog-cplex-optimization-studio)™ from the Julia language.
- [CSDP.jl](https://github.com/jump-dev/CSDP.jl) : Julia wrapper to [CSDP](https://github.com/coin-or/Csdp/) semidefinite programming solver.
- [CUTEst.jl](https://github.com/JuliaSmoothOptimizers/CUTEst.jl) : Julia interface for [CUTEst](https://github.com/ralna/CUTEst/wiki), a repository of constrained and unconstrained nonlinear programming problems for testing and comparing optimization algorithms.
- [ECOS.jl](https://github.com/jump-dev/ECOS.jl) : Julia wrapper for the ECOS conic optimization solver.
- [GLPK.jl](https://github.com/jump-dev/GLPK.jl) : GLPK wrapper module for Julia.
- [GLPKMathProgInterface.jl](https://github.com/JuliaOpt/GLPKMathProgInterface.jl) : Interface between the GLPK.jl wrapper and MathProgBase.jl.
- [Gurobi.jl](https://github.com/jump-dev/Gurobi.jl) : a Julia interface for the commercial [Gurobi](https://www.gurobi.com/) Optimizer.
- [HSL.jl](https://github.com/JuliaSmoothOptimizers/HSL.jl) : Julia interface to the HSL Mathematical Software Library.
- [Ipopt.jl](https://github.com/jump-dev/Ipopt.jl) : Julia interface to the [Ipopt](https://coin-or.github.io/Ipopt/) nonlinear solver.
- [KNITRO.jl](https://github.com/jump-dev/KNITRO.jl) : Julia interface for [KNITRO solver](https://www.artelys.com/solvers/knitro/).
- [Mosek.jl](https://github.com/MOSEK/Mosek.jl) : Interface to the Mosek solver in Julia.
- [NEOSServer.jl](https://github.com/odow/NEOSServer.jl) : A Julia interface for the NEOS Optimisation Server.
- [NLopt.jl](https://github.com/JuliaOpt/NLopt.jl) : Package to call the [NLopt](https://nlopt.readthedocs.io/en/latest/) nonlinear-optimization library from the Julia language.
- [SCS.jl](https://github.com/jump-dev/SCS.jl) : Julia Wrapper for [SCS](https://github.com/cvxgrp/scs).
- [Xpress.jl](https://github.com/jump-dev/Xpress.jl) : A Julia interface for the [FICO Xpress solver](https://www.fico.com/en/products/fico-xpress-solver).

## Linear Programming and Optimization

[Wikipedia: Linear Programming-Optimization](https://en.wikipedia.org/wiki/Linear_programming)

- [Clp.jl](https://github.com/jump-dev/Clp.jl) : Interface to the Coin-OR Linear Programming solver (CLP)
- [NLPModels.jl](https://github.com/JuliaSmoothOptimizers/NLPModels.jl) : Data Structures for Optimization Models.
- [PiecewiseLinearOpt.jl](https://github.com/joehuchette/PiecewiseLinearOpt.jl) : Optimizing over piecewise linear functions.
- [Tulip.jl](https://github.com/ds4dm/Tulip.jl) : is an open-source interior-point solver for linear optimization, written in pure Julia. It implements the homogeneous primal-dual interior-point algorithm with multiple centrality corrections, and therefore handles unbounded and infeasible problems.

## Nonlinear Programming

[Wikipedia: Nonlinear Programming](https://en.wikipedia.org/wiki/Nonlinear_programming)

- [BARON.jl](https://github.com/jump-dev/BARON.jl) : A wrapper for the BARON mixed-integer nonlinear programming solver.
- [ConicNonlinearBridge.jl](https://github.com/mlubin/ConicNonlinearBridge.jl) : Wrapper to solve [conic](https://mathprogbasejl.readthedocs.io/en/latest/conic.html) optimization problems with derivative-based nonlinear solvers.
- [Convex.jl](https://github.com/jump-dev/Convex.jl) : A Julia library for mathematical programming that makes it easy to formulate and fast to solve nonlinear convex optimization problems.
- [EAGO.jl](https://github.com/PSORLab/EAGO.jl) : A development environment for robust and global optimization. EAGO stands for Easy-Advanced Global Optimization.

## Misc

- [AutomotiveDrivingModels.jl](https://github.com/sisl/AutomotiveDrivingModels.jl) : Driving simulation architecture for Julia.
- [BlackBoxOptim.jl](https://github.com/robertfeldt/BlackBoxOptim.jl) : An experimental, work-in-progress global optimization framework for Julia, supporting both multi- and single-objective optimization problems, focused on (meta-)heuristic/stochastic algorithms (DE, PSO, CMA-ES etc).
- [CharibdeOptim.jl](https://github.com/JuliaIntervals/CharibdeOptim.jl) : A Julia implementation of the cooperative solver Charibde in which it uses two parallel running algorithms *Differential Evolution* and *Interval Branch & Contract algorithm* to achieve solution of any difficult problem.
- [IntervalConstraintProgramming.jl](https://github.com/JuliaIntervals/IntervalConstraintProgramming.jl) :  Calculates the feasible region for a set of real-valued inequalities with Julia.
- [CutPools.jl](https://github.com/joehuchette/CutPools.jl) : Pools of cutting planes for JuMP models.
- [EntropicCone.jl](https://github.com/blegat/EntropicCone.jl) : Entropic Cone approximation and optimization.
- [Hyperopt.jl](https://github.com/baggepinnen/Hyperopt.jl) : A package to perform hyperparameter optimization. Currently supports random search, latin hypercube sampling and Bayesian optimization.
- [InfiniteOpt.jl](https://github.com/infiniteopt/InfiniteOpt.jl) : An interface for infinite-dimensional optimization problems. e.g. stochastic programming, dynamic programming, space-time optimization. See also the [YouTube video](https://www.youtube.com/watch?v=q5ETFLZbxiU).
- [LinearOperators.jl](https://github.com/JuliaSmoothOptimizers/LinearOperators.jl) : Linear Operators for Julia. Operators behave like matrices but are defined by their effect when applied to a vector.
- [LsqFit.jl](https://github.com/JuliaNLSolvers/LsqFit.jl) : Simple curve fitting functionality from `Optim.jl` has been moved into its own package.
- [Manopt.jl](https://github.com/JuliaManifolds/Manopt.jl) : Optimization on Manifolds in Julia.
- [MathProgBase.jl](https://github.com/JuliaOpt/MathProgBase.jl) : Solver-independent functions (incl. linprog and mixintprog) and low-level interface for Mathematical Programming.
- [Mayday.jl](https://github.com/rdeits/Mayday.jl) : Sums-of-Squares optimization through semidefinite programming (SDP) in Julia, powered by JuMP.
- [Metaheuristics.jl](https://github.com/jmejia8/Metaheuristics.jl) : High performance metaheuristics for optimization purely coded in Julia.
- [Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl) : A basic optimization algorithms implementation.
- [OSQP.jl](https://github.com/osqp/OSQP.jl) : A Julia wrapper for the Operator Splitting Quadratic Program (OSQP) solver is a numerical optimization package.
- [PolyJuMP.jl](https://github.com/jump-dev/PolyJuMP.jl) : A JuMP extension for Polynomial Optimization.
- [QuadDIRECT.jl](https://github.com/timholy/QuadDIRECT.jl) : Global optimization without derivatives.
- [SemidefiniteModels.jl](https://github.com/JuliaOpt/SemidefiniteModels.jl) : A MathProgBase extension for Semidefinite Modelling.
- [SMM.jl](https://github.com/floswald/SMM.jl) : Simulated Method of Moments for Julia.
- [StructDualDynProg.jl](https://github.com/JuliaStochOpt/StructDualDynProg.jl) : Implementation of SDDP (Stochastic Dual Dynamic Programming) using the StructJuMP modeling interface.
- [StructJuMP.jl](https://github.com/StructJuMP/StructJuMP.jl) : A block-structured optimization framework for JuMP.
- [SumOfSquares.jl](https://github.com/jump-dev/SumOfSquares.jl) : Sum of Squares Programming for Julia.
- [Surrogates.jl](https://github.com/SciML/Surrogates.jl) : Surrogate modeling and optimization.
- [TrafficAssignment.jl](https://github.com/chkwon/TrafficAssignment.jl) : A package for traffic assignment that loads the network data and finds the user equilibrium traffic pattern.
