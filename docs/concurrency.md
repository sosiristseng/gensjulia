---
title: Concurrency
---

> - Julia HPC and Cluster computing.
> - Distributed Computing and Grid computing.
> - Cloud computing
> - Parallel computing
> - Hardware architectures (ARM, CUDA, GPU, MIPS) anb compute kernels

- [Julia Parallel](https://github.com/JuliaParallel) organization
- [Julia Folds](https://github.com/JuliaFolds) organization
- [Julia Folds2](https://github.com/JuliaFolds2) organization
- [Julia Cloud](https://github.com/JuliaCloud) organization

---

- [Julia manual for parallel computing](https://docs.julialang.org/en/v1/manual/parallel-computing/)
- [Wikipedia: Concurrency](https://en.wikipedia.org/wiki/Concurrency_%28computer_science%29)
- [Wikipedia: Parallel Computing](https://en.wikipedia.org/wiki/Category:Parallel_computing)

## General Concurrency Packages

- https://github.com/JuliaActors/Actors.jl : [Actor Model](https://en.wikipedia.org/wiki/Actor_model) concurrent model.
- https://github.com/JuliaArrays/TiledIteration.jl : Julia package to facilitate writing multithreaded, multidimensional, cache-efficient code.
- https://github.com/JuliaFolds2/FLoops.jl : the macro `@floop`, a superset of `Threads.@threads`, for a fast generic for loop iteration over complex collections.
- https://github.com/JuliaFolds2/Folds.jl : A unified interface for sequential, threaded, and distributed folds.
- https://github.com/JuliaParallel/MessageUtils.jl : A collection of utilities for messaging.

## Bindings to external libraries

- https://github.com/JuliaGPU/ArrayFire.jl : Julia Wrapper for the [ArrayFire](https://arrayfire.com/) library.
- https://github.com/JuliaLinearAlgebra/AppleAccelerate.jl : Julia interface to [OS X's Accelerate framework](https://developer.apple.com/library/mac/documentation/Accelerate/Reference/AccelerateFWRef/).
- https://github.com/JuliaParallel/Elly.jl : [Hadoop](https://hadoop.apache.org/) HDFS and Yarn client.
- https://github.com/JuliaParallel/Hwloc.jl : Wrapper to the [hwloc library](https://www.open-mpi.org/projects/hwloc/) to provide a portable abstraction (across OS, versions, architectures, ...) of the hierarchical topology of modern architectures, including NUMA memory nodes, sockets, shared caches, cores and simultaneous multithreading.

### Cloud computing

- https://github.com/JuliaCloud/AWS.jl : supports the EC2 and S3 API's, letting you start and stop EC2 instances dynamically.
- https://github.com/JuliaCloud/AWSCore.jl : [Amazon Web Services](https://aws.amazon.com/) Core Functions and Types.
- https://github.com/JuliaCloud/AWSS3.jl : AWS S3 Simple Storage Service interface for Julia.
- https://github.com/JuliaCloud/GoogleCloud.jl : Google Cloud APIs for Julia.
- https://github.com/JuliaComputing/Kuber.jl : Julia Kubernetes Client.

## SIMD Computing

- [Wikipedia: SIMD Computing](https://en.wikipedia.org/wiki/Category:SIMD_computing).
- [Julia docs: `@simd`](https://docs.julialang.org/en/v1/base/base/#Base.SimdLoop.@simd) macro.

---

- https://github.com/eschnett/SIMD.jl : Explicit SIMD vector operations for Julia.
- https://github.com/JuliaSIMD/LoopVectorization.jl : vectorize for loops using the `@turbo` macro.

## Multi-Threading

- [Julia manual for multi-threading](https://docs.julialang.org/en/v1/manual/multi-threading/)

- https://github.com/carstenbauer/ThreadPinning.jl : Pin Julia threads to CPU processors. Requires the `lscpu` command (Linux systems). [JuliaCon 2023](https://www.youtube.com/watch?v=6Whc9XtlCC0)
- https://github.com/JuliaFolds2/OhMyThreads.jl : Simple multithreading in julia.

## Multiprocessing and Distributed Computing

- [Wikipedia: Distributed Computing](https://en.wikipedia.org/wiki/Category:Distributed_computing) across multiple compute nodes.
- [Wikipedia: Job Scheduler](https://en.wikipedia.org/wiki/Job_scheduler)
- [Julia at scale](https://discourse.julialang.org/c/domain/parallel/34) topic on discourse.

---

- https://github.com/ChevronETC/Schedulers.jl : It provides elastic and fault tolerant parallel map and parallel map reduce methods.
- https://github.com/ChrisRackauckas/ParallelDataTransfer.jl : A bunch of helper functions for transferring data between worker processes.
- https://github.com/eschnett/Persist.jl : Running jobs in the background, independent of the Julia shell.
- https://github.com/JuliaParallel/ClusterManagers.jl : Support for different job queue systems commonly used on compute clusters. (e.g., Slurm, K8s, )
- https://github.com/JuliaParallel/Dagger.jl : A framework for out-of-core and parallel computation and hierarchical Scheduling of DAG Structured Computations. Similar to [`dask`](https://www.dask.org/) library in Python.
- https://github.com/JuliaParallel/DistributedArrays.jl : A task persistency mechanism based on hash-graphs for Dispatcher.jl.
- https://github.com/JuliaParallel/MPI.jl :  Julia interface to the Message Passing Interface ([MPI](https://www.mpi-forum.org/))
- https://github.com/JuliaPluto/Malt.jl : a multiprocessing package for Julia. It is used by https://github.com/fonsp/Pluto.jl to manage the Julia process that notebook code is executed in, as a replacement to Distributed.
- https://github.com/kleinhenz/SlurmClusterManager.jl : julia package for running code on slurm clusters. See https://github.com/magerton/FARMTest.jl for simple example scripts.
- https://github.com/zgornel/DispatcherCache.jl : Tool for building and executing a computation graph given a series of dependent operations.
- https://github.com/beacon-biosignals/K8sClusterManagers.jl : A Julia cluster manager for Kubernetes.


## GPU computing

- [Wikipedia: GPGPU](https://en.wikipedia.org/wiki/General-purpose_computing_on_graphics_processing_units)
- [Sample OpenCL notebooks for GPU Julia](https://nbviewer.org/7436359), and [GPU Transpose](https://nbviewer.org/gist/jakebolewski/7436439).
- Blog post on [High-Performance GPU Computing](https://developer.nvidia.com/blog/gpu-computing-julia-programming-language/#more-8555) in the Julia Programming Language.

---

- https://github.com/JuliaGPU/AMDGPU.jl : AMD GPU (ROCm) programming in Julia.
- https://github.com/JuliaGPU/ArrayFire.jl : Julia Wrapper for the [ArrayFire](https://arrayfire.com/) library.
- https://github.com/JuliaGPU/GPUArrays.jl : Reusable array functionality for Julia's various GPU backends.
- https://github.com/JuliaGPU/oneAPI.jl : Julia support for the [oneAPI](https://software.intel.com/en-us/oneapi) programming toolkit.

### NVIDIA CUDA

- https://github.com/JuliaFolds/FoldsCUDA.jl : provides `Transducers.jl`-compatible fold (`FLoops.jl`) implemented using `CUDA.jl`.
- https://github.com/JuliaGPU/CUDA.jl : CUDA programming in Julia. See also [JuliaCon 2021 video](https://youtu.be/fw0R5G8pB0U).
- https://github.com/JuliaGPU/NVTX.jl : Julia bindings for [NVIDIA Tools Extension Library (NVTX)](https://nvidia.github.io/NVTX/doxygen/index.html), for instrumenting with the [Nvidia Nsight Systems profiler](https://developer.nvidia.com/nsight-systems). [JuliaCon 2023 video](https://www.youtube.com/watch?v=B7ZlScN_rk8).
