---
title: Modeling and simulation
---

General modeling and simulation packages in Julia.

## Organizations

- [ModiaSim](https://github.com/ModiaSim)
- [SciML](https://github.com/SciML)
- [Julia Dynamics](https://juliadynamics.github.io/JuliaDynamics/)

## Resources

- [Workshop for `ModelingToolkit.jl`](https://youtu.be/HEVOgSLBzWA) : A Youtube video for JuliaCon 2021.
- https://github.com/SciML/SciMLTutorials.jl : Tutorials for doing scientific machine learning (SciML) and high-performance differential equation solving with open source software.

## Loading model files

- https://github.com/LCSB-BioCore/SBML.jl : Julia interface to the Systems Biology Markup Language (SBML) library.
- https://github.com/SciML/CellMLToolkit.jl : a Julia library that connects `CellML` models to the Scientific Julia ecosystem.
- https://github.com/SciML/ReactionNetworkImporters.jl : Loading BioNetGen `.net` file.
- https://github.com/SciML/SBMLToolkit.jl : importing models specified in the Systems Biology Markup Language (SBML) into the Julia SciML ecosystem.
- https://github.com/Electa-Git/FMIExchange.jl : load Model Exchange Functional Mock-up Units (FMUs) and simulate them using the `DifferentialEquations.jl` package.

## Symbolic Computation

[Wikipedia: Symbolic Computation](https://en.wikipedia.org/wiki/Symbolic_computation)

- https://github.com/JuliaSymbolics/Symbolics.jl : A fast and modern CAS for a fast and modern language.

- https://github.com/chakravala/Reduce.jl : Symbolic parser generator for Julia language expressions using REDUCE algebra term rewriter.
- https://github.com/jlapeyre/Symata.jl : language for symbolic mathematics.
- https://github.com/JuliaPy/SymPy.jl : Julia interface to [SymPy](https://www.sympy.org/) via `PyCall.jl`.
- https://github.com/jverzani/SymPyPythonCall.jl : Julia interface to [SymPy](https://www.sympy.org/) via `PythonCall.jl`.
- https://github.com/MilesCranmer/SymbolicRegression.jl : Distributed High-Performance symbolic regression in Julia.
- https://github.com/symengine/SymEngine.jl : Julia wrappers of https://github.com/symengine/symengine.

## Data structures

See also [[data-structures]].

- https://github.com/jonniedie/ComponentArrays.jl : Arrays with arbitrarily nested named components.
- https://github.com/SciML/LabelledArrays.jl : Arrays with a label for each element.
- https://github.com/SciML/RecursiveArrayTools.jl : Tools for easily handling nestings array objects like arrays of arrays.

## Differential equations

[Wikipedia: Differential equations](https://en.wikipedia.org/wiki/Differential_equation)

- https://github.com/bradcarman/ModelingToolkitDesigner.jl : A helper tool for visualizing and editing a `ModelingToolkit.jl` system connections.
- https://github.com/cadCAD-org/CadCAD.jl : Complex Adaptive Dynamics Computer Aided Design (CadCAD) is a language for encoding Generalized Dynamical Systems (GDS) as computer programs. The Julia implementation is based on its [Python counterpart](https://github.com/cadCAD-org/cadcad-ri).
- https://github.com/CedarEDA/DAECompiler.jl : the core compiler engine of the [Cedar EDA](https://github.com/CedarEDA) platform. It provides a domain-agnostic framework for high-performance simulation of Differential Algebraic Equations (DAEs). [JuliaCon 2024 video](https://youtu.be/D5U-4Fplqvg)
- https://github.com/jangevaare/Pathogen.jl : Utilities to simulate and perform inference of disease dynamics.
- https://github.com/JuliaApproximation/SingularIntegralEquations.jl : An experimental Julia package for solving singular integral equations.
- https://github.com/JuliaComputing/ModelingToolkitSampledData.jl : A standard library with discrete-time components for ModelingToolkit. It requires `JuliaSimCompiler.jl`, a proprietary product. [JuliaCon 2024 video](https://youtu.be/wL-jYQ_O9Nc)
- https://github.com/JuliaDynamics/ConcurrentSim.jl : A discrete event process oriented simulation framework written in Julia.
- https://github.com/JuliaHolomorphic/RiemannHilbert.jl : A Julia package for solving a Riemann–Hilbert problem, a certain type of boundary value problem.
- https://github.com/JuliaTurkuDataScience/FdeSolver.jl : A Julia package for the numerical solution of fractional differential equations (FDEs) as well as systems of equations.
- https://github.com/ModiaSim/Modia.jl : Modia is a Julia package for modeling and simulation of multidomain engineering systems described by differential equations, algebraic equations, and (space-discretized) partial differential equations.
- https://github.com/nathanaelbosch/ProbNumDiffEq.jl : Probabilistic Numerical Differential Equation solvers via Bayesian filtering and smoothing. [JuliaCon 2024 video](https://youtu.be/iH_GQiOaeUo)
- https://github.com/NonlinearOscillations/HarmonicBalance.jl : solving nonlinear differential equations using the harmonic balance method.
- https://github.com/QuantumBFS/QuDiffEq.jl : Quantum Algorithms for solving differential equations
- https://github.com/SciML/Catalyst.jl : Domain-specific language (DSL) for chemical reaction networks.
- https://github.com/SciML/DataDrivenDiffEq.jl : Data driven modeling and automated discovery of dynamical systems.
- https://github.com/SciML/DifferentialEquations.jl : High-performance solvers of differential equations.
- https://github.com/SciML/ModelingToolkit.jl : A modeling framework for automatically parallelized scientific machine learning (SciML) in Julia.
- https://github.com/SciML/SciMLSensitivity.jl : A component of the DiffEq ecosystem for sensitivity analysis.
- https://github.com/SciML/Sundials.jl : A Julia package that interfaces to the [Sundials](https://computing.llnl.gov/projects/sundials) library and includes a nonlinear solver (KINSOL), ODE's (CVODE), and DAE's (IDA).
- [Dyad.jl](https://juliahub.com/products/dyad) : Modern Modeling and Simulation powered by Machine Learning (formerly JuliaSim). [Julia forum thread](https://discourse.julialang.org/t/ann-dyad-a-new-language-to-make-hardware-engineering-as-fast-as-software/129996)


### Partial Differential Equations

- [Wikipedia: Finite difference method](https://en.wikipedia.org/wiki/Finite_difference_method)
- [Wikipedia: Finite element method](https://en.wikipedia.org/wiki/Finite_element_method)
- [Wikipedia: Finite volume method](https://en.wikipedia.org/wiki/Finite_volume_method)

- https://github.com/PtFEM/PtFEM.jl : Book "[Programming the Finite Element Method](https://www.wiley.com/en-us/Programming+the+Finite+Element+Method,+5th+Edition-p-9781119973348)" by I M Smith, D V Griffiths and L Margetts.

---

- https://github.com/CliMA/ClimaCore.jl : Tools for building spatial discretization. [JuliaCon 2021 video](https://youtu.be/4bQvF3rGB84)
- https://github.com/cvdlab/LinearAlgebraicRepresentation.jl : Official Julia implementation of [LAR](https://linkinghub.elsevier.com/retrieve/pii/S001044851300184X), the Linear Algebraic Representation for Solid Modeling. LAR is a general representation scheme for geometric and topological modeling.
- https://github.com/FourierFlows/FourierFlows.jl : Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains.
- https://github.com/gridap/Gridap.jl : Grid-based approximation of PDEs with finite element (FE) discretization.
- https://github.com/j-fu/VoronoiFVM.jl : Solution of nonlinear multiphysics partial differential equation systems using the Voronoi finite volume method.
- https://github.com/JuliaFEM/FEMBasis.jl : Package contains interpolation routines for standard finite element function spaces.
- https://github.com/JuliaFEM/JuliaFEM.jl : Finite Element method solver.
- https://github.com/JuliaParallel/PETSc.jl : A Julia interface for [PETSc](https://petsc.org/).
- https://github.com/JuliaSmoothOptimizers/Krylov.jl : A Julia Basket of Hand-Picked Krylov Methods.
- https://github.com/lcw/Heptapus.jl : The roofline function is a translation of the [roofline code](https://github.com/paranumal/libparanumal/), Accelerated finite element flow solvers.
- https://github.com/omlins/ParallelStencil.jl : writing high-level code for parallel high-performance stencil computations that can be deployed on both GPUs and CPUs.
- https://github.com/PetrKryslUCSD/FinEtools.jl : `FinEtools` is a package for basic operations on finite element meshes: Construction, modification, selection, and evaluation of quantities defined on a mesh.
- https://github.com/SciML/MethodOfLines.jl : Automatic Finite Difference PDE solving with Julia.
- https://github.com/trixi-framework/Trixi.jl : Adaptive high-order numerical simulations of hyperbolic PDEs in Julia.  [JuliaCon 2021 video](https://youtu.be/hoViWRAhCBE)

### Universal Differential Equations

- https://github.com/Jack-H-Buckner/UniversalDiffEq.jl : builds Universal Differential Equations (UDEs) to learn nonlinear dynamics from time series data.
- https://github.com/SciML/DiffEqFlux.jl : Combining DifferentialEquations.jl and Flux.jl as its building blocks to support research in Scientific Machine Learning, specifically neural differential equations and universal differential equations.
- https://github.com/SciML/NeuralOperators.jl : Learning the solution operator for partial differential equations in pure Julia.
- https://github.com/SciML/NeuralPDE.jl : Physics-Informed Neural Networks (PINN) and Deep BSDE Solvers of Differential Equations.

## Stochastic algorithms

[Wikipedia: Stochastic simulation](https://en.wikipedia.org/wiki/Stochastic_simulation) algorithms (SSA) are also included in the `DifferentialEquations` ecosystem.

- https://github.com/alanderos91/BioSimulator.jl : A stochastic simulation framework in Julia.
- https://github.com/SciML/StochasticDiffEq.jl : Solvers for stochastic differential equations in the SciML ecosystem.
- https://github.com/sdwfrost/Gillespie.jl : Stochastic Gillespie-type simulations using Julia.

## Difference Equations

- https://github.com/JuliaDynamics/DynamicalSystems.jl : Julia software library for the exploration of chaos and nonlinear dynamics.

## Agent-based models

[Wikipedia: Agent-based model](https://en.wikipedia.org/wiki/Agent-based_model)

- https://github.com/JuliaDynamics/Agents.jl : Agent-based modeling framework in Julia.
- https://github.com/JuliaDynamics/DynamicalBilliards.jl : An easy-to-use, modular and extendable Julia package for Dynamical Billiard systems in two dimensions.
- https://github.com/s-fuerst/Vahana.jl : A framework (not only) for large-scale agent-based models.

## Network modeling

- https://github.com/mehalter/Petri.jl : Petri net modeling framework.
- https://github.com/PIK-ICoNe/NetworkDynamics.jl : A package for working with dynamical systems on complex network, providing an interface between `Graphs.jl` and `DifferentialEquations.jl`.

## Utilities

- https://github.com/bifurcationkit/BifurcationKit.jl : Bifurcation Analysis in Julia.
- https://github.com/JinraeKim/SimulationLogger.jl : providing convenient logging tools for `DifferentialEquations.jl`.
- https://github.com/jonniedie/SimulationLogs.jl : Signal logging and scoping for `DifferentialEquations.jl` simulations.
- https://github.com/JuliaDynamics/DrWatson.jl : dealing with simulations and simulation parameters.
- https://github.com/SciML/DataInterpolations.jl : Data interpolation and smoothing functions.
- https://github.com/SciML/SciMLBenchmarks.jl : Benchmarks for scientific machine learning (SciML) software and differential equation solvers. [Benchmark results](https://benchmarks.sciml.ai/stable/)

### Parameter estimation

- https://github.com/MarcusGalea/PhysicsInformedRegression.jl : solving inverse problems (parameter estimation) using physics informed regression. It requires well-defined derivatives. [JuliaCon 2024 video](https://youtu.be/ohmiQv5WemQ)
- https://github.com/SciML/DiffEqParamEstim.jl : a package for simplified parameter estimation with `DifferentialEquations.jl`.
- https://github.com/SciML/SciMLSensitivity.jl : sensitivity analysis and parameter estimation.

## Others

- https://github.com/madsjulia/Mads.jl : [MADS](https://mads.gitlab.io/), Model Analysis & Decision Support.
- https://github.com/ThummeTo/FMI.jl : integrating the [Functional Mock-Up Interface](https://fmi-standard.org/).
- https://github.com/OpenModelica/OMJulia.jl : Julia scripting [OpenModelica](https://www.openmodelica.org/) interface.
