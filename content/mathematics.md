---
title: Mathematics
Created: 2025-11-16, 17:15:16
Modified: 2025-11-22, 15:44:01
---
# Mathematics

- [JuliaMath](https://github.com/JuliaMath) organization
- [JuliaApproximation](https://github.com/JuliaApproximation) organization

## See also

- [[modeling-simulation#Symbolic Computation|Symbolic computation]]
- [[linear-algebra|Linear Algebra]]
- [[dsp|Digital signal processing]]
## General Mathematics packages

- [Dualization.jl](https://github.com/jump-dev/Dualization.jl) : Automatic dualization feature for MathOptInterface.jl conic optimization problems.
- [FastPow.jl](https://github.com/JuliaMath/FastPow.jl) : `@fastpow` speeds up the computation of integer powers in any Julia expression by transforming them into optimal sequences of multiplications, with a slight sacrifice in accuracy.
- [GSL.jl](https://github.com/JuliaMath/GSL.jl) : Julia interface to the GNU Scientific Library - [GSL](https://www.gnu.org/software/gsl/doc/html/index.html).
- [Manifolds.jl](https://github.com/JuliaManifolds/Manifolds.jl) : a unified interface to define and use manifolds as well as a library of manifolds to use for your projects.
- [Tau.jl](https://github.com/JuliaMath/Tau.jl) : A simple module providing definition of the Tau constant = 2pi.

## Numeric data types

- [BitIntegers.jl](https://github.com/rfourquet/BitIntegers.jl) : This package implements fixed-width integer types similar to standard built-in ones like `Int` or `UInt128`.
- [CustomUnitRanges.jl](https://github.com/JuliaArrays/CustomUnitRanges.jl) : This Julia package supports the creation of array types with "unconventional" indices.
- [DualNumbers.jl](https://github.com/JuliaDiff/DualNumbers.jl): Julia package for representing dual numbers for differentiation.
- [FixedPointNumbers.jl](https://github.com/JuliaMath/FixedPointNumbers.jl) : This library exports [fixed-point number](http://en.wikipedia.org/wiki/Fixed-point_arithmetic) types.
- [Infinity.jl](https://github.com/cjdoris/Infinity.jl) : Representation of infinity in Julia.
- [Measures.jl](https://github.com/JuliaGraphics/Measures.jl) : Unified measure and coordinates types.
- [Quaternions.jl](https://github.com/JuliaGeometry/Quaternions.jl) : Quaternions, octonions and dual-quaternions for 3D rotational orientation.
- [Ratios.jl](https://github.com/timholy/Ratios.jl) : Faster Rational-like types for Julia at the risk of greater risk of overflow.

### Units

- [DynamicQuantities.jl](https://github.com/SymbolicML/DynamicQuantities.jl) : Lightweight and fast physical quantities in Julia to supplement `Unitful.jl`.
- [Unitful.jl](https://github.com/PainterQubits/Unitful.jl) : A Julia package for physical units.
- [UnitSystems.jl](https://github.com/chakravala/UnitSystems.jl): Physical unit systems (Metric, English, Natural, Planck, etc...). See also [Similitude.jl](https://github.com/chakravala/Similitude.jl): Dimensions and Quantities for `UnitSystems.jl`.

### Floating-point numbers

- [ArbNumerics.jl](https://github.com/JeffreySarnoff/ArbNumerics.jl) : extended precision math, accurate and performant
- [BFloat16s.jl](https://github.com/JuliaMath/BFloat16s.jl) : This package defines the [BFloat16 data type](https://en.wikipedia.org/wiki/Bfloat16_floating-point_format). The only currently available hardware implementation of this datatype are Google's [Cloud TPUs](https://en.wikipedia.org/wiki/Tensor_processing_unit).
- [DecFP.jl](https://github.com/JuliaMath/DecFP.jl) : The package provides 32-bit, 64-bit, and 128-bit binary-encoded decimal floating-point types following the IEEE 754-2008, implemented as a wrapper around the (BSD-licensed) [Intel Decimal Floating-Point Math Library](https://www.intel.com/content/www/us/en/developer/articles/tool/intel-decimal-floating-point-math-library.html).
- [Decimals.jl](https://github.com/JuliaMath/Decimals.jl) : Pure Julia decimal arithmetic library.
- [DoubleFloats.jl](https://github.com/JuliaMath/DoubleFloats.jl) : Numbers with 85 accurate bits.
- [LogarithmicNumbers.jl](https://github.com/cjdoris/LogarithmicNumbers.jl) : A [logarithmic number system](https://en.wikipedia.org/wiki/Logarithmic_number_system) for Julia. Provides the signed `ULogarithmic` and unsigned `Logarithmic` types for representing real numbers on a logarithmic scale.
### Intervals

[Julia intervals](https://juliaintervals.github.io/)

- [IntervalArithmetic.jl](https://github.com/juliaintervals/IntervalArithmetic.jl) : Rigorous floating-point calculations using interval arithmetic in Julia.
- [Measurements.jl](https://github.com/JuliaPhysics/Measurements.jl) : Error propagation calculator and library. It supports real and complex numbers with uncertainty, arbitrary precision calculations, and operations with arrays.
- [MonteCarloMeasurements.jl](https://github.com/baggepinnen/MonteCarloMeasurements.jl) : Error propagation using Monte-Carlo simulation. Similar to `Measurements.jl`, but more accurate for highly nonlinear functions at the expense of longer execution time.

## Computer Arithmetic

- [Wikipedia: Computer Arithmetic](https://en.wikipedia.org/wiki/Category:Computer_arithmetic)
- [ent](https://github.com/williamstein/ent) : Primes, Congruences, and Secrets.

### Floating Point numbers

[Wikipedia: Floating Point](https://en.wikipedia.org/wiki/Category:Floating_point)

- [ErrorfreeArithmetic.jl](https://github.com/JeffreySarnoff/ErrorfreeArithmetic.jl) : Error-free transformations for arithmetic ops.
- [FastRounding.j](https://github.com/JeffreySarnoff/FastRounding.jl) : Faster directed rounding for inline arithmetic.

## Algebra

[adeles](https://github.com/williamstein/adeles) algebraic number theory

---

- [Hecke.jl](https://github.com/thofma/Hecke.jl) : A package for algebraic number theory that works on top of `Nemo.jl` by Tommy Hofmann and Claus Fieker.
- [Mods.jl](https://github.com/scheinerman/Mods.jl) : Easy modular arithmetic for Julia.
- [Nemo.jl](https://github.com/Nemocas/Nemo.jl) : A computer algebra package for the Julia programming language.
- [OEIS.jl](https://github.com/MurrayT/OEIS.jl) : A basic wrapper to allow access to [OEIS](http://oeis.org/) integer sequences from within Julia.
- [SemiringAlgebra.jl](https://github.com/JuliaComputing/SemiringAlgebra.jl) : [Semiring Algebra](https://dspace.mit.edu/handle/1721.1/115964). A linear algebraic approach to graph algorithms that exploits the sparse adjacency matrix representation of graphs can provide a variety of benefits.
### Boolean Algebra

[Boolean Algebra](https://en.wikipedia.org/wiki/Category:Boolean_algebra)

- [ShowSet.jl](https://github.com/scheinerman/ShowSet.jl) : Nicer output for Set and IntSet objects.

## Approximations

- [AMD.jl](https://github.com/JuliaSmoothOptimizers/AMD.jl) : Given a square sparse matrix, compute an approximate minimum degree ordering.
- [ChebyshevApprox.jl](https://github.com/RJDennis/ChebyshevApprox.jl) : Julia code to approximate continuous functions using Chebyshev polynomials.
- [FastGaussQuadrature.jl](https://github.com/JuliaApproximation/FastGaussQuadrature.jl) : A Julia package to compute n-point Gauss quadrature nodes and weights to 16-digit accuracy and in O(n) time.
- [FastTransforms.jl](https://github.com/JuliaApproximation/FastTransforms.jl) : Julia package for fast orthogonal polynomial transforms.
- [Remez.jl](https://github.com/simonbyrne/Remez.jl) : [Remez algorithm](https://en.wikipedia.org/wiki/Remez_algorithm) for computing minimax polynomial approximations.
- [Simplices.jl](https://github.com/JuliaDynamics/Simplices.jl) : Compute exact simplex intersections in N dimensions.
- [Sobol.jl](https://github.com/stevengj/Sobol.jl) : is a generation of [Sobol low-discrepancy sequence (LDS) implementation](https://en.wikipedia.org/wiki/Sobol_sequence), that generates **quasi-random** sequences of points in N dimensions which are equally distributed over an N-dimensional hypercube.
### Interpolations

- [CoordinateSplittingPTrees.jl](https://github.com/timholy/CoordinateSplittingPTrees.jl) : Accurate and efficient full-degree multidimensional polynomial interpolation.
- [DataInterpolations.jl](https://github.com/SciML/DataInterpolations.jl): A library of data interpolation and smoothing functions.
- [Dierckx.jl](https://github.com/kbarbary/Dierckx.jl) : Julia package for 1-d and 2-d splines, a wrapper for the dierckx Fortran library.
- [GridInterpolations.jl](https://github.com/sisl/GridInterpolations.jl) : Multi-dimensional grid interpolation in arbitrary dimensions on a recti-linear grid.
- [Interpolations.jl](https://github.com/JuliaMath/Interpolations.jl) : Fast, continuous interpolation of discrete datasets in Julia.
- [PiecewiseInterpolation.jl](https://github.com/gwater/PiecewiseInterpolation.jl) : A simple interface for interpolations on timeseries with first order discontinuities (using `Dierckx.jl`).

## Polynomials

[Wikipedia: Polynomials](https://en.wikipedia.org/wiki/Category:Polynomials)

- [FastPolynomialRoots.jl](https://github.com/andreasnoack/FastPolynomialRoots.jl) : Fast and backward stable computation of roots of polynomials by Fortran in Julia.
- [Jacobi.jl](https://github.com/pjabardo/Jacobi.jl) : Jacobi polynomials and Gauss quadrature related functions.
- [MultivariatePolynomials.jl](https://github.com/JuliaAlgebra/MultivariatePolynomials.jl) : Multivariate polynomials and multivariate moments.
- [PolynomialRoots.jl](https://github.com/giordano/PolynomialRoots.jl) : Fast complex polynomial root finder, with support for arbitrary precision calculations.
- [Polynomials.jl](https://github.com/JuliaMath/Polynomials.jl) : Basic arithmetic, integration, differentiation, evaluation, root finding, and fitting for univariate [polynomials](https://en.wikipedia.org/wiki/Polynomial) in [Julia](https://julialang.org/).
- [SemialgebraicSets.jl](https://github.com/JuliaAlgebra/SemialgebraicSets.jl) : Extension of MultivariatePolynomials to semi-algebraic sets.
- [TaylorModels.jl](https://github.com/JuliaIntervals/TaylorModels.jl) : A numerical mathematics package to treat the high-order scaling property of the remainder bound interval in a Taylor polynomial. [📹 JuliaCon 2018](https://youtu.be/o1h7BUW04NI).

## Functions

[Wikipedia: Functions](https://en.wikipedia.org/wiki/Category:Types_of_functions)

> Evaluation and approximations of functions

- [ApproxFun.jl](https://github.com/JuliaApproximation/ApproxFun.jl) : Julia package for function approximation.
- [BasisFunctions.jl](https://github.com/JuliaApproximation/BasisFunctions.jl) : A collection of routines for working with a number of standard basis functions. For more complete software packages to manipulate numerical function approximations, please consider ApproxFun.
- [Elliptic.jl](https://github.com/nolta/Elliptic.jl) : Elliptic integral and Jacobi elliptic special functions.
- [FrameFun.jl](https://github.com/JuliaApproximation/FrameFun.jl) : Exploring practical possibilities of approximating functions with frames rather than with a basis.
- [LambertW.jl](https://github.com/jlapeyre/LambertW.jl) : A package implementing the Lambert_W function and associated omega constant.
- [LogExpFunctions.jl](https://github.com/JuliaStats/LogExpFunctions.jl): Julia package for various special functions based on `log` and `exp`.
- [NaNMath.jl](https://github.com/JuliaMath/NaNMath.jl) : Implementations of basic math functions which return NaN instead of throwing a `DomainError`.
- [SpecialFunctions.jl](https://github.com/JuliaMath/SpecialFunctions.jl) : Special mathematical functions in Julia.
- [Struve.jl](https://github.com/gwater/Struve.jl) : [Struve](https://dlmf.nist.gov/11) functions for Julia.

## Calculus

- [Riemann Hypothesis book](https://wstein.org/rh/) with the [source code on github](https://github.com/williamstein/rh).
- [Calculus With Julia](https://github.com/CalculusWithJulia/CalculusWithJulia.github.io) : Introductory Calculus with the Julia Programming Language.
- An IJulia notebook showing [Taylor's method integration of the pendulum](https://nbviewer.org/gist/lbenet/616fa81f3c12c9cfcf97).

---

- [Calculus.jl](https://github.com/JuliaMath/Calculus.jl) : Calculus package.
- [Cuba.jl](https://github.com/giordano/Cuba.jl) : Library for multidimensional numerical integration with the [Cuba library](https://www.feynarts.de/cuba/).
- [Cubature.jl](https://github.com/JuliaMath/Cubature.jl) : Oneand multi-dimensional adaptive integration routines for the Julia language.
- [FastGaussQuadrature.jl](https://github.com/JuliaApproximation/FastGaussQuadrature.jl) : Computes Gauss quadrature rules to 16-digit precision (so far Legendre, Jacobi, Lobatto, Radau).
- [FiniteDifferences.jl](https://github.com/JuliaDiff/FiniteDifferences.jl) : estimating derivatives with [finite differences](https://en.wikipedia.org/wiki/Finite_difference).
- [FiniteDiff.jl](https://github.com/JuliaDiff/FiniteDiff.jl) : Fast non-allocating calculations of gradients, Jacobians, and Hessians with sparsity support.
- [FractionalCalculus.jl](https://github.com/SciFracX/FractionalCalculus.jl) : High performance and high precision numerical [fractional calculus](https://en.wikipedia.org/wiki/Fractional_calculus) computing.
- [HCubature.jl](https://github.com/JuliaMath/HCubature.jl) : Pure-Julia multidimensional h-adaptive integration.
- [Integrals.jl](https://github.com/SciML/Integrals.jl) : A common interface for quadrature and numerical integration.
- [RiemannComplexNumbers.j](https://github.com/scheinerman/RiemannComplexNumbers.jl) : The RiemannComplexNumbers module is an alternative Complex type for Julia (with a single complex infinity value).
- [Roots.jl](https://github.com/JuliaMath/Roots.jl) : Root finding functions for Julia.
- [TaylorSeries.jl](https://github.com/JuliaDiff/TaylorSeries.jl) : A julia package for Taylor expansions in one independent variable.
- [WiltonInts84.jl](https://github.com/krcools/WiltonInts84.jl) : Integrals of arbitrary powers of R over flat triangles.

### Automatic Differentiation

- [ADOLC.jl](https://github.com/TimSiebert1/ADOLC.jl) : A Julia wrapper of the automatic differentiation package [ADOL-C](https://github.com/coin-or/ADOL-C). [JuliaCon 2024 video](https://www.youtube.com/watch?v=ctIZi0ToYeM)
- [ChainRules.jl](https://github.com/JuliaDiff/ChainRules.jl) : forward and reverse mode automatic differentiation primitives.
- [DifferentiationInterface.jl](https://github.com/gdalle/DifferentiationInterface.jl) : An interface to various automatic differentiation backends in Julia. [JuliaCon 2024 video](https://youtu.be/ww3ntpyxNtI)
- [Diffractor.jl](https://github.com/JuliaDiff/Diffractor.jl) : An experimental next-generation, compiler-based AD system for Julia.
- [DualNumbers.jl](https://github.com/JuliaDiff/DualNumbers.jl) : Julia package for representing dual numbers and for performing dual algebra.
- [Enzyme.jl](https://github.com/EnzymeAD/Enzyme.jl) : Julia bindings for the [Enzyme](https://github.com/wsmoses/enzyme) automatic differentiator. The Enzyme project is a tool for performing reverse-mode automatic differentiation (AD) of statically-analyzable LLVM IR.
- [ForwardDiff.j](https://github.com/JuliaDiff/ForwardDiff.jl) : Forward Mode Automatic Differentiation for Julia.
- [HyperDualNumbers.jl](https://github.com/JuliaDiff/HyperDualNumbers.jl) : Hyper-dual numbers can be used to compute first and second derivatives numerically without the cancellation errors of finite-differencing schemes.
- [ReverseDiff.jl](https://github.com/JuliaDiff/ReverseDiff.jl) : Reverse Mode Automatic Differentiation for Julia.
- [StochasticAD.jl](https://github.com/gaurav-arya/StochasticAD.jl) : automatic differentiation of programs containing discrete randomness. [JuliaCon 2023 video](https://www.youtube.com/watch?v=_irOyB1ODvM)
- [Yota.jl](https://github.com/dfdx/Yota.jl) : Reverse-mode automatic differentiation for static and dynamic graphs.
- [Zygote.jl](https://github.com/FluxML/Zygote.jl) : Source-to-source automatic differentiation (AD) in Julia, and is the next-gen AD system for the Flux differentiable programming framework.

## Mathematical Analysis

[Wikipedia: Mathematical Analysis](https://en.wikipedia.org/wiki/Category:Mathematical_analysis)

- [Complementarity.jl](https://github.com/chkwon/Complementarity.jl) : This package provides a modeling and computational interface for solving [Mixed Complementarity Problems (MCP)](https://en.wikipedia.org/wiki/Mixed_complementarity_problem), modeling by `JuMP.jl` and computing by `PATHSolver.jl`.
- [Fatou.jl](https://github.com/chakravala/Fatou.jl) : [Fatou/Julia sets](https://en.wikipedia.org/wiki/Julia_set) in Julia (Fractals, Newton basins, Mandelbrot).
- [PATHSolver.jl](https://github.com/chkwon/PATHSolver.jl) : This package provides a Julia wrapper of the PATH Solver for solving _linear_ Mixed Complementarity Problems (MCP).
- [Wilkinson.jl](https://github.com/chakravala/Wilkinson.jl) : Toolkit for studying numerical analysis and floating point algebra round-off error in Julia.

## Discrete math

- [Wikipedia: Discrete math](https://en.wikipedia.org/wiki/Category:Discrete_mathematics)
- [Wikipedia: Combinatorics](https://en.wikipedia.org/wiki/Category:Combinatorics)
- See also [[graph]] theory

---

- [Collatz.jl](https://github.com/StefanKarpinski/Collatz.jl) : The [Collatz conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture).
- [PermPlain.jl](https://github.com/jlapeyre/PermPlain.jl) : Permutations of integers.
- [Permutations.jl](https://github.com/scheinerman/Permutations.jl) : Permutations class for Julia.
- [SimplePosets.jl](https://github.com/scheinerman/SimplePosets.jl) : Simple partially ordered sets for Julia.
- [ZChop.jl](https://github.com/jlapeyre/ZChop.jl) : Replaces small numbers with zero.

## Information theory

[Wikipedia: Information theory](https://en.wikipedia.org/wiki/Information_theory)

- [InformationMeasures.jl](https://github.com/Tchanders/InformationMeasures.jl) : Entropy, mutual information and higher order measures from information theory, with various estimators and discretization methods.