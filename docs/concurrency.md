---
title: Concurrency
---

- Julia HPC and Cluster computing.
- Distributed Computing and Grid computing.
- Cloud computing
- Parallel computing
- Hardware architectures (ARM, CUDA, GPU, MIPS) anb compute kernels

## Organizations

- [Julia Parallel](https://github.com/JuliaParallel)
- [Julia Folds](https://github.com/JuliaFolds)
- [Julia Cloud](https://github.com/JuliaCloud)

## Resources

- [Julia manual for parallel computing](https://docs.julialang.org/en/v1/manual/parallel-computing/)
- [Wikipedia: Concurrency](https://en.wikipedia.org/wiki/Concurrency_%28computer_science%29)
- [Wikipedia: Parallel Computing](https://en.wikipedia.org/wiki/Category:Parallel_computing)

---

## General Concurrency Packages

- [Actors.jl](https://github.com/JuliaActors/Actors.jl) : [Actor Model](https://en.wikipedia.org/wiki/Actor_model) cocurrent model.
- [FLoops.jl](https://github.com/JuliaFolds/FLoops.jl): the macro `@floop` for a fast generic iteration over complex collections.
- [Folds.jl](https://github.com/JuliaFolds/Folds.jl) : A unified interface for sequential, threaded, and distributed folds. The [docs](https://juliafolds.github.io/Folds.jl/stable/) list what functions it supports.
- [TiledIteration.jl](https://github.com/JuliaArrays/TiledIteration.jl) : Julia package to facilitate writing mulithreaded, multidimensional, cache-efficient code.
- [MessageUtils.jl](https://github.com/JuliaParallel/MessageUtils.jl) : A collection of utilities for messaging.

## Bindings

- [AppleAccelerate.jl](https://github.com/JuliaLinearAlgebra/AppleAccelerate.jl) : Julia interface to [OS X's Accelerate framework](https://developer.apple.com/library/mac/documentation/Accelerate/Reference/AccelerateFWRef/).
- [ArrayFire.jl](https://github.com/JuliaGPU/ArrayFire.jl) : Julia Wrapper for the [ArrayFire](https://arrayfire.com/) library.
- [Elly.jl](https://github.com/JuliaParallel/Elly.jl) : [Hadoop](https://hadoop.apache.org/) HDFS and Yarn client.
- [Hwloc.jl](https://github.com/JuliaParallel/Hwloc.jl) : Wrapper to the [hwloc library](https://www.open-mpi.org/projects/hwloc/) to provide a portable abstraction (across OS, versions, architectures, ...) of the hierarchical topology of modern architectures, including NUMA memory nodes, sockets, shared caches, cores and simultaneous multithreading.

### Cloud computing

- [AWS.jl](https://github.com/JuliaCloud/AWS.jl) : supports the EC2 and S3 API's, letting you start and stop EC2 instances dynamically.
- [AWSCore.jl](https://github.com/JuliaCloud/AWSCore.jl) : [Amazon Web Services](https://aws.amazon.com/) Core Functions and Types.
- [AWSS3.jl](https://github.com/JuliaCloud/AWSS3.jl) : AWS S3 Simple Storage Service interface for Julia.
- [GoogleCloud.jl](https://github.com/JuliaCloud/GoogleCloud.jl) : Google Cloud APIs for Julia.
- [Kuber.jl](https://github.com/JuliaComputing/Kuber.jl) : Julia Kubernetes Client.

## SIMD Computing

- [Wikipedia: SIMD Computing](https://en.wikipedia.org/wiki/Category:SIMD_computing).
- [Julia docs: `@simd`](https://docs.julialang.org/en/v1/base/base/#Base.SimdLoop.@simd) macro.

---

- [LoopVectorization.jl](https://github.com/JuliaSIMD/LoopVectorization.jl) : vectorize your for loop using the `@turbo` macro.
- [SIMD.jl](https://github.com/eschnett/SIMD.jl) : Explicit SIMD vector operations for Julia.

## Multi-Threading

- [ThreadsX.jl](https://github.com/tkf/ThreadsX.jl) : Multithreaded base functions such as `map()`, `reduce()`, `foreach()`.
- [ThreadPinning.jl](https://github.com/carstenbauer/ThreadPinning.jl) : Pin Julia threads to CPU processors. Requires `lscpu` command (in virtually all Linux systems). [JuliaCon 2023](https://www.youtube.com/watch?v=6Whc9XtlCC0)

## Multiprocessing and Distributed Computing

- [Wikipedia: Distributed Computing](https://en.wikipedia.org/wiki/Category:Distributed_computing) across multiple compute nodes.
- [Wikipedia: Job Scheduler](https://en.wikipedia.org/wiki/Job_scheduler)
- [Julia at scale](https://discourse.julialang.org/c/domain/parallel/34) topic on discourse.
- [FARMTest.jl](https://github.com/magerton/FARMTest.jl) : Simple example scripts for running Julia on a SLURM, using [SlurmClusterManager.jl](https://github.com/kleinhenz/SlurmClusterManager.jl).

---

- [MPI.jl](https://github.com/JuliaParallel/MPI.jl) :  Julia interface to the Message Passing Interface ([MPI](https://www.mpi-forum.org/))
- [Dagger.jl](https://github.com/JuliaParallel/Dagger.jl) : A framework for out-of-core and parallel computation and hierarchical Scheduling of DAG Structured Computations. Similar to [`dask`](https://www.dask.org/) library in Python.
- [DistributedArrays.jl](https://github.com/JuliaParallel/DistributedArrays.jl) : A task persistency mechanism based on hash-graphs for Dispatcher.jl.
- [ClusterManagers.jl](https://github.com/JuliaParallel/ClusterManagers.jl) : Support for different clustering technologies.
- [DispatcherCache.jl](https://github.com/zgornel/DispatcherCache.jl) : Tool for building and executing a computation graph given a series of dependent operations.
- [ParallelDataTransfer.jl](https://github.com/ChrisRackauckas/ParallelDataTransfer.jl) : A bunch of helper functions for transferring data between worker processes.
- [Persist.jl](https://github.com/eschnett/Persist.jl) : Running jobs in the background, independent of the Julia shell.
- [Schedulers.jl](https://github.com/ChevronETC/Schedulers.jl) : It provides elastic and fault tolerant parallel map and parallel map reduce methods. The primary feature that distinguishes Schedulers parallel `map` method from Julia's `Distributed.pmap()` is elasticity where the cluster is permitted to dynamically grow/shrink.

## GPU computing

- [Wikipedia: GPGPU](https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units)
- Sample notebooks for [GPU Julia](https://nbviewer.org/7436359), and [GPU Transpose](https://nbviewer.org/gist/jakebolewski/7436439).
- Blog post on [High-Performance GPU Computing](https://developer.nvidia.com/blog/gpu-computing-julia-programming-language/#more-8555) in the Julia Programming Language.

---

- [AMDGPU.jl](https://github.com/JuliaGPU/AMDGPU.jl) : AMD GPU (ROCm) programming in Julia.
- [ArrayFire.jl](https://github.com/JuliaGPU/ArrayFire.jl) : Julia Wrapper for the [ArrayFire](https://arrayfire.com/) library.
- [CVortex.jl](https://github.com/hjabird/CVortex.jl) : Julia wrapper for [cvortex](https://github.com/hjabird/cvortex) GPU accelerated vortex filament and vortex particle methods.

### NVIDIA CUDA

- [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl) : CUDA programming in Julia. See also [JuliaCon 2021 video](https://youtu.be/fw0R5G8pB0U).
- [CuCountMap.jl](https://github.com/xiaodaigh/CuCountMap.jl) : Fast `StatsBase.countmap` for small types on the GPU via `CUDA.jl`
- [FoldsCUDA.jl](https://github.com/JuliaFolds/FoldsCUDA.jl) : provides `Transducers.jl`-compatible fold (reduce) implemented using `CUDA.jl`. This brings the transducers and reducing function combinators implemented in Transducers.jl to GPU. Furthermore, using FLoops.jl, you can write parallel for loops that run on GPU.
- [NVTX.jl](https://github.com/JuliaGPU/NVTX.jl) : Julia bindings for [NVTX](https://nvidia.github.io/NVTX/doxygen/index.html), for instrumenting with the [Nvidia Nsight Systems profiler](https://developer.nvidia.com/nsight-systems). [JuliaCon 2023 video](https://www.youtube.com/watch?v=B7ZlScN_rk8).
