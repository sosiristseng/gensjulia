---
title: Data Structures
---

## Organizations

- [Julia Collections](https://github.com/JuliaCollections)
- [Julia ArbTypes](https://github.com/JuliaArbTypes)

## Resources

- [Youtube: The State of the Type System](https://www.youtube.com/watch?v=Z2LtJUe1q8c) at JuliaCon 2017 by Jeff Bezanson
- [Youtube: The Unreasonable Effectiveness of Multiple Dispatch](https://youtu.be/kc9HwsxE1OY)  at JuliaCon 2019 by Stefan Karpinski
- [A more thorough look at Julia's **double colon** syntax](https://nbviewer.org/github/tlycken/IJulia-Notebooks/blob/master/A%20more%20thorough%20look%20at%20Julia%27s%20%22double%20colon%22%20syntax.ipynb)

## General data structures

- https://github.com/JuliaAudio/RingBuffers.jl : A simple non-allocating circular RingBuffer type, with configurable overflow and underflow handling.
- https://github.com/JuliaCollections/DataStructures.jl : Julia implementation of Data structures.
- https://github.com/noahbenson/Air.jl : an immutable data structure and software transactional memory tool for Julia.
- https://github.com/tkoolen/TypeSortedCollections.jl : It provides the `TypeSortedCollection` type, which can be used to store type-heterogeneous data in a way that allows operations on the data to be performed in a type-stable manner.

### Functors

- https://github.com/JuliaCollections/FunctionalCollections.jl : Functional and and persistent data structures for Julia.

### Result types

- https://github.com/iamed2/ResultTypes.jl : A Result type for returning a value or an error in a type-stable manner without throwing an exception.
- https://github.com/jakobnissen/ErrorTypes.jl : A simple implementation of Rust-like error handling in Julia.

## Text / string data type

- https://github.com/JuliaComputing/FixedSizeStrings.jl : A type for efficiently storing short strings of known size.
- https://github.com/JuliaData/WeakRefStrings.jl : a minimal String type for Julia that allows for efficient string representation and transfer.
- https://github.com/JuliaInterop/VersionParsing.jl : flexible VersionNumber parsing in Julia.
- https://github.com/JuliaIO/Formatting.jl : A Julia package to provide Python-like formatting support.
- https://github.com/JuliaString/Format.jl : This Julia package provides C and Python-style types and functions formatting support.
- https://github.com/JuliaString/ShortStrings.jl : A fast and efficient string format implementation for storing strings of size less than 15 bytes.
- https://github.com/JuliaString/StringLiterals.jl : Implement improved string literals with Swift-style syntax for interpolation, hex, & unicode characters, plus C & Python style formatting and Unicode, HTML, LaTeX, and Emoji entities.
- https://github.com/matthieugomez/StringDistances.jl : String Distances in Julia.
- https://github.com/stevengj/LaTeXStrings.jl : This is a small package to make it easier to type LaTeX equations in string literals in the Julia language.

### i18n-L10n and unicode tools

- https://github.com/Julia-i18n/Gettext.jl : An interface to the [gettext](http://www.gnu.org/software/gettext/manual/html_node/index.html) internationalization/translation interface.
- https://github.com/JuliaStrings/ICU.jl : Julia wrapper for the [International Components for Unicode (ICU) libraries](http://site.icu-project.org/).

## Graph data types

See the [[graph]] theory section.

## Numeric data types

- https://github.com/cjdoris/Infinity.jl : Representation of infinity in Julia.
- https://github.com/JuliaArrays/CustomUnitRanges.jl : This Julia package supports the creation of array types with "unconventional" indices.
- https://github.com/JuliaGeometry/Quaternions.jl : Quaternions, octonions and dual-quaternions for 3D rotational orientation.
- https://github.com/JuliaGraphics/Measures.jl : Unified measure and coordinates types.
- https://github.com/JuliaMath/FixedPointNumbers.jl : This library exports [fixed-point number](http://en.wikipedia.org/wiki/Fixed-point_arithmetic) types.
- https://github.com/PainterQubits/Unitful.jl : A Julia package for physical units.
- https://github.com/rfourquet/BitIntegers.jl : This package implements fixed-width integer types similar to standard builtin-ones like Int or UInt128.
- https://github.com/SymbolicML/DynamicQuantities.jl : Lightweight and fast physical quantities in Julia.
- https://github.com/timholy/Ratios.jl : Faster Rational-like types for Julia at the risk of greater risk of overflow.

### Intervals

[Julia intervals](https://juliaintervals.github.io/)

- https://github.com/baggepinnen/MonteCarloMeasurements.jl : Error propagation using Monte-Carlo simulation. Similar to `Measurements.jl`, but more accurate for highly nonlinear functions at the expense of longer execution time.
- https://github.com/juliaintervals/intervalarithmetic.jl : Rigorous floating-point calculations using interval arithmetic in Julia.
- https://github.com/JuliaPhysics/Measurements.jl : Error propagation calculator and library. It supports real and complex numbers with uncertainty, arbitrary precision calculations, and operations with arrays.

### Floating-point numbers

- https://github.com/cjdoris/LogarithmicNumbers.jl : A [logarithmic number system](https://en.wikipedia.org/wiki/Logarithmic_number_system) for Julia. Provides the signed `ULogarithmic` and unsigned `Logarithmic` types for representing real numbers on a logarithmic scale.
- https://github.com/JeffreySarnoff/ArbNumerics.jl : extended precision math, accurate and performant
- https://github.com/JuliaMath/BFloat16s.jl : This package defines the [BFloat16 data type](https://en.wikipedia.org/wiki/Bfloat16_floating-point_format). The only currently available hardware implementation of this datatype are Google's [Cloud TPUs](https://en.wikipedia.org/wiki/Tensor_processing_unit).
- https://github.com/JuliaMath/DecFP.jl : The package provides 32-bit, 64-bit, and 128-bit binary-encoded decimal floating-point types following the IEEE 754-2008, implemented as a wrapper around the (BSD-licensed) [Intel Decimal Floating-Point Math Library](https://www.intel.com/content/www/us/en/developer/articles/tool/intel-decimal-floating-point-math-library.html).
- https://github.com/JuliaMath/Decimals.jl : Pure Julia decimal arithmetic library.
- https://github.com/JuliaMath/DoubleFloats.jl : Numbers with 85 accurate bits.

## Array types

See the [[mathematics]] section.

## Composite Data Types

[Wikipedia: Composite Data Types](https://en.wikipedia.org/wiki/Category:Composite_data_types)

- [`Base.@kwdef`](https://discourse.julialang.org/t/what-does-kwdef-do/51973) : a concise struct construction in the Julia base.

---

- https://github.com/andyferris/Dictionaries.jl : An alternative interface for dictionaries in Julia, for improved productivity and performance.
- https://github.com/charleskawczynski/DispatchedTuples.jl : `Dispatched Tuples` are like immutable dictionaries (so, they're technically more like `NamedTuples`) except that the keys are instances of types. Also, because DispatchedTuples are backed by tuples, they are GPU-friendly.
- https://github.com/jonniedie/ConcreteStructs.jl : `@concrete` can be used to make non-concrete structs concrete without the boilerplate of adding type parameters.
- https://github.com/mauro3/SimpleTraits.jl : Simple [Traits](https://github.com/JuliaLang/julia/issues/2345#issuecomment-54537633) for Julia
- https://github.com/scheinerman/Bijections.jl : Bijection datatype for Julia that blocks assigning the same value to two different keys.
- https://github.com/synchronoustechnologies/TypeParams.jl : keeping compile-time type information in `struct` for better performance.

### Accessing elements

- https://github.com/devmotion/SimpleUnPack.jl : Lightweight Julia macro for destructuring properties and fields. (Requires Julia >= 1.7)
- https://github.com/JeffreySarnoff/TypedDelegation.jl : Easily apply functions onto fields' values.
- https://github.com/JuliaObjects/Accessors.jl : updating immutable data simple. It is the successor of `Setfield.jl`.
- https://github.com/jw3126/Setfield.jl : Update deeply nested immutable structs.
- https://github.com/mauro3/Parameters.jl : Types with default field values, keyword constructors and (un-)pack macros.
- https://github.com/mauro3/UnPack.jl : `@unpack` some or all of the fields of a type, and `@pack`, in the case of mutable datatypes.
