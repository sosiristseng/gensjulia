---
title: Modeling and simulation
draft: false
tags: []
---

General modeling and simulation packages in Julia.

## Organizations

- [ModiaSim](https://github.com/ModiaSim)
- [SciML](https://github.com/SciML)
- [Julia Dynamics](https://juliadynamics.github.io/JuliaDynamics/)

## File IO for models

- [SBML.jl](https://github.com/LCSB-BioCore/SBML.jl) : Julia interface to the Systems Biology Markup Language (SBML) library.
- [SBMLToolkit.jl](https://github.com/SciML/SBMLToolkit.jl) : importing models specified in the Systems Biology Markup Language (SBML) into the Julia SciML ecosystem.
- [CellMLToolkit.jl](https://github.com/SciML/CellMLToolkit.jl) : a Julia library that connects `CellML` models to the Scientific Julia ecosystem.
- [ReactionNetworkImporters.jl](https://github.com/SciML/ReactionNetworkImporters.jl) : Loading BioNetGen `.net` file.

## Symbolic Computation

[Wikipedia: Symbolic Computation](https://en.wikipedia.org/wiki/Symbolic_computation)

- [Reduce.jl](https://github.com/chakravala/Reduce.jl) : Symbolic parser generator for Julia language expressions using REDUCE algebra term rewriter.
- [Symata.jl](https://github.com/jlapeyre/Symata.jl) : language for symbolic mathematics.
- [SymbolicRegression.jl](https://github.com/MilesCranmer/SymbolicRegression.jl) : Distributed High-Performance symbolic regression in Julia.
- [Symbolics.jl](https://github.com/JuliaSymbolics/Symbolics.jl) : A fast and modern CAS for a fast and modern language.
- [SymEngine.jl](https://github.com/symengine/SymEngine.jl) : Julia wrappers of [SymEngine](https://github.com/symengine/symengine).
- [SymPy.jl](https://github.com/JuliaPy/SymPy.jl) : Julia interface to [SymPy](https://www.sympy.org/) via `PyCall.jl`.

## Data structures

See also [[Data Structures]].

- [ComponentArrays.jl](https://github.com/jonniedie/ComponentArrays.jl) : Arrays with arbitrarily nested named components.
- [LabelledArrays.jl](https://github.com/SciML/LabelledArrays.jl) : Arrays with a label for each element.
- [RecursiveArrayTools.jl](https://github.com/SciML/RecursiveArrayTools.jl) : Tools for easily handling nestings array objects like arrays of arrays.

## Differential equations

[Wikipedia: Differential equations](https://en.wikipedia.org/wiki/Differential_equation)

- [Catalyst.jl](https://github.com/SciML/Catalyst.jl) : Domain-specific language (DSL) for chemical reaction networks.
- [DataDrivenDiffEq.jl](https://github.com/SciML/DataDrivenDiffEq.jl) : Data driven modeling and automated discovery of dynamical systems.
- [DiffEqFlux.jl](https://github.com/SciML/DiffEqFlux.jl): Combining DifferentialEquations.jl and Flux.jl as its building blocks to support research in Scientific Machine Learning, specifically neural differential equations and universal differential equations.
- [SciMLSensitivity.jl](https://github.com/SciML/SciMLSensitivity.jl) : A component of the DiffEq ecosystem for sensitivity analysis.
- [DifferentialEquations.jl](https://github.com/SciML/DifferentialEquations.jl) : High-performance solvers of differential equations.
- [DiffModels.jl](https://github.com/DrugowitschLab/DiffModels.jl) : Diffusion Model simulation and first-passage time densities in Julia.
- [DynamicalSystems.jl](https://github.com/JuliaDynamics/DynamicalSystems.jl) : Julia software library for the exploration of chaos and nonlinear dynamics.
- [FdeSolver.jl](https://github.com/JuliaTurkuDataScience/FdeSolver.jl) : A Julia package for the numerical solution of fractional differential equations (FDEs) as well as systems of equations.
- [LatentDiffEq.jl](https://github.com/gabrevaya/LatentDiffEq.jl) : A high-level Flux + DiffEq library solving Generative ODE modeling with Known Unknowns (GOKU). [JuliaCon 2021 video](https://youtu.be/jhIgs4swrMA)
- [ModelingToolkit.jl](https://github.com/SciML/ModelingToolkit.jl) : A modeling framework for automatically parallelized scientific machine learning (SciML) in Julia.
- [ModelingToolkitDesigner.jl](https://github.com/bradcarman/ModelingToolkitDesigner.jl) : A helper tool for visualizing and editing a ModelingToolkit.jl system connections.
- [Modia.jl](https://github.com/ModiaSim/Modia.jl) : Modia is a Julia package for modeling and simulation of multidomain engineering systems described by differential equations, algebraic equations, and (space-discretized) partial differential equations.
- [Pathogen.jl](https://github.com/jangevaare/Pathogen.jl) : Utilities to simulate and perform inference of disease dynamics.
- [QuDiffEq.jl](https://github.com/QuantumBFS/QuDiffEq.jl) : Quantum Algorithms for solving differential equations
- [RiemannHilbert.jl](https://github.com/JuliaHolomorphic/RiemannHilbert.jl) : A Julia package for solving Riemann–Hilbert problems.
- [SimJulia.jl](https://github.com/BenLauwens/SimJulia.jl) : A discrete event process oriented simulation framework written in Julia.
- [SingularIntegralEquations.jl](https://github.com/JuliaApproximation/SingularIntegralEquations.jl) : An experimental Julia package for solving singular integral equations.
- [Sundials.jl](https://github.com/SciML/Sundials.jl) : A Julia package that interfaces to the [Sundials](https://computing.llnl.gov/projects/sundials) library and includes a nonlinear solver (KINSOL), ODE's (CVODE), and DAE's (IDA).


### Partial Differential Equations

- [Wikipedia: Finite difference method](https://en.wikipedia.org/wiki/Finite_difference_method)
- [Wikipedia: Finite element method](https://en.wikipedia.org/wiki/Finite_element_method)
- [Wikipedia: Finite volume method](https://en.wikipedia.org/wiki/Finite_volume_method)

- [PtFEM.jl](https://github.com/PtFEM/PtFEM.jl) : Book "[Programming the Finite Element Method](https://www.wiley.com/en-us/Programming+the+Finite+Element+Method,+5th+Edition-p-9781119973348)" by I M Smith, D V Griffiths and L Margetts.

---

- [ClimaCore.jl](https://github.com/CliMA/ClimaCore.jl) : Tools for building spatial discretizations. [JuliaCon 2021 video](https://youtu.be/4bQvF3rGB84)
- [DiffEqOperators.jl](https://github.com/SciML/DiffEqOperators.jl) : Linear operators for discretizations of differential equations.
- [FEMBasis.jl](https://github.com/JuliaFEM/FEMBasis.jl) : Package contains interpolation routines for standard finite element function spaces.
- [FinEtools.jl](https://github.com/PetrKryslUCSD/FinEtools.jl) : `FinEtools` is a package for basic operations on finite element meshes: Construction, modification, selection, and evaluation of quantities defined on a mesh.
- [FourierFlows.jl](https://github.com/FourierFlows/FourierFlows.jl) : Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains.
- [Gridap.jl](https://github.com/gridap/Gridap.jl) : Grid-based approximation of PDEs with finite element (FE) discretizations.
- [Heptapus.jl](https://github.com/lcw/Heptapus.jl) : The roofline function is a translation of the [roofline code](https://github.com/paranumal/libparanumal/), Accelerated finite element flow solvers.
- [JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl) : Finite Element method solver.
- [JuliaSmoothOptimizers.jl](https://github.com/JuliaSmoothOptimizers/Krylov.jl) : A Julia Basket of Hand-Picked Krylov Methods.
- [LinearAlgebraicRepresentation.jl](https://github.com/cvdlab/LinearAlgebraicRepresentation.jl) : Official Julia implementation of [LAR](https://linkinghub.elsevier.com/retrieve/pii/S001044851300184X), the Linear Algebraic Representation for Solid Modeling. LAR is a general representation scheme for geometric and topological modeling.
- [MethodOfLines.jl](https://github.com/SciML/MethodOfLines.jl) : Automatic Finite Difference PDE solving with Julia.
- [NeuralOperators.jl](https://github.com/SciML/NeuralOperators.jl) : Learning the solution operator for partial differential equations in pure Julia.
- [NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) : Physics-Informed Neural Networks (PINN) and Deep BSDE Solvers of Differential Equations.
- [PETSc.jl](https://github.com/JuliaParallel/PETSc.jl) : A Julia interface for [PETSc](https://www.mcs.anl.gov/petsc/).
- [Trixi.jl](https://github.com/trixi-framework/Trixi.jl) : Adaptive high-order numerical simulations of hyperbolic PDEs in Julia.  [JuliaCon 2021 video](https://youtu.be/hoViWRAhCBE)
- [VoronoiFVM.jl](https://github.com/j-fu/VoronoiFVM.jl) : Solution of nonlinear multiphysics partial differential equation systems using the Voronoi finite volume method.

## Stochastic algorithms

[Wikipedia: Stochastic simulation](https://en.wikipedia.org/wiki/Stochastic_simulation) algorithms (SSA) are also included in the `DifferentialEquations` ecosystem.

- [BioSimulator.jl](https://github.com/alanderos91/BioSimulator.jl) : A stochastic simulation framework in Julia.
- [Gillespie.jl](https://github.com/sdwfrost/Gillespie.jl) : Stochastic Gillespie-type simulations using Julia.
- [StochasticDiffEq.jl](https://github.com/SciML/StochasticDiffEq.jl) : Solvers for stochastic differential equations in the SciML ecosystem.

## Agent-based models

[Wikipedia: Agent-based model](https://en.wikipedia.org/wiki/Agent-based_model)

- [Agents.jl](https://github.com/JuliaDynamics/Agents.jl) : Agent-based modeling framework in Julia.
- [DynamicalBilliards.jl](https://github.com/JuliaDynamics/DynamicalBilliards.jl) : An easy-to-use, modular and extendable Julia package for Dynamical Billiard systems in two dimensions.
- [Vahana.jl](https://github.com/s-fuerst/Vahana.jl) : A framework (not only) for large-scale agent-based models.

## Network modeling

- [Petri.jl](https://github.com/mehalter/Petri.jl) : Petri net modeling framework.
- [NetworkDynamics.jl](https://github.com/PIK-ICoNe/NetworkDynamics.jl) : A package for working with dynamical systems on complex networks. NetworkDynamics.jl provides an interface between `Graphs.jl` and `DifferentialEquations.jl`.

## Utilities

- [DrWatson.jl](https://github.com/JuliaDynamics/DrWatson.jl) : dealing with simulations and simulation parameters.
- [SciMLBenchmarks.jl](https://github.com/SciML/SciMLBenchmarks.jl) : Benchmarks for scientific machine learning (SciML) software and differential equation solvers.
- [SimulationLogger.jl](https://github.com/JinraeKim/SimulationLogger.jl) : providing convenient logging tools for `DifferentialEquations.jl`.
- [SimulationLogs.jl](https://github.com/jonniedie/SimulationLogs.jl) : Signal logging and scoping for `DifferentialEquations.jl` simulations.

## Others

- [Mads.jl](https://github.com/madsjulia/Mads.jl) : [MADS](https://mads.gitlab.io/), Model Analysis & Decision Support.

## Resources

- [Workshop for `ModelingToolkit.jl`](https://youtu.be/HEVOgSLBzWA) : A Youtube video for JuliaCon 2021.
- [SciMLTutorials.jl](https://github.com/SciML/SciMLTutorials.jl) : Tutorials for doing scientific machine learning (SciML) and high-performance differential equation solving with open source software.
