---
title: Programming Paradigms
---

- [Wikipedia: Programming Paradigms](https://en.wikipedia.org/wiki/Programming_paradigm)
- [Basic Language Comparison](https://github.com/JulesKouatchou/basic_language_comparison) : Basic Comparison of Various Computing Languages, eg. Python, Julia, Matlab, IDL, R, Java, Scala, C, Fortran.
- [Programming Language Theory](https://github.com/steshaw/plt)

## Automata

- [Wikipedia: Automata](https://en.wikipedia.org/wiki/Category:Automata_(computation))
- [Wikipedia: Deterministic finite automaton](https://en.wikipedia.org/wiki/Deterministic_finite_automaton)

---

- https://github.com/BioJulia/Automa.jl : A julia code generator for regular expressions - this package can do text validation, parsing, and tokenizing based on state machine compiler.
- https://github.com/timholy/CodeTracking.jl : An extension of Julia's InteractiveUtils library that provides an interface for obtaining strings and expressions of method definitions, method signatures, etc.. designed to work with `Revise.jl` (for versions v1.1.0 and higher).


## Control Flow

- [Wikipedia: Control Flow](https://en.wikipedia.org/wiki/Category:Control_flow)
- [Julia docs: Control flow](https://docs.julialang.org/en/v1/manual/control-flow/)

---

- https://github.com/jemofthewest/LinearControl.jl : Julia package for analysis and design of control strategies for linear systems.
- https://github.com/JuliaCollections/IterTools.jl : Common functional iterator patterns.
- https://github.com/JuliaControl/ControlSystems.jl : A Control Systems Toolbox for Julia.
- https://github.com/JuliaIO/ProtoBuf.jl : A Julia implementation for protocol buffers, a language-neutral, platform-neutral, extensible way of serializing structured data for use in communications protocols, data storage, and more.
- https://github.com/rdeits/CommonSubexpressions.jl : Naïve combined subexpression elimination in Julia.

### Reversible programming

- [Wikipedia: reversible programming](https://en.wikipedia.org/wiki/Reversible_computing)

---

- https://github.com/GiggleLiu/NiLang.jl : a reversible domain-specific language (DSL). Every state change can be undone.

## Functional Programming

- [Wikipedia: Declarative Programming](https://en.wikipedia.org/wiki/Declarative_programming)
- [Wikipedia: Functional Programming](https://en.wikipedia.org/wiki/Functional_programming)

---

- https://github.com/jkrumbiegel/Chain.jl : A Julia package for piping a value through a series of transformation expressions using a convenient syntax.
- https://github.com/MikeInnes/Lazy.jl : Functional programming for Julia with lazily-evaluated lists and a large library of functions for working with them.
- https://github.com/oxinabox/Pipe.jl : Improved function piping in Julia.
- https://github.com/pao/Monads.jl : Monadic expressions and sequences for Julia. [hSee the doc](https://monadsjl.readthedocs.io/en/latest/).
- https://github.com/swadey/LispSyntax.jl : lisp-like language in julia. [LispREPL.jl](https://github.com/swadey/LispREPL.jl) : REPL for `LispSyntax.jl`.
- https://github.com/vtjnash/Glob.jl : POSIX-compliant file name pattern matching.

### Pattern matching

- [Wikipedia pattern matching](https://en.wikipedia.org/wiki/Pattern_matching)

- https://github.com/jolin-io/SimpleMatch.jl : a simple Julia pattern matching package providing only the `@match` macro.
- https://github.com/JuliaServices/Match.jl : Advanced Pattern Matching for Julia.
- https://github.com/thautwarm/MLStyle.jl : Julia functional programming infrastructures and metaprogramming facilities.
- https://github.com/Roger-luo/Moshi.jl : Generic Algebraic Data Type + Pattern Match.

## Reactive Programming

[Wikipedia: Reactive Programming](https://en.wikipedia.org/wiki/Reactive_programming)

- https://github.com/biaslab/Rocket.jl : A functional reactive programming extensions library for Julia.
- https://github.com/JuliaGizmos/Reactive.jl : A package for reactive programming in Julia.

## Design by contract

[Wikipedia: Design by contract](https://en.wikipedia.org/wiki/Design_by_contract)

- https://github.com/ghaetinger/DesignByContract.jl : an interface for Design By Contract programming in Julia. See also [Eiffel](https://www.eiffel.org/doc/eiffel/Learning_Eiffel), which first introduced Design By Contract programming.

## Interpreters

[Wikipedia: Interpreters](https://en.wikipedia.org/wiki/Category:Interpreters_(computing))

- https://github.com/JuliaDebug/JuliaInterpreter.jl : Interpreter for Julia code.

## Macro and Metaprogramming

- [Wikipedia: Macro](https://en.wikipedia.org/wiki/Macro_(computer_science))
- [Wikipedia: Metaprogramming](https://en.wikipedia.org/wiki/Metaprogramming)
- [Julia docs: Metaprogramming](https://docs.julialang.org/en/v1/manual/metaprogramming/#Metaprogramming)

---

- https://github.com/chakravala/ForceImport.jl : Macro that force imports conflicting methods in Julia modules.
- https://github.com/chakravala/SyntaxTree.jl : Toolset for modifying Julia AST and characteristic values.
- https://github.com/FluxML/MacroTools.jl : A library providing helpful tools for writing macros, notably a very simple templating system with some functions.
- https://github.com/StephenVavasis/Unroll.jl : A julia macro for unrolling conditional `for` loops.

## Automatic Programming

[Wikipedia: Automatic Programming](https://en.wikipedia.org/wiki/Automatic_programming)

--

- https://github.com/FluxML/IRTools.jl : Intermediate Representation toolkit to provide a simple and flexible IR format, expressive enough to work with both lowered and typed Julia code, as well as external IRs. It can be used with Julia metaprogramming tools such as Cassette.
- https://github.com/JuliaLabs/Cassette.jl : a Julia package that provides a mechanism for dynamically injecting code transformation passes into Julia’s just-in-time (JIT) compilation cycle, enabling post hoc analysis, optimization, and modification of "Cassette-unaware" Julia programs.
- https://github.com/timholy/Revise.jl : Automatically update function definitions in a running Julia session. It will help you keep your sessions running longer, reducing the need to restart Julia whenever you make changes to code.

## Program Analysis


- [Wikipedia: Program Analysis](https://en.wikipedia.org/wiki/Category:Program_analysis)\
- [Julia docs: profiling](https://docs.julialang.org/en/v1/manual/profile/).

---

- https://github.com/JuliaCollections/LRUCache.jl : An implementation of a Least Recently Used (LRU) Cache.
- https://github.com/kimikage/ProfileSVG.jl : Write flame graphs to SVG format and explore them interactively in Jupyter, Pluto, etc.
- https://github.com/timholy/CallGraphs.jl : A package for analyzing source-code callgraphs, particularly of Julia's `src/` directory. The main motivation for this package was to aid in finding all functions that might trigger garbage collection by directly or indirectly calling `jl_gc_collect`; however, the package has broader uses.
- https://github.com/timholy/ProfileView.jl : Visualization of Julia profiling data
- https://github.com/tkluck/StatProfilerHTML.jl : Show Julia profiling data in an explorable HTML page.
- https://github.com/zenna/Lens.jl : A simple Julia library to inspect the runtime behaviour of your programs, with minimal interference to the program itself.

## Polymorphism amd multiple dispatch

- [Wikipedia: Polymorphism](https://en.wikipedia.org/wiki/Category:Polymorphism_(computer_science)) and [Holy Traits pattern](https://github.com/JuliaLang/julia/issues/2345#issuecomment-54537633).
- [The Design Impact of Multiple Dispatch](https://nbviewer.jupyter.org/gist/StefanKarpinski/b8fe9dbb36c1427b9f22) presented by StefanKarpinski at Strange Loop on 19-Sep-2013.
- [JuliaCon 2019: The Unreasonable Effectiveness of Multiple Dispatch by Stefan Karpinski](https://youtu.be/kc9HwsxE1OY)

---

- https://github.com/jolin-io/WhereTraits.jl : This package exports one powerful macro @traits with which you can extend Julia's where syntax.
- https://github.com/mauro3/SimpleTraits.jl : Simple Traits for Julia.
- https://github.com/tk3369/BinaryTraits.jl : easy-to-use trait library with formal interface specification support.
- https://github.com/ztangent/ValSplit.jl : Compile away dynamic dispatch on Val-typed arguments via value-splitting.

## Object-oriented programming (OOP)

- https://github.com/Suzhou-Tongyuan/ObjectOriented.jl : Conventional object-oriented programming in Julia without breaking Julia's core design ideas. We recommend you to read [How to Translate OOP into Idiomatic Julia](https://suzhou-tongyuan.github.io/ObjectOriented.jl/dev/how-to-translate-oop-into-julia) before using this package.

## Fuzzy Logic

[Wikipedia: Fuzzy logic](https://en.wikipedia.org/wiki/Fuzzy_logic)

---

- https://github.com/lucaferranti/FuzzyLogic.jl : Julia package for fuzzy inference. [Julia Con 2023 video](https://www.youtube.com/watch?v=6WfX3e-aOBc)
