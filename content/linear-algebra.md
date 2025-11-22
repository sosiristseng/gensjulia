---
Created: 2025-11-22, 15:16:27
Modified: 2025-11-22, 16:17:21
title: Linear Algebra
aliases:
  - Linear Algebra
---
# Linear Algebra

[Linear Algebra](https://en.wikipedia.org/wiki/Category:Linear_algebra)

- [Video of Andreas Noack and Jiahao Chen](https://www.youtube.com/channel/UCizxnsw19qcTOdJdIJVtl0Q) speaking at the Linear Algebra and Optimization seminar at the Institute for Computational and Mathematical Engineering at Stanford.
- Learn the [theory of linear algebra](https://github.com/ULAFF/notebooks) in Python Jupyter notebooks.
- [Benchmarking Matrix Multiplication](https://nbviewer.org/url/math.mit.edu/~stevenj/18.335/Matrix-multiplication-experiments.ipynb)

---

- [Linear Algebra stdlib in Julia](https://docs.julialang.org/en/v1/stdlib/LinearAlgebra/)
- [DirectSum.jl](https://github.com/chakravala/DirectSum.jl) : Abstract tangent bundle vector space type operations.
- [Divergences.jl](https://github.com/gragusa/Divergences.jl) : A Julia package that makes it easy to evaluate divergence measures between two vectors. The package allows calculating the gradient and the diagonal of the Hessian of several divergences which can be used to good effect by the MomentBasedEstimators package.
- [Elemental.jl](https://github.com/JuliaParallel/Elemental.jl) : A Julia interface to the [Elemental linear algebra library](https://github.com/elemental/Elemental) with third-party interfaces.
- [GenericLinearAlgebra.jl](https://github.com/JuliaLinearAlgebra/GenericLinearAlgebra.jl) : Partly to extend linear algebra functionality in base to cover generic element types, e.g. `BigFloat` and `Quaternion`, and partly to be a place to experiment with fast linear algebra routines.
- [IntelVectorMath.jl](https://github.com/JuliaMath/IntelVectorMath.jl) : Julia bindings for the [Intel Vector Math Library](https://www.intel.com/content/www/us/en/develop/documentation/onemkl-developer-reference-c/top/vector-mathematical-functions.html).
- [IterativeSolvers.jl](https://github.com/JuliaLinearAlgebra/IterativeSolvers.jl) : Iterative algorithms for solving linear systems, eigen systems, and singular value problems.
- [LinearMaps.jl](https://github.com/JuliaLinearAlgebra/LinearMaps.jl) : A Julia package for defining and working with linear maps, also known as linear transformations or linear operators acting on vectors. The only requirement for a LinearMap is that it can act on a vector (by multiplication) efficiently.
- [LLLplus.jl](https://github.com/christianpeel/LLLplus.jl) : LLL lattice reduction, sphere decoder, and related lattice tools.
- [MKL.jl](https://github.com/JuliaLinearAlgebra/MKL.jl) : Intel [MKL](https://en.wikipedia.org/wiki/Math_Kernel_Library) linear algebra backend for Julia.
- [PartitionedArrays.jl](https://github.com/fverdugo/PartitionedArrays.jl) : distributed (a.k.a. partitioned) vectors and sparse matrices in Julia. It can be used for parallel algebraic multigrid (AMG) to solve PDE problems. [JuliaCon 2024 video](https://youtu.be/SRTP_STlGSk)
- [VSL.jl](https://github.com/JuliaRandom/VSL.jl) : Julia bindings for the Intel Vector Statistics Library. Requires `MKL.jl`.
## Array Data Structures

See also [[algorithm-data-structure]].

- [ArrayInterface.jl](https://github.com/JuliaArrays/ArrayInterface.jl) : Designs for new Base array interface primitives.
- [BlockArrays.jl](https://github.com/JuliaArrays/BlockArrays.jl) : BlockArrays for Julia.
- [CategoricalArrays.jl](https://github.com/JuliaData/CategoricalArrays.jl) : Arrays for working with categorical data (both nominal and ordinal) in Julia.
- [ComponentArrays.jl](https://github.com/jonniedie/ComponentArrays.jl) : Arrays with arbitrarily nested named components.
- [ContinuumArrays.jl](https://github.com/JuliaApproximation/ContinuumArrays.jl) : A package for representing quasi arrays with continuous indices.
- [DiskArrays.jl](https://github.com/meggart/DiskArrays.jl) : Accessing array data on slower media (e.g., hard disk).
- [IndirectArrays.jl](https://github.com/JuliaArrays/IndirectArrays.jl) : Julia implementation of indexed or "lookup" arrays.
- [InfiniteArrays.jl](https://github.com/JuliaArrays/InfiniteArrays.jl) : A Julia package for representing infinite-dimensional arrays.
- [LabelledArrays.jl](https://github.com/SciML/LabelledArrays.jl) : Arrays with a label for each element.
- [LazyArrays.j](https://github.com/JuliaArrays/LazyArrays.jl) : Lazy arrays and linear algebra in Julia.
- [LazyGrids.jl](https://github.com/JuliaArrays/LazyGrids.jl) : lazy representation of multi-dimensional grids.
- [MappedArrays.jl](https://github.com/JuliaArrays/MappedArrays.jl) : Lazy in-place transformations of arrays.
- [NamedArrays.jl](https://github.com/davidavdav/NamedArrays.jl) : Julia type that implements a drop-in replacement of Array with named dimensions and Dict-type indexes.
- [OffsetArrays.jl](https://github.com/JuliaArrays/OffsetArrays.jl) : Fortran-like arrays with arbitrary, zero or negative starting indices.
- [QuasiArrays.jl](https://github.com/JuliaApproximation/QuasiArrays.jl) : A package for representing quasi-arrays, viz. arrays with non-classical indexing, including possibly continuous indexing.
- [RandomMatrices.jl](https://github.com/JuliaMath/RandomMatrices.jl) : Random Matrices, extending the `Distributions` package to provide methods for working with matrix-valued random variables.
- [RangeArrays.jl](https://github.com/JuliaArrays/RangeArrays.jl) : Efficient and convenient array data structures where the columns of the arrays are generated (on the fly) by Ranges.
- [RecursiveArrayTools.jl](https://github.com/SciML/RecursiveArrayTools.jl) : Tools for easily handling nesting array objects like arrays of arrays.
- [ShiftedArrays.jl](https://github.com/JuliaArrays/ShiftedArrays.jl) : Lazy shifted arrays implementation for data analysis in Julia.
- [StaticArrays.jl](https://github.com/JuliaArrays/StaticArrays.jl) : Statically sized arrays for Julia.
- [StrideArrays.jl](https://github.com/JuliaSIMD/StrideArrays.jl) : Library supporting the ArrayInterface.jl strided array interface.
- [StructArrays.jl](https://github.com/JuliaArrays/StructArrays.jl) : Efficient implementation of struct arrays.
- [SuffixArrays.j](https://github.com/JuliaCollections/SuffixArrays.jl) : Native Julia suffix array implementation.
- [UniqueVectors.jl](https://github.com/garrison/UniqueVectors.jl) : Vectors of unique elements, with quick reverse lookups.
- [Vec.jl](https://github.com/sisl/Vec.jl) : Provides 2D and 3D vector types for vector operations. All types are immutable and are subtypes of `StaticArrays.jl`.
### Matrices

[Wikipedia: Matrix Theory](https://en.wikipedia.org/wiki/Category:Matrix_theory)

> Special Array/Matrix Algorithms, for Array Types, see Data Types section.

- [AxisAlgorithms.jl](https://github.com/timholy/AxisAlgorithms.jl) : Efficient filtering and linear algebra routines for multidimensional arrays.
- [BandedMatrices.j](https://github.com/JuliaMatrices/BandedMatrices.jl) : A Julia package for representing banded matrices.
- [CatIndices.jl](https://github.com/JuliaArrays/CatIndices.jl) : Julia package for indices-aware array concatenation and growth.
- [EndpointRanges.jl](https://github.com/JuliaArrays/EndpointRanges.jl) : Julia package for doing arithmetic on endpoints in array indexing.
- [HMatrices.jl](https://github.com/WaveProp/HMatrices.jl) : A Julia library for hierarchical matrices.
- [IncrementalSVD.jl](https://github.com/aaw/IncrementalSVD.jl) : Simon Funk's approach to collaborative filtering using the singular value decomposition, implemented in Julia.
- [Kronecker.jl](https://github.com/MichielStock/Kronecker.jl) : efficiently work with Kronecker products.
- [KSVD.jl](https://github.com/RomeoV/KSVD.jl) : K-SVD is an algorithm for creating over-complete dictionaries for sparse representations. [JuliaCon 2024 video](https://www.youtube.com/watch?v=N3QxTTAp9Xo)
- [LowRankApprox.jl](https://github.com/JuliaMatrices/LowRankApprox.jl) : Fast low-rank matrix approximation in Julia.
- [MatrixDepot.jl](https://github.com/JuliaMatrices/MatrixDepot.jl) : An Extensible Test Matrix Collection for Julia. [Documentation](https://matrixdepotjl.readthedocs.io/en/latest/)
- [PaddedViews.jl](https://github.com/JuliaArrays/PaddedViews.jl) : Add virtual padding to the edges of an array.
- [PDMats.jl](https://github.com/JuliaStats/PDMats.jl) : Uniform Interface for positive definite matrices of various structures.
- [PositiveFactorizations.jl](https://github.com/timholy/PositiveFactorizations.jl) : Positive-definite (approximations) to matrices.
- [Pseudospectra.jl](https://github.com/RalphAS/Pseudospectra.jl) : a package for computing pseudospectra of non-symmetric matrices, and plotting them along with eigenvalues ("spectral portraits").
- [RandomizedDiagonalEstimation.jl](https://github.com/niclaspopp/RandomizedDiagonalEstimation.jl) : randomized diagonal estimation of matrices and matrix functions. [JuliaCon 2024 video](https://youtu.be/ly8S1NjbaK0)
- [SpecialMatrices.j](https://github.com/JuliaMatrices/SpecialMatrices.jl) : Julia package for working with special matrix types.
- [ToeplitzMatrices.jl](https://github.com/JuliaMatrices/ToeplitzMatrices.jl) : Fast matrix multiplication and division for Toeplitz matrices in Julia.
- [TSVD.jl](https://github.com/JuliaLinearAlgebra/TSVD.jl) : Truncated singular value decomposition with partial reorthogonalization.
- [WoodburyMatrices.jl](https://github.com/timholy/WoodburyMatrices.jl) : Library support for the [Woodbury matrix identity](https://en.wikipedia.org/wiki/Woodbury_matrix_identity).

#### Sparse Matrices

- [Wikipedia: Sparse Matrices](https://en.wikipedia.org/wiki/Category:Sparse_matrices)
- [Sparse matrices in Julia stdlib](https://docs.julialang.org/en/v1/stdlib/SparseArrays/)

---

- [InteractiveFixedEffectModels.jl](https://github.com/FixedEffects/InteractiveFixedEffectModels.jl) : Estimate factor models on sparse datasets.
- [MUMPS.jl](https://github.com/JuliaSmoothOptimizers/MUMPS.jl) : An interface to MUMPS, a libray for the solution of sparse linear systems on multicore computers.
- [HarwellRutherfordBoeing.jl](https://github.com/JuliaSparse/HarwellRutherfordBoeing.jl) : A Julia Reader for the Harwell-Boeing and Rutherford-Boeing Formats.
- [MatrixMarket.jl](https://github.com/JuliaSparse/MatrixMarket.jl) : A package to read the [MatrixMarket file format](https://math.nist.gov/MatrixMarket/formats.html#MMformat).
- [Metis.jl](https://github.com/JuliaSparse/Metis.jl) : Julia interface to the [Metis](https://github.com/KarypisLab/METIS) graph-partitioning algorithms.
- [MKLSparse.j](https://github.com/JuliaSparse/MKLSparse.jl) : Override sparse-dense operations when `MKL.jl` is available.
- [Pardiso.jl](https://github.com/JuliaSparse/Pardiso.jl) : Calling the [PARDISO](https://www.pardiso-project.org) library from Julia.
### Tensors

- [AbstractTensors.jl](https://github.com/chakravala/AbstractTensors.jl) : Tensor algebra abstract type interoperability with vector bundle parameter.
- [Finch.jl](https://github.com/willow-ahrens/Finch.jl) : Finch is a cutting-edge Julia-to-Julia compiler specially designed for optimizing loop nests over sparse or structured multidimensional arrays.
- [ITensors.jl](https://github.com/ITensor/ITensors.jl) : A Julia library for efficient tensor calculations.
- [Leibniz.jl](https://github.com/chakravala/Leibniz.jl) : Operator algebras for mixed-symmetry multivariate differentiable tensor fields.
- [TensorCast.jl](https://github.com/mcabbott/TensorCast.jl) :  working with multi-dimensional arrays in index notation.
- [TensorOperations.jl](https://github.com/Jutho/TensorOperations.jl) : Fast tensor operations using a convenient Einstein index notation.
- [Tullio.jl](https://github.com/mcabbott/Tullio.jl) : A very flexible [einsum](https://en.wikipedia.org/wiki/Einstein_notation) macro. A package for writing array operations in index notation.