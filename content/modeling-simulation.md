---
title: Modeling and Simulation
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:48:58
---

> General modeling and simulation packages in Julia.

## Organizations

- [ModiaSim](https://github.com/ModiaSim)
- [SciML](https://github.com/SciML)
- [Julia Dynamics](https://juliadynamics.github.io/JuliaDynamics/)

## See also

- [[algorithm-data-structure]]
- [[linear-algebra#Array Data Structures]]

## Resources

- [SciMLTutorials.jl](https://github.com/SciML/SciMLTutorials.jl) : Tutorials for doing scientific machine learning (SciML) and high-performance differential equation solving with open source software.
- [Workshop for `ModelingToolkit.jl`](https://youtu.be/HEVOgSLBzWA) : A Youtube video for JuliaCon 2021.

## File IO

- [CellMLToolkit.jl](https://github.com/SciML/CellMLToolkit.jl) : a Julia library that connects `CellML` models to the Scientific Julia ecosystem.
- [FMIExchange.jl](https://github.com/Electa-Git/FMIExchange.jl) : load Model Exchange Functional Mock-up Units (FMUs) and simulate them using the `DifferentialEquations.jl` package.
- [ReactionNetworkImporters.jl](https://github.com/SciML/ReactionNetworkImporters.jl) : Loading BioNetGen `.net` file.
- [SBML.jl](https://github.com/LCSB-BioCore/SBML.jl) : Julia interface to the Systems Biology Markup Language (SBML) library.
- [SBMLToolkit.jl](https://github.com/SciML/SBMLToolkit.jl) : importing models specified in the Systems Biology Markup Language (SBML) into the Julia SciML ecosystem.

## Symbolic Computation

[Wikipedia: Symbolic Computation](https://en.wikipedia.org/wiki/Symbolic_computation)

- [CommonSubexpressions.jl](https://github.com/rdeits/CommonSubexpressions.jl) : Naïve combined subexpression elimination in Julia.
- [Reduce.jl](https://github.com/chakravala/Reduce.jl) : Symbolic parser generator for Julia language expressions using REDUCE algebra term rewriter.
- [Symata.jl](https://github.com/jlapeyre/Symata.jl) : language for symbolic mathematics.
- [SymbolicRegression.jl](https://github.com/MilesCranmer/SymbolicRegression.jl) : Distributed High-Performance symbolic regression in Julia.
- [Symbolics.jl](https://github.com/JuliaSymbolics/Symbolics.jl) : A fast and modern CAS for a fast and modern language.
- [SymEngine.jl](https://github.com/symengine/SymEngine.jl) : Julia wrappers of https://github.com/symengine/symengine.
- [SymPy.jl](https://github.com/JuliaPy/SymPy.jl) : Julia interface to [SymPy](https://www.sympy.org/) via `PyCall.jl`.
- [SymPyPythonCall.jl](https://github.com/jverzani/SymPyPythonCall.jl) : Julia interface to [SymPy](https://www.sympy.org/) via `PythonCall.jl`.

## Differential equations

[Wikipedia: Differential equations](https://en.wikipedia.org/wiki/Differential_equation)

**Frameworks**
- [CadCAD.jl](https://github.com/cadCAD-org/CadCAD.jl) : Complex Adaptive Dynamics Computer Aided Design (CadCAD) is a language for encoding Generalized Dynamical Systems (GDS) as computer programs. The Julia implementation is based on its [Python counterpart](https://github.com/cadCAD-org/cadcad-ri).
- [Catalyst.jl](https://github.com/SciML/Catalyst.jl) : Domain-specific language (DSL) for chemical reaction networks.
- [ConcurrentSim.jl](https://github.com/JuliaDynamics/ConcurrentSim.jl) : A discrete event process oriented simulation framework written in Julia.
- [DifferentialEquations.jl](https://github.com/SciML/DifferentialEquations.jl) : High-performance solvers of differential equations.
- [Dyad.jl](https://juliahub.com/products/dyad) : Modern Modeling and Simulation powered by Machine Learning (formerly JuliaSim). [Julia forum thread](https://discourse.julialang.org/t/ann-dyad-a-new-language-to-make-hardware-engineering-as-fast-as-software/129996)
- [ModelingToolkit.jl](https://github.com/SciML/ModelingToolkit.jl) : A modeling framework for automatically parallelized scientific machine learning (SciML) in Julia.
- [Modia.jl](https://github.com/ModiaSim/Modia.jl) : Modia is a Julia package for modeling and simulation of multidomain engineering systems described by differential equations, algebraic equations, and (space-discretized) partial differential equations.

**Algorithms**
- [DAECompiler.jl](https://github.com/CedarEDA/DAECompiler.jl) : the core compiler engine of the [Cedar EDA](https://github.com/CedarEDA) platform. It provides a domain-agnostic framework for high-performance simulation of Differential Algebraic Equations (DAEs). [JuliaCon 2024 video](https://youtu.be/D5U-4Fplqvg)
- [DataDrivenDiffEq.jl](https://github.com/SciML/DataDrivenDiffEq.jl) : Data driven modeling and automated discovery of dynamical systems.
- [FdeSolver.jl](https://github.com/JuliaTurkuDataScience/FdeSolver.jl) : A Julia package for the numerical solution of fractional differential equations (FDEs) as well as systems of equations.
- [HarmonicBalance.jl](https://github.com/NonlinearOscillations/HarmonicBalance.jl) : solving nonlinear differential equations using the harmonic balance method.
- [ProbNumDiffEq.jl](https://github.com/nathanaelbosch/ProbNumDiffEq.jl) : Probabilistic Numerical Differential Equation solvers via Bayesian filtering and smoothing. [JuliaCon 2024 video](https://youtu.be/iH_GQiOaeUo)
- [QuDiffEq.jl](https://github.com/QuantumBFS/QuDiffEq.jl) : Quantum Algorithms for solving differential equations
- [RiemannHilbert.jl](https://github.com/JuliaHolomorphic/RiemannHilbert.jl) : A Julia package for solving a Riemann–Hilbert problem, a certain type of boundary value problem.
- [SingularIntegralEquations.jl](https://github.com/JuliaApproximation/SingularIntegralEquations.jl) : An experimental Julia package for solving singular integral equations.
- [Sundials.jl](https://github.com/SciML/Sundials.jl) : A Julia package that interfaces to the [Sundials](https://computing.llnl.gov/projects/sundials) library and includes a nonlinear solver (KINSOL), ODE's (CVODE), and DAE's (IDA).

**Utilities**
- [ModelingToolkitDesigner.jl](https://github.com/bradcarman/ModelingToolkitDesigner.jl) : A helper tool for visualizing and editing a `ModelingToolkit.jl` system connections.
- [ModelingToolkitSampledData.jl](https://github.com/JuliaComputing/ModelingToolkitSampledData.jl) : A standard library with discrete-time components for ModelingToolkit. It requires `JuliaSimCompiler.jl`, a proprietary product. [JuliaCon 2024 video](https://youtu.be/wL-jYQ_O9Nc)
- [Pathogen.jl](https://github.com/jangevaare/Pathogen.jl) : Utilities to simulate and perform inference of disease dynamics.
- [SciMLSensitivity.jl](https://github.com/SciML/SciMLSensitivity.jl) : A component of the DiffEq ecosystem for sensitivity analysis.
- [Surrogates.jl](https://github.com/SciML/Surrogates.jl) : Surrogate modeling and optimization.

### Partial Differential Equations

- [Wikipedia: Finite difference method](https://en.wikipedia.org/wiki/Finite_difference_method)
- [Wikipedia: Finite element method](https://en.wikipedia.org/wiki/Finite_element_method)
- [Wikipedia: Finite volume method](https://en.wikipedia.org/wiki/Finite_volume_method)
- https://github.com/PtFEM/PtFEM.jl : Book "[Programming the Finite Element Method](https://www.wiley.com/en-us/Programming+the+Finite+Element+Method,+5th+Edition-p-9781119973348)" by I M Smith, D V Griffiths and L Margetts.

---

**Frameworks**
[ModelingToolkit.jl](https://github.com/SciML/ModelingToolkit.jl) supports finite difference method via `MethodOfLines.jl`.

- [Gridap.jl](https://github.com/gridap/Gridap.jl) : Grid-based approximation of PDEs with finite element (FE) discretization.
- [JuliaFEM.jl](https://github.com/JuliaFEM/JuliaFEM.jl) : Finite Element method solver.
- [PETSc.jl](https://github.com/JuliaParallel/PETSc.jl) : A Julia interface for [PETSc](https://petsc.org/).
- [Trixi.jl](https://github.com/trixi-framework/Trixi.jl) : Adaptive high-order numerical simulations of hyperbolic PDEs in Julia.  [JuliaCon 2021 video](https://youtu.be/hoViWRAhCBE)
- [VoronoiFVM.jl](https://github.com/j-fu/VoronoiFVM.jl) : Solution of nonlinear multiphysics partial differential equation systems using the Voronoi finite volume method.

**Utilities**
- [ClimaCore.jl](https://github.com/CliMA/ClimaCore.jl) : Tools for building spatial discretization. [JuliaCon 2021 video](https://youtu.be/4bQvF3rGB84)
- [FEMBasis.jl](https://github.com/JuliaFEM/FEMBasis.jl) : Package contains interpolation routines for standard finite element function spaces.
- [FinEtools.jl](https://github.com/PetrKryslUCSD/FinEtools.jl) : `FinEtools` is a package for basic operations on finite element meshes: Construction, modification, selection, and evaluation of quantities defined on a mesh.
- [FourierFlows.jl](https://github.com/FourierFlows/FourierFlows.jl) : Tools for building fast, hackable, pseudospectral partial differential equation solvers on periodic domains.
- [Heptapus.jl](https://github.com/lcw/Heptapus.jl) : The roofline function is a translation of the [roofline code](https://github.com/paranumal/libparanumal/), Accelerated finite element flow solvers.
- [Krylov.jl](https://github.com/JuliaSmoothOptimizers/Krylov.jl) : A Julia Basket of Hand-Picked Krylov Methods.
- [LinearAlgebraicRepresentation.jl](https://github.com/cvdlab/LinearAlgebraicRepresentation.jl) : Official Julia implementation of [LAR](https://linkinghub.elsevier.com/retrieve/pii/S001044851300184X), the Linear Algebraic Representation for Solid Modeling. LAR is a general representation scheme for geometric and topological modeling.
- [MethodOfLines.jl](https://github.com/SciML/MethodOfLines.jl) : Automatic Finite Difference PDE solving with Julia.
- [ParallelStencil.jl](https://github.com/omlins/ParallelStencil.jl) : writing high-level code for parallel high-performance stencil computations that can be deployed on both GPUs and CPUs.

#### Computational Fluid Dynamics (CFD)

- [Wikipedia: Fluid Dynamics](https://en.wikipedia.org/wiki/Fluid_dynamics)
- Blog post about [CFD tutorial in julia](https://www.juliabloggers.com/cfd-tutorial-in-julia/)

---

- [WaterLily.jl](https://github.com/weymouth/WaterLily.jl) : a simple and fast fluid simulator written in pure Julia.

### Steady state solutions

- [HomotopyContinuation.jl](https://github.com/JuliaHomotopyContinuation/HomotopyContinuation.jl): solving systems of polynomial equations by numerical homotopy continuation.
- [NonlinearSolve.jl](https://github.com/SciML/NonlinearSolve.jl) : Fast implementations of root finding algorithms in Julia using the SciML common interface.
- [SteadyStateDiffEq.jl](https://github.com/SciML/SteadyStateDiffEq.jl): Solvers for steady states in differential equations.

### Universal Differential Equations

> When differential equations meet neural networks

- [DiffEqFlux.jl](https://github.com/SciML/DiffEqFlux.jl) : Combining DifferentialEquations.jl and Flux.jl as its building blocks to support research in Scientific Machine Learning, specifically neural differential equations and universal differential equations.
- [NeuralOperators.jl](https://github.com/SciML/NeuralOperators.jl) : Learning the solution operator for partial differential equations in pure Julia.
- [NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) : Physics-Informed Neural Networks (PINN) and Deep BSDE Solvers of Differential Equations.
- [UniversalDiffEq.jl](https://github.com/Jack-H-Buckner/UniversalDiffEq.jl) : builds Universal Differential Equations (UDEs) to learn nonlinear dynamics from time series data.

## Stochastic algorithms

[Wikipedia: Stochastic simulation](https://en.wikipedia.org/wiki/Stochastic_simulation) algorithms (SSA) are also included in the `DifferentialEquations` ecosystem.

- [BioSimulator.jl](https://github.com/alanderos91/BioSimulator.jl) : A stochastic simulation framework in Julia.
- [CompetingClocks.jl](https://github.com/adolgert/CompetingClocks.jl) : samples continuous-time probability distributions with time-varying hazard rates. It is a sampler for stochastic simulation in continuous time.
- [Gillespie.jl](https://github.com/sdwfrost/Gillespie.jl) : Stochastic Gillespie-type simulations using Julia.
- [JumpProcesses.jl](https://github.com/SciML/JumpProcesses.jl): Build and simulate jump equations like Gillespie simulations and jump diffusions with constant and state-dependent rates and mix with differential equations.
- [StochasticDiffEq.jl](https://github.com/SciML/StochasticDiffEq.jl) : Solvers for stochastic differential equations in the SciML ecosystem.

## Difference Equations

- [DynamicalSystems.jl](https://github.com/JuliaDynamics/DynamicalSystems.jl) : Julia software library for the exploration of chaos and nonlinear dynamics.

## Agent-based models

[Wikipedia: Agent-based model](https://en.wikipedia.org/wiki/Agent-based_model)

- [Agents.jl](https://github.com/JuliaDynamics/Agents.jl) : Agent-based modeling framework in Julia.
- [DynamicalBilliards.jl](https://github.com/JuliaDynamics/DynamicalBilliards.jl) : An easy-to-use, modular and extendable Julia package for Dynamical Billiard systems in two dimensions.

## Network modeling

- [ACME.jl](https://github.com/HSU-ANT/ACME.jl) : Analog Circuit Modeling and Emulation for Julia.
- [NetworkDynamics.jl](https://github.com/PIK-ICoNe/NetworkDynamics.jl) : A package for working with dynamical systems on complex network, providing an interface between `Graphs.jl` and `DifferentialEquations.jl`.
- [Petri.jl](https://github.com/mehalter/Petri.jl) : Petri net modeling framework.
- [PowerDynamics.jl](https://github.com/JuliaEnergy/PowerDynamics.jl): Package for dynamical modeling of power grids, based on `NetworkDynamics.jl`.
- [PowerSimulations.jl](https://github.com/NREL-SIIP/PowerSimulations.jl) : Julia for optimization simulation and modeling of PowerSystems.
- [PowerSystems.jl](https://github.com/NREL-SIIP/PowerSystems.jl) : Data structures in Julia to enable power systems analysis.
- [TrafficAssignment.jl](https://github.com/gdalle/TrafficAssignment.jl): Julia package for finding traffic user equilibrium flow.

## Utilities

- [BifurcationKit.jl](https://github.com/bifurcationkit/BifurcationKit.jl) : Bifurcation Analysis in Julia.
- [DataInterpolations.jl](https://github.com/SciML/DataInterpolations.jl) : Data interpolation and smoothing functions.
- [DrWatson.jl](https://github.com/JuliaDynamics/DrWatson.jl) : dealing with simulations and simulation parameters.
- [ProgressLogging.jl](https://github.com/JuliaLogging/ProgressLogging.jl) : a package for defining progress logs, supported by REPL ([TerminalLoggers.jl](https://github.com/JuliaLogging/TerminalLoggers.jl)), VS Code, Pluto.
- [SciMLBenchmarks.jl](https://github.com/SciML/SciMLBenchmarks.jl) : Benchmarks for scientific machine learning (SciML) software and differential equation solvers. [Benchmark results](https://benchmarks.sciml.ai/stable/)
- [SimulationLogger.jl](https://github.com/JinraeKim/SimulationLogger.jl) : providing convenient logging tools for `DifferentialEquations.jl`.
- [SimulationLogs.jl](https://github.com/jonniedie/SimulationLogs.jl) : Signal logging and scoping for `DifferentialEquations.jl` simulations.

### Parameter estimation

- [DiffEqParamEstim.jl](https://github.com/SciML/DiffEqParamEstim.jl) : a package for simplified parameter estimation with `DifferentialEquations.jl`.
- [PEtab.jl](https://github.com/sebapersson/PEtab.jl): Create parameter estimation problems for ODE models
- [PhysicsInformedRegression.jl](https://github.com/MarcusGalea/PhysicsInformedRegression.jl) : solving inverse problems (parameter estimation) using physics informed regression. It requires well-defined derivatives. [JuliaCon 2024 video](https://youtu.be/ohmiQv5WemQ)
- [SciMLSensitivity.](https://github.com/SciML/SciMLSensitivity.jl) : sensitivity analysis and parameter estimation.

## Others

- [ControlSystems.jl](https://github.com/JuliaControl/ControlSystems.jl) : A Control Systems Toolbox for Julia.
- [FMI.jl](https://github.com/ThummeTo/FMI.jl) : integrating the [Functional Mock-Up Interface](https://fmi-standard.org/).
- [Mads.jl](https://github.com/madsjulia/Mads.jl) : [MADS](https://mads.gitlab.io/), Model Analysis & Decision Support.
- [OMJulia.jl](https://github.com/OpenModelica/OMJulia.jl) : Julia scripting [OpenModelica](https://www.openmodelica.org/) interface.
