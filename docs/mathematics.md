---
title: Mathematics
---

[Mathematical](https://en.wikipedia.org/wiki/Lists_of_mathematics_topics) libraries/packages, and related resources in Julia.

## Organizations

- [Julia Approximation](https://github.com/JuliaApproximation)
- [Julia Crypto](https://github.com/JuliaCrypto)
- [Julia Linear Algebra](https://github.com/JuliaLinearAlgebra)
- [Julia Math](https://github.com/JuliaMath)
- [Julia Matrices](https://github.com/JuliaMatrices/)
- [Julia Diff](https://github.com/JuliaDiff)
- [Julia sparse](https://github.com/JuliaSparse)
- [Julia DSP](https://github.com/JuliaDSP)
- [Julia Arrays](https://github.com/JuliaArrays)

## General Mathematics packages

- https://github.com/andrioni/MPFR.jl : A Julia package for the GNU MPFR library.
- https://github.com/dillondaudert/UMAP.jl : Uniform Manifold Approximation and Projection ([UMAP](https://arxiv.org/abs/1802.03426)) implementation in Julia.
- https://github.com/dmbates/NLreg.jl : Nonlinear regression in Julia.
- https://github.com/GiovineItalia/Hexagons.jl : Useful tools for working with hexagonal grids.
- https://github.com/JuliaManifolds/Manifolds.jl : a unified interface to define and use manifolds as well as a library of manifolds to use for your projects.
- https://github.com/JuliaMath/FastPow.jl : `@fastpow` speeds up the computation of integer powers in any Julia expression by transforming them into optimal sequences of multiplications, with a slight sacrifice in accuracy.
- https://github.com/JuliaMath/GSL.jl : Julia interface to the GNU Scientific Library - [GSL](https://www.gnu.org/software/gsl/doc/html/index.html).
- https://github.com/JuliaMath/NaNMath.jl : Implementations of basic math functions which return NaN instead of throwing a `DomainError`.
- https://github.com/JuliaMath/Tau.jl : A simple module providing definition of the Tau constant = 2pi.
- https://github.com/SciML/NonlinearSolve.jl : Fast implementations of root finding algorithms in Julia using the SciML common interface.
- https://github.com/thofma/Hecke.jl : Computational algebraic number theory.

## Cryptography

- [Wikipedia: Cryptography](https://en.wikipedia.org/wiki/Cryptography)
- [Wikipedia: checksums](https://en.wikipedia.org/wiki/Checksum)

---

- https://github.com/andrewcooke/CRC.jl : a Julia module for calculating Cyclic Redundancy Checksums (CRCs).
- https://github.com/JuliaCrypto/MD5.jl : A pure julia MD5 implementation.
- https://github.com/JuliaCrypto/Nettle.jl : is a simple wrapper around libnettle, a cryptographic library, providing MD5, SHA1, SHA2 hashing and HMAC functionality, as well as AES encryption/decryption
- https://github.com/JuliaCrypto/SEAL.jl : wrapping the Microsoft SEAL library for homomorphic encryption
- https://github.com/JuliaCrypto/SHA.jl : a performant, 100% native-julia SHA-1, SHA-2 224, 256, 384 and 512, and SHA-3 224, 256, 384 and 512 functions.
- https://github.com/JuliaIO/CRC32.jl : computing the [CRC-32 checksum](https://en.wikipedia.org/wiki/Cyclic_redundancy_check).
- https://github.com/JuliaLang/MbedTLS.jl : Wrapper around [mbedtls](https://tls.mbed.org/).
- https://github.com/JuliaRandom/RNGTest.jl : A package that is a Julia interface to the test suite TestU01 of Pierre l'Ecuyer to test random numbers.
- https://gitlab.com/braneproject/ECC.jl : Elliptic Curve Cryptography in Julia (secp256k1 curve).

### Cryptocurrency

- https://github.com/Julia-Blockchain/LearnBlockChain : Block chain [tutorial](https://www.youtube.com/watch?v=eDELq53TpNc) in Julia.

## Computer Arithmetic

- [Wikipedia: Computer Arithmetic](https://en.wikipedia.org/wiki/Category:Computer_arithmetic)
- [ent](https://github.com/williamstein/ent) : Primes, Congruences, and Secrets.

---

- https://github.com/jlapeyre/DeepConvert.jl : This package provides convenient literal construction of values of large data types.
- https://github.com/tshort/Calc.jl : An RPN calculator for the Julia REPL.

### Floating Point

[Wikipedia: Floating Point](https://en.wikipedia.org/wiki/Category:Floating_point)

For floating-point datatypes, see [[data-structures]].

- https://github.com/JeffreySarnoff/ErrorfreeArithmetic.jl : Error-free transformations for arithmetic ops.
- https://github.com/JeffreySarnoff/FastRounding.jl : Faster directed rounding for inline arithmetic.
- https://github.com/JuliaIntervals/ValidatedNumerics.jl : Rigorous floating-point calculations via interval arithmetic.

## Algebra

Resources: https://github.com/williamstein/adeles algebraic number theory

- https://github.com/JuliaComputing/SemiringAlgebra.jl : [Semiring Algebra](https://dspace.mit.edu/handle/1721.1/115964). A linear algebraic approach to graph algorithms that exploits the sparse adjacency matrix representation of graphs can provide a variety of benefits.
- https://github.com/MurrayT/OEIS.jl : A basic wrapper to allow access to [OEIS](http://oeis.org/) integer sequences from within Julia.
- https://github.com/Nemocas/Nemo.jl : A computer algebra package for the Julia programming language.
- https://github.com/scheinerman/Mods.jl : Easy modular arithmetic for Julia.
- https://github.com/thofma/Hecke.jl : A package for algebraic number theory that works on top of `Nemo.jl` by Tommy Hofmann and Claus Fieker.

### Boolean Algebra

[Boolean Algebra](https://en.wikipedia.org/wiki/Category:Boolean_algebra)

- https://github.com/scheinerman/ShowSet.jl : Nicer output for Set and IntSet objects.

## Numerical Analysis

[Numerical Analysis](https://en.wikipedia.org/wiki/Category:Numerical_analysis)

- https://github.com/cdsousa/LinearExpressions.jl : Linear symbolic expressions for the Julia language.
- https://github.com/floswald/ApproXD.jl : B-splines and linear high-dimensional approximators in multiple dimensions for Julia.
- https://github.com/gwater/PiecewiseInterpolation.jl : A simple interface for interpolations on timeseries with first order discontinuities (using `Dierckx.jl`).
- https://github.com/JeffreySarnoff/RollingFunctions.jl : Roll a function over data, run a statistic along a `weighted` data window.
- https://github.com/JuliaApproximation/FastGaussQuadrature.jl : A Julia package to compute n-point Gauss quadrature nodes and weights to 16-digit accuracy and in O(n) time.
- https://github.com/JuliaApproximation/FastTransforms.jl : Julia package for fast orthogonal polynomial transforms.
- https://github.com/JuliaDynamics/Simplices.jl : Compute exact simplex intersections in N dimensions.
- https://github.com/JuliaMath/Interpolations.jl : Fast, continuous interpolation of discrete datasets in Julia.
- https://github.com/JuliaSmoothOptimizers/AMD.jl : Approximate Minimum Degree (AMD) Ordering in Julia.
- https://github.com/jump-dev/Dualization.jl : Automatic dualization feature for MathOptInterface.jl conic optimization problems.
- https://github.com/jump-dev/KNITRO.jl : Julia interface to the [Knitro](https://www.artelys.com/solvers/knitro/) solver.
- https://github.com/kbarbary/Dierckx.jl : Julia package for 1-d and 2-d splines, a wrapper for the dierckx Fortran library.
- https://github.com/mrtkp9993/NumericalAlgorithms.jl : Statistics & Numerical algorithms implemented in Julia.
- https://github.com/sisl/GridInterpolations.jl : Multi-dimensional grid interpolation in arbitrary dimensions on a recti-linear grid.
- https://github.com/stevengj/Sobol.jl : is a generation of Sobol low-discrepancy sequence (LDS) implementation, that generates **quasi-random** sequences of points in N dimensions which are equally distributed over an N-dimensional hypercube.

## Linear Algebra

[Linear Algebra](https://en.wikipedia.org/wiki/Category:Linear_algebra)

- [Video of Andreas Noack and Jiahao Chen](https://www.youtube.com/channel/UCizxnsw19qcTOdJdIJVtl0Q) speaking at the Linear Algebra and Optimization seminar at the Institute for Computational and Mathematical Engineering at Stanford.
- Learn the [theory of linear algebra](https://github.com/ULAFF/notebooks) in Python Jupyter notebooks.
- [Benchmarking Matrix Multiplication](https://nbviewer.org/url/math.mit.edu/~stevenj/18.335/Matrix-multiplication-experiments.ipynb)

---

- https://github.com/aaw/IncrementalSVD.jl : Simon Funk's approach to collaborative filtering using the singular value decomposition, implemented in Julia.
- https://github.com/chakravala/DirectSum.jl : Abstract tangent bundle vector space type operations.
- https://github.com/chakravala/Leibniz.jl : Operator algebras for mixed-symmetry multivariate differentiable tensor fields.
- https://github.com/christianpeel/LLLplus.jl : LLL lattice reduction, sphere decoder, and related lattice tools.
- https://github.com/gragusa/Divergences.jl : A Julia package that makes it easy to evaluate divergence measures between two vectors. The package allows calculating the gradient and the diagonal of the Hessian of several divergences which can be used to good effect by the MomentBasedEstimators package.
- https://github.com/JuliaFolds/FGenerators.jl : A package for defining `Transducers.jl`-compatible extended `foldl` with a simple `@yield`-based syntax.
- https://github.com/JuliaFolds/Transducers.jl : provides composable algorithms on "sequence" of inputs. This feature, available in Clojure language, is a [transformation matrix](https://en.wikipedia.org/wiki/Transformation_matrix) for linear transformations that is now in Julia.
- https://github.com/JuliaLinearAlgebra/GenericLinearAlgebra.jl : Partly to extend linear algebra functionality in base to cover generic element types, e.g. `BigFloat` and `Quaternion`, and partly to be a place to experiment with fast linear algebra routines.
- https://github.com/JuliaLinearAlgebra/IterativeSolvers.jl : Iterative algorithms for solving linear systems, eigen systems, and singular value problems.
- https://github.com/JuliaLinearAlgebra/LinearMaps.jl : A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
- https://github.com/JuliaLinearAlgebra/MKL.jl : Intel MKL linear algebra backend for Julia.
- https://github.com/JuliaMath/IntelVectorMath.jl : Julia bindings for the Intel Vector Math Library.
- https://github.com/JuliaParallel/Elemental.jl : A Julia interface to the [Elemental linear algebra library](https://github.com/elemental/Elemental) with third-party interfaces.
- https://github.com/JuliaRandom/VSL.jl : Julia bindings for the Intel Vector Statistics Library. Requires `MKL.jl`.
- https://github.com/Jutho/TensorOperations.jl : Julia package for tensor contractions and related operations.
- https://github.com/lopezm94/SugarBLAS.jl : Syntactic sugar for BLAS polynomials.
- https://github.com/mcabbott/TensorCast.jl :  working with multi-dimensional arrays in index notation.
- https://github.com/wildart/LMCLUS.jl : Julia's package for Linear Manifold Clustering.

### Array Data Structures

- https://github.com/davidavdav/NamedArrays.jl : Julia type that implements a drop-in replacement of Array with named dimensions and Dict-type indexes.
- https://github.com/eschnett/FastArrays.jl : Multi-dimensional arrays with arbitrary upper and lower bounds that can be fixed at compile time.
- https://github.com/garrison/UniqueVectors.jl : Vectors of unique elements, with quick reverse lookups.
- https://github.com/JuliaApproximation/ContinuumArrays.jl : A package for representing quasi arrays with continuous indices.
- https://github.com/JuliaApproximation/QuasiArrays.jl : A package for representing quasi-arrays, viz. arrays with non-classical indexing, including possibly continuous indexing.
- https://github.com/JuliaArrays/ArrayInterface.jl : Designs for new Base array interface primitives.
- https://github.com/JuliaArrays/BlockArrays.jl : BlockArrays for Julia.
- https://github.com/JuliaArrays/IndirectArrays.jl : Julia implementation of indexed or "lookup" arrays.
- https://github.com/JuliaArrays/InfiniteArrays.jl : A Julia package for representing infinite-dimensional arrays.
- https://github.com/JuliaArrays/LazyArrays.jl : Lazy arrays and linear algebra in Julia.
- https://github.com/JuliaArrays/LazyGrids.jl : lazy representation of multi-dimensional grids.
- https://github.com/JuliaArrays/MappedArrays.jl : Lazy in-place transformations of arrays.
- https://github.com/JuliaArrays/OffsetArrays.jl : Fortran-like arrays with arbitrary, zero or negative starting indices for arrays in Julia. The main purpose of this package is to simplify translation from Fortran codes intensively using Fortran arrays with negative and zero starting indices, such as the codes accompanying the book Numerical Solution of Hyperbolic Partial Differential Equations by prof. John A. Trangenstein.
- https://github.com/JuliaArrays/RangeArrays.jl : Efficient and convenient array data structures where the columns of the arrays are generated (on the fly) by Ranges.
- https://github.com/JuliaArrays/ShiftedArrays.jl : Lazy shifted arrays implementation for data analysis in Julia.
- https://github.com/JuliaArrays/StaticArrays.jl : Statically sized arrays for Julia.
- https://github.com/JuliaArrays/StructArrays.jl : Efficient implementation of struct arrays.
- https://github.com/JuliaCollections/SuffixArrays.jl : Native Julia suffix array implementation.
- https://github.com/JuliaData/CategoricalArrays.jl : Arrays for working with categorical data (both nominal and ordinal) in Julia.
- https://github.com/JuliaMath/RandomMatrices.jl : Random Matrices, extending the `Distributions` package to provide methods for working with matrix-valued random variables.
- https://github.com/JuliaSIMD/StrideArrays.jl : Library supporting the ArrayInterface.jl strided array interface.
- https://github.com/meggart/DiskArrays.jl : Accessing array data on slower media (e.g., hard disk).
- https://github.com/RalphAS/Pseudospectra.jl : a package for computing pseudospectra of non-symmetric matrices, and plotting them along with eigenvalues ("spectral portraits").
- https://github.com/sisl/Vec.jl : Provides 2D and 3D vector types for vector operations. All types are immutable and are subtypes of `StaticArrays.jl`.
- https://github.com/timholy/NamedAxesArrays.jl : Performant arrays where each axis can be named.

### Matrices

[Wikipedia: Matrix Theory](https://en.wikipedia.org/wiki/Category:Matrix_theory)

> Special Array/Matrix Algorithms, for Array Types, see Data Types section.

- https://github.com/IshitaTakeshi/KSVD.jl : K-SVD is an algorithm for creating over-complete dictionaries for sparse representations.
- https://github.com/JuliaArrays/CatIndices.jl : Julia package for indices-aware array concatenation and growth.
- https://github.com/JuliaArrays/EndpointRanges.jl : Julia package for doing arithmetic on endpoints in array indexing.
- https://github.com/JuliaArrays/PaddedViews.jl : Add virtual padding to the edges of an array.
- https://github.com/JuliaLinearAlgebra/TSVD.jl : Truncated singular value decomposition with partial reorthogonalization.
- https://github.com/JuliaMatrices/BandedMatrices.jl : A Julia package for representing banded matrices.
- https://github.com/JuliaMatrices/LowRankApprox.jl : Fast low-rank matrix approximation in Julia.
- https://github.com/JuliaMatrices/MatrixDepot.jl : An Extensible Test Matrix Collection for Julia. [Documentation](https://matrixdepotjl.readthedocs.io/en/latest/)
- https://github.com/JuliaMatrices/SpecialMatrices.jl : Julia package for working with special matrix types.
- https://github.com/JuliaMatrices/ToeplitzMatrices.jl : Fast matrix multiplication and division for Toeplitz matrices in Julia.
- https://github.com/JuliaStats/PDMats.jl : Uniform Interface for positive definite matrices of various structures.
- https://github.com/MichielStock/Kronecker.jl : A general-purpose toolbox for efficient Kronecker-based algebra that combines lazy evaluation and algebraic tricks such that it can implicitly work with huge matrices. It allows to work with large Kronecker systems both much faster and using much less memory than the naive implementation of the [Kronecker product](https://en.wikipedia.org/wiki/Kronecker_product).
- https://github.com/timholy/AxisAlgorithms.jl : Efficient filtering and linear algebra routines for multidimensional arrays.
- https://github.com/timholy/PositiveFactorizations.jl : Positive-definite (approximations) to matrices.
- https://github.com/timholy/WoodburyMatrices.jl : Library support for the [Woodbury matrix identity](https://en.wikipedia.org/wiki/Woodbury_matrix_identity).
- https://github.com/WaveProp/HMatrices.jl : A Julia library for hierarchical matrices.
- https://github.com/niclaspopp/RandomizedDiagonalEstimation.jl : randomized diagonal estimation of matrices and matrix functions. [JuliaCon 2024 video](https://youtu.be/ly8S1NjbaK0)

#### Sparse Matrices

[Wikipedia: Sparse Matrices](https://en.wikipedia.org/wiki/Category:Sparse_matrices)

- https://github.com/FixedEffects/InteractiveFixedEffectModels.jl : Estimate factor models on sparse datasets.
- https://github.com/JuliaSmoothOptimizers/MUMPS.jl : An interface to MUMPS, a libray for the solution of sparse linear systems on multicore computers.
- https://github.com/JuliaSparse/HarwellRutherfordBoeing.jl : A Julia Reader for the Harwell-Boeing and Rutherford-Boeing Formats.
- https://github.com/JuliaSparse/MatrixMarket.jl : A package to read the [MatrixMarket file format](https://math.nist.gov/MatrixMarket/formats.html#MMformat).
- https://github.com/JuliaSparse/Metis.jl : Julia interface to the [Metis](https://github.com/KarypisLab/METIS) graph-partitioning algorithms.
- https://github.com/JuliaSparse/MKLSparse.jl : Override sparse-dense operations when MKL is available.
- https://github.com/JuliaSparse/Pardiso.jl : Calling the [PARDISO](https://www.pardiso-project.org) library from Julia.

### Tensors

- https://github.com/ahwillia/Einsum.jl : [Einstein summation notation](https://en.wikipedia.org/wiki/Einstein_notation) in julia.
- https://github.com/chakravala/AbstractTensors.jl : Tensor algebra abstract type interoperability with vector bundle parameter.
- https://github.com/ITensor/ITensors.jl : A Julia library for efficient tensor calculations.
- https://github.com/mcabbott/Tullio.jl : A very flexible [einsum](https://en.wikipedia.org/wiki/Einstein_notation) macro. A package for writing array operations in index notation.
- https://github.com/willow-ahrens/Finch.jl : Finch is a cutting-edge Julia-to-Julia compiler specially designed for optimizing loop nests over sparse or structured multidimensional arrays.

## Digital signal processing (DSP)

[Wikipedia: DSP](https://en.wikipedia.org/wiki/Digital_signal_processing)

- https://github.com/JuliaDSP/DSP.jl : Filter design, periodograms, window functions, and other digital signal processing functionality.
- https://github.com/JuliaDSP/Wavelets.jl : Fast Discrete Wavelet Transforms written in Julia by JuliaDSP.
- https://github.com/nantonel/ImageMethodReverb.jl : Julia implementation of a Room Acoustics Impulse Response Generator using the Randomized Image Method (RIM).
- https://github.com/sairus7/SortFilters.jl : Fast moving quantile filters implemented as fast moving window sort algorithm.
- https://github.com/stevengj/MDCT.jl : This module computes the modified discrete cosine transform (MDCT) in the Julia language and the inverse transform (IMDCT), using the fast type-IV discrete cosine transform (DCT-IV) functions in Julia (via FFTW).

### Fast Fourier transform (FFT)

[Wikipedia: FFT](https://en.wikipedia.org/wiki/Fast_Fourier_transform)

- https://github.com/bionanoimaging/FourierTools.jl : Tools for working with Fourier space. [JuliaCon 2021 video](https://youtu.be/qYgJDb_Ko2E)
- https://github.com/gwater/HexFFT.jl : Fast Fourier transform on hexagonal grids using [Birdsong and Rummelt's algorithm](https://ieeexplore.ieee.org/document/7532670/).
- https://github.com/JuliaArrays/FFTViews.jl : Julia package for fast fourier transforms and periodic views.
- https://github.com/JuliaMath/FFTW.jl : Julia bindings to the FFTW library for fast Fourier transforms.
- https://github.com/JuliaMath/NFFT.jl : Julia implementation of the Non-equidistant Fast Fourier Transform (NFFT).

## Symbolic Computation

See [[modeling-simulation]]

## Polynomials

[Wikipedia: Polynomials](https://en.wikipedia.org/wiki/Category:Polynomials)

- https://github.com/andreasnoack/FastPolynomialRoots.jl : Fast and backward stable computation of roots of polynomials in Julia.
- https://github.com/daviddelaat/MultiPoly.jl : Sparse multivariate polynomials in Julia. (No `Project.toml`)
- https://github.com/giordano/PolynomialRoots.jl : Fast complex polynomial root finder, with support for arbitrary precision calculations
- https://github.com/JuliaAlgebra/FixedPolynomials.jl : A package for really fast evaluation of multivariate polynomials. (No `Project.toml`)
- https://github.com/JuliaAlgebra/MultivariatePolynomials.jl : Multivariate polynomials and multivariate moments.
- https://github.com/JuliaAlgebra/SemialgebraicSets.jl : Extension of MultivariatePolynomials to semi-algebraic sets.
- https://github.com/JuliaIntervals/TaylorModels.jl : A numerical mathematics package to treat the high-order scaling property of the remainder bound interval in a Taylor polynomial. [📹 JuliaCon 2018](https://youtu.be/o1h7BUW04NI).
- https://github.com/JuliaMath/Polynomials.jl : Polynomial manipulations and [PolyExt](https://gist.github.com/mathpup/8514578), an extension of Polynomial.jl to support polynomial division, with handy conversions and promotion rules.
- https://github.com/pjabardo/Jacobi.jl : Jacobi polynomials and Gauss quadrature related functions.
- https://github.com/RJDennis/ChebyshevApprox.jl : Julia code to approximate continuous functions using Chebyshev polynomials.
- https://github.com/simonbyrne/Remez.jl : [Remez algorithm](https://en.wikipedia.org/wiki/Remez_algorithm) for computing minimax polynomial approximations.
- https://github.com/timholy/CoordinateSplittingPTrees.jl : Accurate and efficient full-degree multidimensional polynomial interpolation.

## Functions

[Wikipedia: Functions](https://en.wikipedia.org/wiki/Category:Types_of_functions)

> Evaluation and approximations of functions

- https://github.com/gwater/Struve.jl : [Struve](https://dlmf.nist.gov/11) functions for Julia.
- https://github.com/jlapeyre/LambertW.jl : A package implementing the Lambert_W function and associated omega constant.
- https://github.com/JuliaApproximation/ApproxFun.jl : Julia package for function approximation.
- https://github.com/JuliaApproximation/BasisFunctions.jl : A collection of routines for working with a number of standard basis functions. For more complete software packages to manipulate numerical function approximations, please consider ApproxFun.
- https://github.com/JuliaApproximation/FrameFun.jl : Exploring practical possibilities of approximating functions with frames rather than with a basis.
- https://github.com/JuliaMath/SpecialFunctions.jl : Special mathematical functions in Julia.
- https://github.com/nolta/Elliptic.jl : Elliptic integral and Jacobi elliptic special functions.

## Calculus

- [Riemann Hypothesis book](https://wstein.org/rh/) with the [source code on github](https://github.com/williamstein/rh).
- [Calculus With Julia](https://github.com/CalculusWithJulia/CalculusWithJulia.github.io) : Introductory Calculus with the Julia Programming Language.
- An IJulia notebook showing [Taylor's method integration of the pendulum](https://nbviewer.org/gist/lbenet/616fa81f3c12c9cfcf97).

---

- https://github.com/giordano/Cuba.jl : Library for multidimensional numerical integration with the [Cuba library](https://www.feynarts.de/cuba/).
- https://github.com/JuliaApproximation/FastGaussQuadrature.jl : Computes Gauss quadrature rules to 16-digit precision (so far Legendre, Jacobi, Lobatto, Radau).
- https://github.com/JuliaDiff/FiniteDiff.jl : Fast non-allocating calculations of gradients, Jacobians, and Hessians with sparsity support.
- https://github.com/JuliaDiff/FiniteDifferences.jl : estimating derivatives with [finite differences](https://en.wikipedia.org/wiki/Finite_difference).
- https://github.com/JuliaDiff/TaylorSeries.jl : A julia package for Taylor expansions in one independent variable.
- https://github.com/JuliaMath/Calculus.jl : Calculus package.
- https://github.com/JuliaMath/Cubature.jl : One- and multi-dimensional adaptive integration routines for the Julia language.
- https://github.com/JuliaMath/HCubature.jl : Pure-Julia multidimensional h-adaptive integration.
- https://github.com/JuliaMath/Roots.jl : Root finding functions for Julia.
- https://github.com/krcools/WiltonInts84.jl : Integrals of arbitrary powers of R over flat triangles.
- https://github.com/scheinerman/RiemannComplexNumbers.jl : The RiemannComplexNumbers module is an alternative Complex type for Julia (with a single complex infinity value).
- https://github.com/SciFracX/FractionalCalculus.jl : High performance and high precision numerical [fractional calculus](https://en.wikipedia.org/wiki/Fractional_calculus) computing.
- https://github.com/SciML/Integrals.jl : A common interface for quadrature and numerical integration.

### Automatic Differentiation

- https://github.com/dfdx/Yota.jl : Reverse-mode automatic differentiation for static and dynamic graphs.
- https://github.com/EnzymeAD/Enzyme.jl : Julia bindings for the [Enzyme](https://github.com/wsmoses/enzyme) automatic differentiator. The Enzyme project is a tool for performing reverse-mode automatic differentiation (AD) of statically-analyzable LLVM IR.
- https://github.com/FluxML/Zygote.jl : Source-to-source automatic differentiation (AD) in Julia, and is the next-gen AD system for the Flux differentiable programming framework.
- https://github.com/gaurav-arya/StochasticAD.jl : automatic differentiation of programs containing discrete randomness. [JuliaCon 2023 video](https://www.youtube.com/watch?v=_irOyB1ODvM)
- https://github.com/JuliaDiff/ChainRules.jl : forward and reverse mode automatic differentiation primitives.
- https://github.com/JuliaDiff/Diffractor.jl : An experimental next-generation, compiler-based AD system for Julia.
- https://github.com/JuliaDiff/DualNumbers.jl : Julia package for representing dual numbers and for performing dual algebra.
- https://github.com/JuliaDiff/ForwardDiff.jl : Forward Mode Automatic Differentiation for Julia.
- https://github.com/JuliaDiff/HyperDualNumbers.jl : Hyper-Dual Numbers for Exact Second-Derivative Calculations, is structured similar to the DualNumbers package, which aims for complete support for HyperDual types for numerical functions within Julia's Base. Currently, basic mathematical operations and trigonometric functions are supported.
- https://github.com/JuliaDiff/ReverseDiff.jl : Reverse Mode Automatic Differentiation for Julia.
- https://github.com/mlubin/ReverseDiffSparse.jl : Hessian algorithmic differentiation to compute hessian sparsity pattern.
- https://github.com/TimSiebert1/ADOLC.jl : A Julia wrapper of the automatic differentiation package https://github.com/coin-or/ADOL-C. [JuliaCon 2024 video](https://www.youtube.com/watch?v=ctIZi0ToYeM)

## Mathematical Analysis

[Wikipedia: Mathematical Analysis](https://en.wikipedia.org/wiki/Category:Mathematical_analysis)

- https://github.com/chakravala/Fatou.jl : [Fatou/Julia sets](https://en.wikipedia.org/wiki/Julia_set) in Julia (Fractals, Newton basins, Mandelbrot).
- https://github.com/chakravala/Wilkinson.jl : Toolkit for studying numerical analysis and floating point algebra round-off error in Julia.
- https://github.com/chkwon/Complementarity.jl : This package provides a modeling and computational interface for solving [Mixed Complementarity Problems (MCP)](https://en.wikipedia.org/wiki/Mixed_complementarity_problem), modeling by `JuMP.jl` and computing by `PATHSolver.jl`.
- https://github.com/chkwon/PATHSolver.jl : This package provides a Julia wrapper of the PATH Solver for solving _linear_ Mixed Complementarity Problems (MCP).

## Discrete math

- [Wikipedia: Discrete math](https://en.wikipedia.org/wiki/Category:Discrete_mathematics)
- [Wikipedia: Combinatorics](https://en.wikipedia.org/wiki/Category:Combinatorics)

---

- https://github.com/jlapeyre/PermPlain.jl : Permutations of integers.
- https://github.com/jlapeyre/ZChop.jl : Replaces small numbers with zero.
- https://github.com/scheinerman/Permutations.jl : Permutations class for Julia.
- https://github.com/scheinerman/SimplePosets.jl : Simple partially ordered sets for Julia.
- https://github.com/StefanKarpinski/Collatz.jl : The [Collatz conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture).

### Graph Theory

See [[graph]] theory section.

## Information theory

[Wikipedia: Information theory](https://en.wikipedia.org/wiki/Information_theory)

- https://github.com/Tchanders/InformationMeasures.jl : Entropy, mutual information and higher order measures from information theory, with various estimators and discretisation methods.
