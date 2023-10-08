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

- [FastPow.jl](https://github.com/JuliaMath/FastPow.jl) : `@fastpow` speeds up the computation of integer powers in any Julia expression by transforming them into optimal sequences of multiplications, with a slight sacrifice in accuracy.
- [GSL.jl](https://github.com/JuliaMath/GSL.jl) : Julia interface to the GNU Scientific Library - [GSL](https://www.gnu.org/software/gsl/doc/html/index.html).
- [Hecke.jl](https://github.com/thofma/Hecke.jl) : Computational algebraic number theory.
- [Hexagons.jl](https://github.com/GiovineItalia/Hexagons.jl) : Useful tools for working with hexagonal grids.
- [Manifolds.jl](https://github.com/JuliaManifolds/Manifolds.jl) : a unified interface to define and use manifolds as well as a library of manifolds to use for your projects.
- [MPFR.jl](https://github.com/andrioni/MPFR.jl) : A Julia package for the GNU MPFR library.
- [NaNMath.jl](https://github.com/JuliaMath/NaNMath.jl) : Implementations of basic math functions which return NaN instead of throwing a `DomainError`.
- [NLreg.jl](https://github.com/dmbates/NLreg.jl) : Nonlinear regression in Julia.
- [NonlinearSolve.jl](https://github.com/SciML/NonlinearSolve.jl) : Fast implementations of root finding algorithms in Julia using the SciML common interface.
- [Tau.jl](https://github.com/JuliaMath/Tau.jl) : A simple module providing definition of the Tau constant = 2pi.
- [UMAP.jl](https://github.com/dillondaudert/UMAP.jl) : Uniform Manifold Approximation and Projection ([UMAP](https://arxiv.org/abs/1802.03426)) implementation in Julia.

## Cryptography

- [Wikipedia: Cryptography](https://en.wikipedia.org/wiki/Cryptography)
- [Wikipedia: checksums](https://en.wikipedia.org/wiki/Checksum)

---

- [MbedTLS.jl](https://github.com/JuliaLang/MbedTLS.jl) : Wrapper around [mbedtls](https://tls.mbed.org/).
- [MD5.jl](https://github.com/JuliaCrypto/MD5.jl) : A pure julia MD5 implementation.
- [Nettle.jl](https://github.com/JuliaCrypto/Nettle.jl) : is a simple wrapper around libnettle, a cryptographic library, providing MD5, SHA1, SHA2 hashing and HMAC functionality, as well as AES encryption/decryption
- [RNGTest.jl](https://github.com/JuliaRandom/RNGTest.jl) : A package that is a Julia interface to the test suite TestU01 of Pierre l'Ecuyer to test random numbers.
- [SHA.jl](https://github.com/JuliaCrypto/SHA.jl) : a performant, 100% native-julia SHA-1, SHA-2 224, 256, 384 and 512, and SHA-3 224, 256, 384 and 512 functions.
- [SEAL.jl](https://github.com/JuliaCrypto/SEAL.jl) : wrapping the Microsoft SEAL library for homomorphic encryption
- [CRC.jl](https://github.com/andrewcooke/CRC.jl) : a Julia module for calculating Cyclic Redundancy Checksums (CRCs).
- [CRC32.jl](https://github.com/JuliaIO/CRC32.jl) : computing the [CRC-32 checksum](https://en.wikipedia.org/wiki/Cyclic_redundancy_check).
- [ECC.jl](https://gitlab.com/braneproject/ECC.jl) : Elliptic Curve Cryptography in Julia (secp256k1 curve).

### Cryptocurrency

- [LearnBlockChain](https://github.com/Julia-Blockchain/LearnBlockChain) : Block chain [tutorial](https://www.youtube.com/watch?v=eDELq53TpNc) in Julia.

## Computer Arithmetic

- [Wikipedia: Computer Arithmetic](https://en.wikipedia.org/wiki/Category:Computer_arithmetic)
- [ent](https://github.com/williamstein/ent) : Primes, Congruences, and Secrets.

---

- [Calc.jl](https://github.com/tshort/Calc.jl) : An RPN calculator for the Julia REPL.
- [DeepConvert.jl](https://github.com/jlapeyre/DeepConvert.jl) : This package provides convenient literal construction of values of large data types.

### Floating Point

[Wikipedia: Floating Point](https://en.wikipedia.org/wiki/Category:Floating_point)

For floating-point datatypes, see [[data-structures]].

- [ErrorfreeArithmetic.jl](https://github.com/JeffreySarnoff/ErrorfreeArithmetic.jl) : Error-free transformations for arithmetic ops.
- [FastRounding.jl](https://github.com/JeffreySarnoff/FastRounding.jl) : Faster directed rounding for inline arithmetic.
- [ValidatedNumerics.jl](https://github.com/JuliaIntervals/ValidatedNumerics.jl) : Rigorous floating-point calculations via interval arithmetic.

## Algebra

Resources: [Ideles adeles algebraic number theory](https://github.com/williamstein/adeles)

- [Equations.jl](https://github.com/jhlq/Equations.jl) : Derive mathematical relations.
- [Hecke.jl](https://github.com/thofma/Hecke.jl) : A package for algebraic number theory that works on top of `Nemo.jl` by Tommy Hofmann and Claus Fieker.
- [HemirealFactorizations.jl](https://github.com/timholy/HemirealFactorizations.jl) : Matrix factorizations over the hemireals.
- [HemirealNumbers.jl](https://github.com/timholy/HemirealNumbers.jl) : Implementation of hemireal arithmetic for Julia.
- [Mods.jl](https://github.com/scheinerman/Mods.jl) : Easy modular arithmetic for Julia.
- [Nemo.jl](https://github.com/Nemocas/Nemo.jl) : A computer algebra package for the Julia programming language.
- [OEIS.jl](https://github.com/MurrayT/OEIS.jl) : A basic wrapper to allow access to [OEIS](http://oeis.org/) integer sequences from within Julia.
- [SemiringAlgebra.jl](https://github.com/JuliaComputing/SemiringAlgebra.jl) : [Semiring Algebra](https://dspace.mit.edu/handle/1721.1/115964).

### Boolean Algebra

[Boolean Algebra](https://en.wikipedia.org/wiki/Category:Boolean_algebra)

- [ShowSet.jl](https://github.com/scheinerman/ShowSet.jl) : Nicer output for Set and IntSet objects.

## Numerical Analysis

[Numerical Analysis](https://en.wikipedia.org/wiki/Category:Numerical_analysis)

- [AMD.jl](https://github.com/JuliaSmoothOptimizers/AMD.jl) : Approximate Minimum Degree (AMD) Ordering in Julia.
- [ApproXD.jl](https://github.com/floswald/ApproXD.jl) : B-splines and linear high-dimensional approximators in multiple dimensions for Julia.
- [Dierckx.jl](https://github.com/kbarbary/Dierckx.jl) : Julia package for 1-d and 2-d splines, a wrapper for the dierckx Fortran library.
- [Dualization.jl](https://github.com/jump-dev/Dualization.jl) : Automatic dualization feature for MathOptInterface.jl conic optimization problems.
- [FastGaussQuadrature.jl](https://github.com/JuliaApproximation/FastGaussQuadrature.jl) : A Julia package to compute n-point Gauss quadrature nodes and weights to 16-digit accuracy and in O(n) time.
- [FastTransforms.jl](https://github.com/JuliaApproximation/FastTransforms.jl) : Julia package for fast orthogonal polynomial transforms.
- [GridInterpolations.jl](https://github.com/sisl/GridInterpolations.jl) : Multi-dimensional grid interpolation in arbitrary dimensions on a recti-linear grid.
- [Interpolations.jl](https://github.com/JuliaMath/Interpolations.jl) : Fast, continuous interpolation of discrete datasets in Julia.
- [KNITRO.jl](https://github.com/jump-dev/KNITRO.jl) : Julia interface to the [Knitro](https://www.artelys.com/solvers/knitro/) solver.
- [LinearExpressions.jl](https://github.com/cdsousa/LinearExpressions.jl) : Linear symbolic expressions for the Julia language.
- [NumericalAlgorithms.jl](https://github.com/mrtkp9993/NumericalAlgorithms.jl) : Statistics & Numerical algorithms implemented in Julia.
- [PiecewiseInterpolation.jl](https://github.com/gwater/PiecewiseInterpolation.jl) : A simple interface for interpolations on timeseries with first order discontinuities (using `Dierckx.jl`).
- [RollingFunctions.jl](https://github.com/JeffreySarnoff/RollingFunctions.jl) : Roll a function over data, run a statistic along a `weighted` data window.
- [Simplices.jl](https://github.com/JuliaDynamics/Simplices.jl) : Compute exact simplex intersections in N dimensions.
- [Sobol.jl](https://github.com/stevengj/Sobol.jl) : is a generation of Sobol low-discrepancy sequence (LDS) implementation, that generates **quasi-random** sequences of points in N dimensions which are equally distributed over an N-dimensional hypercube.

## Linear Algebra

[Linear Algebra](https://en.wikipedia.org/wiki/Category:Linear_algebra)

- [Video of Andreas Noack and Jiahao Chen](https://www.youtube.com/channel/UCizxnsw19qcTOdJdIJVtl0Q) speaking at the Linear Algebra and Optimization seminar at the Institute for Computational and Mathematical Engineering at Stanford.
- Learn the [theory of linear algebra](https://github.com/ULAFF/notebooks) in Python Jupyter notebooks.
- [Benchmarking Matrix Multiplication](https://nbviewer.org/url/math.mit.edu/~stevenj/18.335/Matrix-multiplication-experiments.ipynb)

---

- [DirectSum.jl](https://github.com/chakravala/DirectSum.jl) : Abstract tangent bundle vector space type operations.
- [Divergences.jl](https://github.com/gragusa/Divergences.jl) : A Julia package that makes it easy to evaluate divergence measures between two vectors. The package allows calculating the gradient and the diagonal of the Hessian of several divergences which can be used to good effect by the MomentBasedEstimators package.
- [Elemental.jl](https://github.com/JuliaParallel/Elemental.jl) : A Julia interface to the [Elemental linear algebra library](https://github.com/elemental/Elemental) with third-party interfaces.
- [FGenerators.jl](https://github.com/JuliaFolds/FGenerators.jl) : A package for defining `Transducers.jl`-compatible extended foldl with a simple `@yield`-based syntax.
- [GenericLinearAlgebra.jl](https://github.com/JuliaLinearAlgebra/GenericLinearAlgebra.jl> : Partly to extend linear algebra functionality in base to cover generic element types, e.g. `BigFloat` and `Quaternion`, and partly to be a place to experiment with fast linear algebra routines.
- [IncrementalSVD.jl](https://github.com/aaw/IncrementalSVD.jl) : Simon Funk's approach to collaborative filtering using the singular value decomposition, implemented in Julia.
- [IntelVectorMath.jl](https://github.com/JuliaMath/IntelVectorMath.jl) : Julia bindings for the Intel Vector Math Library.
- [IterativeSolvers.jl](https://github.com/JuliaLinearAlgebra/IterativeSolvers.jl) : Iterative algorithms for solving linear systems, eigensystems, and singular value problems.
- [Leibniz.jl](https://github.com/chakravala/Leibniz.jl) : Operator algebras for mixed-symmetry multivariate differentiable tensor fields.
- [LinearMaps.jl](https://github.com/JuliaLinearAlgebra/LinearMaps.jl) : A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
- [LLLplus.jl](https://github.com/christianpeel/LLLplus.jl) : LLL lattice reduction, sphere decoder, and related lattice tools.
- [LMCLUS.jl](https://github.com/wildart/LMCLUS.jl) : Julia's package for Linear Manifold Clustering.
- [MKL.jl](https://github.com/JuliaLinearAlgebra/MKL.jl) : Intel MKL linear algebra backend for Julia.
- [SugarBLAS.jl](https://github.com/lopezm94/SugarBLAS.jl) : Syntactic sugar for BLAS polynomials.
- [TensorCast.jl](https://github.com/mcabbott/TensorCast.jl) :  working with multi-dimensional arrays in index notation.
- [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl) : Julia package for tensor contractions and related operations.
- [Transducers.jl](https://github.com/JuliaFolds/Transducers.jl) : provides composable algorithms on "sequence" of inputs. This feature, available in Clojure language, is a [transformation matrix](https://en.wikipedia.org/wiki/Transformation_matrix) for linear transformations that is now in Julia.
- [VSL.jl](https://github.com/JuliaRandom/VSL.jl) : Julia bindings for the Intel Vector Statistics Library. Requires `MKL.jl`.

### Array Data Structures

- [ArrayInterface.jl](https://github.com/JuliaArrays/ArrayInterface.jl) : Designs for new Base array interface primitives.
- [BlockArrays.jl](https://github.com/JuliaArrays/BlockArrays.jl) : BlockArrays for Julia.
- [CategoricalArrays.jl](https://github.com/JuliaData/CategoricalArrays.jl) : Arrays for working with categorical data (both nominal and ordinal) in Julia.
- [ContinuumArrays.jl](https://github.com/JuliaApproximation/ContinuumArrays.jl) : A package for representing quasi arrays with continuous indices.
- [FastArrays.jl](https://github.com/eschnett/FastArrays.jl) : Multi-dimensional arrays with arbitrary upper and lower bounds that can be fixed at compile time.
- [IndirectArrays.jl](https://github.com/JuliaArrays/IndirectArrays.jl) : Julia implementation of indexed or "lookup" arrays.
- [InfiniteArrays.jl](https://github.com/JuliaArrays/InfiniteArrays.jl) : A Julia package for representing infinite-dimensional arrays.
- [LazyArrays.jl](https://github.com/JuliaArrays/LazyArrays.jl) : Lazy arrays and linear algebra in Julia.
- [LazyGrids.jl](https://github.com/JuliaArrays/LazyGrids.jl) : lazy representation of multi-dimensional grids.
- [MappedArrays.jl](https://github.com/JuliaArrays/MappedArrays.jl) : Lazy in-place transformations of arrays.
- [NamedArrays.jl](https://github.com/davidavdav/NamedArrays.jl) : Julia type that implements a drop-in replacement of Array with named dimensions and Dict-type indexes.
- [NamedAxesArrays.jl](https://github.com/timholy/NamedAxesArrays.jl) : Performant arrays where each axis can be named.
- [OffsetArrays.jl](https://github.com/JuliaArrays/OffsetArrays.jl) : Fortran-like arrays with arbitrary, zero or negative starting indices for arrays in Julia. The main purpose of this package is to simplify translation from Fortran codes intensively using Fortran arrays with negative and zero starting indices, such as the codes accompanying the book Numerical Solution of Hyperbolic Partial Differential Equations by prof. John A. Trangenstein.
- [Pseudospectra.jl](https://github.com/RalphAS/Pseudospectra.jl) : a package for computing pseudospectra of non-symmetric matrices, and plotting them along with eigenvalues ("spectral portraits").
- [QuasiArrays.jl](https://github.com/JuliaApproximation/QuasiArrays.jl) : A package for representing quasi-arrays, viz. arrays with non-classical indexing, including possibly continuous indexing.
- [RandomMatrices.jl](https://github.com/JuliaMath/RandomMatrices.jl) : Random Matrices, extending the `Distributions` package to provide methods for working with matrix-valued random variables.
- [RangeArrays.jl](https://github.com/JuliaArrays/RangeArrays.jl) : Efficient and convenient array data structures where the columns of the arrays are generated (on the fly) by Ranges.
- [ShiftedArrays.jl](https://github.com/JuliaArrays/ShiftedArrays.jl) : Lazy shifted arrays implementation for data analysis in Julia.
- [StaticArrays.jl](https://github.com/JuliaArrays/StaticArrays.jl) : Statically sized arrays for Julia.
- [StrideArrays.jl](https://github.com/JuliaSIMD/StrideArrays.jl) : Library supporting the ArrayInterface.jl strided array interface.
- [StructArrays.jl](https://github.com/JuliaArrays/StructArrays.jl) : Efficient implementation of struct arrays.
- [SuffixArrays.jl](https://github.com/JuliaCollections/SuffixArrays.jl) : Native Julia suffix array implementation.
- [UniqueVectors.jl](https://github.com/garrison/UniqueVectors.jl) : Vectors of unique elements, with quick reverse lookups.
- [Vec.jl](https://github.com/sisl/Vec.jl) : Provides 2D and 3D vector types for vector operations. All types are immutable and are subtypes of `StaticArrays.jl`.

### Matrices

[Wikipedia: Matrix Theory](https://en.wikipedia.org/wiki/Category:Matrix_theory)

> Special Array/Matrix Algorithms, for Array Types, see Data Types section.

- [TSVD.jl](https://github.com/JuliaLinearAlgebra/TSVD.jl) : Truncated singular value decomposition with partial reorthogonalization.
- [AxisAlgorithms.jl](https://github.com/timholy/AxisAlgorithms.jl) : Efficient filtering and linear algebra routines for multidimensional arrays.
- [BandedMatrices.jl](https://github.com/JuliaMatrices/BandedMatrices.jl) : A Julia package for representing banded matrices.
- [CatIndices.jl](https://github.com/JuliaArrays/CatIndices.jl) : Julia package for indices-aware array concatenation and growth.
- [EndpointRanges.jl](https://github.com/JuliaArrays/EndpointRanges.jl) : Julia package for doing arithmetic on endpoints in array indexing.
- [HMatrices.jl](https://github.com/WaveProp/HMatrices.jl) : A Julia library for hierarchical matrices.
- [Kronecker.jl](https://github.com/MichielStock/Kronecker.jl) : A general-purpose toolbox for efficient Kronecker-based algebra that combines lazy evaluation and algebraic tricks such that it can implicitely work with huge matrices. It allows to work with large Kronecker systems both much faster and using much less memory than the naive implementation of the [Kronecker product](https://en.wikipedia.org/wiki/Kronecker_product).
- [KSVD.jl](https://github.com/IshitaTakeshi/KSVD.jl) : K-SVD is an algorithm for creating overcomplete dictionaries for sparse representations.
- [LowRankApprox.jl](https://github.com/JuliaMatrices/LowRankApprox.jl) : Fast low-rank matrix approximation in Julia.
- [MatrixDepot.jl](https://github.com/JuliaMatrices/MatrixDepot.jl) : An Extensible Test Matrix Collection for Julia. [Documentation](https://matrixdepotjl.readthedocs.io/en/latest/)
- [PaddedViews.jl](https://github.com/JuliaArrays/PaddedViews.jl) : Add virtual padding to the edges of an array.
- [PDMats.jl](https://github.com/JuliaStats/PDMats.jl) : Uniform Interface for positive definite matrices of various structures.
- [PositiveFactorizations.jl](https://github.com/timholy/PositiveFactorizations.jl) : Positive-definite (approximations) to matrices.
- [SpecialMatrices.jl](https://github.com/JuliaMatrices/SpecialMatrices.jl) : Julia package for working with special matrix types.
- [ToeplitzMatrices.jl](https://github.com/JuliaMatrices/ToeplitzMatrices.jl) : Fast matrix multiplication and division for Toeplitz matrices in Julia.
- [WoodburyMatrices.jl](https://github.com/timholy/WoodburyMatrices.jl) : Library support for the [Woodbury matrix identity](https://en.wikipedia.org/wiki/Woodbury_matrix_identity).

#### Sparse Matrices

[Wikipedia: Sparse Matrices](https://en.wikipedia.org/wiki/Category:Sparse_matrices)

- [HarwellRutherfordBoeing.jl](https://github.com/JuliaSparse/HarwellRutherfordBoeing.jl) : A Julia Reader for the Harwell-Boeing and Rutherford-Boeing Formats.
- [InteractiveFixedEffectModels.jl](https://github.com/FixedEffects/InteractiveFixedEffectModels.jl) : Estimate factor models on sparse datasets.
- [MatrixMarket.jl](https://github.com/JuliaSparse/MatrixMarket.jl) : A package to read the [MatrixMarket file format](https://math.nist.gov/MatrixMarket/formats.html#MMformat).
- [Metis.jl](https://github.com/JuliaSparse/Metis.jl) : Julia interface to the [Metis](https://github.com/KarypisLab/METIS) graph-partitioning algorithms.
- [MKLSparse.jl](https://github.com/JuliaSparse/MKLSparse.jl) : Override sparse-dense operations when MKL is available.
- [MUMPS.jl](https://github.com/JuliaSmoothOptimizers/MUMPS.jl) : An interface to [MUMPS](https://graal.ens-lyon.fr/MUMPS/index.php?page=home) (a MUltifrontal Massively Parallel sparse direct Solver) to efficiently solve large and sparse linear systems in scientific computing.
- [Pardiso.jl](https://github.com/JuliaSparse/Pardiso.jl) : Calling the [PARDISO](https://www.pardiso-project.org) library from Julia.

### Tensors

- [AbstractTensors.jl](https://github.com/chakravala/AbstractTensors.jl) : Tensor algebra abstract type interoperability with vector bundle parameter.
- [ITensors.jl](https://github.com/ITensor/ITensors.jl) : A Julia library for efficient tensor calculations.
- [Einsum.jl](https://github.com/ahwillia/Einsum.jl) : [Einstein summation notation](https://en.wikipedia.org/wiki/Einstein_notation) in julia.
- [Tullio.jl](https://github.com/mcabbott/Tullio.jl) : Tullio is a very flexible [einsum](https://en.wikipedia.org/wiki/Einstein_notation) macro. A package for writing array operations in index notation.


## Digital signal processing (DSP)

[Wikipedia: DSP](https://en.wikipedia.org/wiki/Digital_signal_processing)

- [DSP.jl](https://github.com/JuliaDSP/DSP.jl) : Filter design, periodograms, window functions, and other digital signal processing functionality.
- [ImageMethodReverb.jl](https://github.com/nantonel/ImageMethodReverb.jl) : Julia implementation of a Room Acoustics Impulse Response Generator using the Randomized Image Method (RIM).
- [MDCT.jl](https://github.com/stevengj/MDCT.jl) : This module computes the modified discrete cosine transform (MDCT) in the Julia language and the inverse transform (IMDCT), using the fast type-IV discrete cosine tranform (DCT-IV) functions in Julia (via FFTW).
- [SortFilters.jl](https://github.com/sairus7/SortFilters.jl) : Fast moving quantile filters implemented as fast moving window sort algorithm.
- [Wavelets.jl](https://github.com/JuliaDSP/Wavelets.jl) : Fast Discrete Wavelet Transforms written in Julia by JuliaDSP.

### Fast Fourier transform (FFT)

[Wikipedia: FFT](https://en.wikipedia.org/wiki/Fast_Fourier_transform)

- [FFTViews.jl](https://github.com/JuliaArrays/FFTViews.jl) : Julia package for fast fourier transforms and periodic views.
- [FFTW.jl](https://github.com/JuliaMath/FFTW.jl) : Julia bindings to the FFTW library for fast Fourier transforms.
- [FourierTools.jl](https://github.com/bionanoimaging/FourierTools.jl) : Tools for working with Fourier space. [JuliaCon 2021 video](https://youtu.be/qYgJDb_Ko2E)
- [HexFFT.jl](https://github.com/gwater/HexFFT.jl) : Fast Fourier transform on hexagonal grids using [Birdsong and Rummelt's algorithm](https://ieeexplore.ieee.org/document/7532670/).
- [NFFT.jl](https://github.com/JuliaMath/NFFT.jl) : Julia implementation of the Non-equidistant Fast Fourier Transform (NFFT).

## Symbolic Computation

See [[modeling-simulation]]

## Polynomials

[Wikipedia: Polynomials](https://en.wikipedia.org/wiki/Category:Polynomials)

- [ChebyshevApprox.jl](https://github.com/RJDennis/ChebyshevApprox.jl) : Julia code to approximate continuous functions using Chebyshev polynomials.
- [CoordinateSplittingPTrees.jl](https://github.com/timholy/CoordinateSplittingPTrees.jl) : Accurate and efficient full-degree multidimensional polynomial interpolation.
- [FastPolynomialRoots.jl](https://github.com/andreasnoack/FastPolynomialRoots.jl) : Fast and backward stable computation of roots of polynomials in Julia.
- [FixedPolynomials.jl](https://github.com/JuliaAlgebra/FixedPolynomials.jl) : A package for really fast evaluation of multivariate polynomials. (No `Porject.toml`)
- [Jacobi.jl](https://github.com/pjabardo/Jacobi.jl) : Jacobi polynomials and Gauss quadrature related functions.
- [MultiPoly.jl](https://github.com/daviddelaat/MultiPoly.jl) : Sparse multivariate polynomials in Julia. (No `Porject.toml`)
- [MultivariatePolynomials.jl](https://github.com/JuliaAlgebra/MultivariatePolynomials.jl) : Multivariate polynomials and multivariate moments.
- [Polynomials.jl](https://github.com/JuliaMath/Polynomials.jl) : Polynomial manipulations and [PolyExt](https://gist.github.com/mathpup/8514578), an extension of Polynomial.jl to support polynomial division, with handy conversions and promotion rules.
- [PolynomialRoots.jl](https://github.com/giordano/PolynomialRoots.jl) : Fast complex polynomial root finder, with support for arbitrary precision calculations
- [Remez.jl](https://github.com/simonbyrne/Remez.jl) : [Remez algorithm](https://en.wikipedia.org/wiki/Remez_algorithm) for computing minimax polynomial approximations.
- [SemialgebraicSets.jl](https://github.com/JuliaAlgebra/SemialgebraicSets.jl) : Extension of MultivariatePolynomials to semialgebraic sets.
- [TaylorModels.jl](https://github.com/JuliaIntervals/TaylorModels.jl) : A numerical mathematics package to treat the high-order scaling property of the remainder bound interval in a Taylor polynomial. [📹 JuliaCon 2018](https://youtu.be/o1h7BUW04NI).

## Functions

[Wikipedia: Functions](https://en.wikipedia.org/wiki/Category:Types_of_functions)

> Evaluation and approximations of functions

- <https://github.com/JuliaApproximation/ApproxFun.jl> : Julia package for function approximation.
- <https://github.com/JuliaApproximation/BasisFunctions.jl> : A collection of routines for working with a number of standard basis functions. For more complete software packages to manipulate numerical function approximations, please consider ApproxFun.
- <https://github.com/nolta/Elliptic.jl> : Elliptic integral and Jacobi elliptic special functions.
- <https://github.com/JuliaApproximation/FrameFun.jl> : Exploring practical possibilities of approximating functions with frames rather than with a basis.
- <https://github.com/jlapeyre/LambertW.jl> : A package implementing the Lambert_W function and associated omega constant.
- <https://github.com/JuliaMath/SpecialFunctions.jl> : Special mathematical functions in Julia.
- <https://github.com/gwater/Struve.jl> : [Struve](https://dlmf.nist.gov/11) functions for Julia.

## Calculus

- [Riemann Hypothesis book](https://wstein.org/rh/) with the [source code on github](https://github.com/williamstein/rh).
- [Calculus With Julia](https://github.com/CalculusWithJulia/CalculusWithJulia.github.io) : Introductory Calculus with the Julia Programming Language.
- An IJulia notebook showing [Taylor's method integration of the pendulum](https://nbviewer.org/gist/lbenet/616fa81f3c12c9cfcf97).

---

- [Calculus.jl](https://github.com/JuliaMath/Calculus.jl) : Calculus package.
- [Cuba.jl](https://github.com/giordano/Cuba.jl) : Library for multidimensional numerical integration with the [Cuba library](https://www.feynarts.de/cuba/).
- [Cubature.jl](https://github.com/JuliaMath/Cubature.jl) : One- and multi-dimensional adaptive integration routines for the Julia language.
- [FastGaussQuadrature.jl](https://github.com/JuliaApproximation/FastGaussQuadrature.jl) : Computes Gauss quadrature rules to 16-digit precision (so far Legendre, Jacobi, Lobatto, Radau).
- [FiniteDiff.jl](https://github.com/JuliaDiff/FiniteDiff.jl) : Fast non-allocating calculations of gradients, Jacobians, and Hessians with sparsity support.
- [FiniteDifferences.jl](https://github.com/JuliaDiff/FiniteDifferences.jl) : estimating derivatives with [finite differences](https://en.wikipedia.org/wiki/Finite_difference).
- [FractionalCalculus.jl](https://github.com/SciFracX/FractionalCalculus.jl) : High performance and high precision numerical [fractional calculus](https://en.wikipedia.org/wiki/Fractional_calculus) computing.
- [HCubature.jl](https://github.com/JuliaMath/HCubature.jl) : Pure-Julia multidimensional h-adaptive integration.
- [Integrals.jl](https://github.com/SciML/Integrals.jl) : A common interface for quadrature and numerical integration.
- [RiemannComplexNumbers.jl](https://github.com/scheinerman/RiemannComplexNumbers.jl) : The RiemannComplexNumbers module is an alternative Complex type for Julia (with a single complex infinity value).
- [Roots.jl](https://github.com/JuliaMath/Roots.jl) : Root finding functions for Julia.
- [TaylorSeries.jl](https://github.com/JuliaDiff/TaylorSeries.jl) : A julia package for Taylor expansions in one independent variable.
- [WiltonInts84.jl](https://github.com/krcools/WiltonInts84.jl) : Integrals of arbitrary powers of R over flat triangles.

### Automatic Differentiation

- [ChainRules.jl](https://github.com/JuliaDiff/ChainRules.jl) : forward and reverse mode automatic differentiation primitives.
- [Diffractor.jl](https://github.com/JuliaDiff/Diffractor.jl) : An experimental next-generation, compiler-based AD system for Julia.
- [DualNumbers.jl](https://github.com/JuliaDiff/DualNumbers.jl) : Julia package for representing dual numbers and for performing dual algebra.
- [Enzyme.jl](https://github.com/EnzymeAD/Enzyme.jl) : Julia bindings for the [Enzyme](https://github.com/wsmoses/enzyme) automatic differentiator. The Enzyme project is a tool for performing reverse-mode automatic differentiation (AD) of statically-analyzable LLVM IR.
- [ForwardDiff.jl](https://github.com/JuliaDiff/ForwardDiff.jl) : Forward Mode Automatic Differentiation for Julia.
- [HyperDualNumbers.jl](https://github.com/JuliaDiff/HyperDualNumbers.jl) : Hyper-Dual Numbers for Exact Second-Derivative Calculations, is structured similar to the DualNumbers package, which aims for complete support for HyperDual types for numerical functions within Julia's Base. Currently, basic mathematical operations and trigonometric functions are supported.
- [ReverseDiff.jl](https://github.com/JuliaDiff/ReverseDiff.jl) : Reverse Mode Automatic Differentiation for Julia.
- [ReverseDiffSparse.jl](https://github.com/mlubin/ReverseDiffSparse.jl) : Hessian algorithmic differentiation to compute hessian sparsity pattern.
- [Yota.jl](https://github.com/dfdx/Yota.jl) : Reverse-mode automatic differentiation for static and dynamic graphs.
- [Zygote.jl](https://github.com/FluxML/Zygote.jl) : Source-to-source automatic differentiation (AD) in Julia, and is the next-gen AD system for the Flux differentiable programming framework.
- [StochasticAD.jl](https://github.com/gaurav-arya/StochasticAD.jl) : automatic differentiation of programs containing discrete randomness. [JuliaCon 2023 video](https://www.youtube.com/watch?v=_irOyB1ODvM)

## Mathematical Analysis

[Wikipedia: Mathematical Analysis](https://en.wikipedia.org/wiki/Category:Mathematical_analysis)

- [Complementarity.jl](https://github.com/chkwon/Complementarity.jl) : This package provides a modeling and computational interface for solving [Mixed Complementarity Problems (MCP)](https://en.wikipedia.org/wiki/Mixed_complementarity_problem), modeling by `JuMP.jl` and computing by `PATHSolver.jl`.
- [Fatou.jl](https://github.com/chakravala/Fatou.jl) : Fatou sets in Julia (Fractals, Newton basins, Mandelbrot).
- [PATHSolver.jl](https://github.com/chkwon/PATHSolver.jl) : This package provides a Julia wrapper of the PATH Solver for solving _linear_ Mixed Complementarity Problems (MCP).
- [Wilkinson.jl](ttps://github.com/chakravala/Wilkinson.jl) : Toolkit for studying numerical analysis and floating point algebra round-off error in Julia.

## Discrete math

- [Wikipedia: Discrete math](https://en.wikipedia.org/wiki/Category:Discrete_mathematics)
- [Wikipedia: Combinatorics](https://en.wikipedia.org/wiki/Category:Combinatorics)

---

- [Collatz.jl](https://github.com/StefanKarpinski/Collatz.jl) : The [Collatz conjecture](https://en.wikipedia.org/wiki/Collatz_conjecture).
- [PermPlain.jl](https://github.com/jlapeyre/PermPlain.jl) : Permutations of integers.
- [Permutations.jl](https://github.com/scheinerman/Permutations.jl) : Permutations class for Julia.
- [SimplePosets.jl](https://github.com/scheinerman/SimplePosets.jl) : Simple partially ordered sets for Julia.
- [ZChop.jl](https://github.com/jlapeyre/ZChop.jl) : Replaces small numbers with zero.

### Graph Theory

See [[graph]].

## Information theory

[Wikipedia: Information theory](https://en.wikipedia.org/wiki/Information_theory)

- [InformationMeasures.jl](https://github.com/Tchanders/InformationMeasures.jl) : Entropy, mutual information and higher order measures from information theory, with various estimators and discretisation methods.
