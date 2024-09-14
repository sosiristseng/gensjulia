---
title: Development Tools
---

Julia development tools, compilers, debuggers, [DevOps](https://en.wikipedia.org/wiki/DevOps).

## Organizations

- [Julia debug](https://github.com/JuliaDebug)
- [Julia editor support](https://github.com/JuliaEditorSupport)
- [Julia packaging](https://github.com/JuliaPackaging)

## Resources

- [Awesome devops](https://github.com/wmariuss/awesome-devops)
- [JuliaHub](https://juliahub.com/ui/Home)
- [General registry](https://github.com/JuliaRegistries/General) : The official registry of general Julia packages.

## Static analysis

- https://github.com/aviatesk/JET.jl : experimental code analyzer for Julia.
- https://github.com/JuliaLang/AllocCheck.jl : a Julia package that statically checks if a function call may allocate by analyzing the generated LLVM IR of it and its callees.
- https://github.com/tonyhffong/Lint.jl : A lint tool to hunt for imperfections and dodgy structures that could be improved for Julia code.

## Style Guidelines

[Official Julia style guide](https://docs.julialang.org/en/v1/manual/style-guide/)

- https://github.com/invenia/BlueStyle : A Julia style guide.
- https://github.com/jrevels/YASGuide : Yet Another Style Guide For Julia.
- https://github.com/JuliaTesting/Aqua.jl : Auto QUality Assurance (automated checks) for Julia packages.

## Developing Julia packages

- https://github.com/JuliaInterop/VersionParsing.jl : flexible Version Number parsing.
- https://github.com/JuliaLang/Compat.jl : A package for cross-version compatibility between old Julia and the new - takes care of syntax breakage and provides compatibility constructs that will work in both versions without warnings.
- https://github.com/JuliaLang/PrecompileTools.jl : Reduce time-to-first-execution of Julia code.
- https://github.com/JuliaPackaging/Requires.jl : Lazy code loading in Julia packages. Will be replaced by [the extension system](https://pkgdocs.julialang.org/v1.9/creating-packages/#Conditional-loading-of-code-in-packages-(Extensions)) in Julia version 1.9+.
- https://github.com/Roger-luo/FromFile.jl : providing a macro `@from` importing objects from files without having to `include` files repeatedly.
- https://github.com/simonster/Reexport.jl : Julia macro for re-exporting one module from another.

### Package registry

- https://github.com/GunnarFarneback/LocalRegistry.jl : Create and maintain local package registries for Julia packages.
- https://github.com/JuliaComputing/Registrator.jl : Julia [package](https://pkg.julialang.org/) registration bot.

### Package templates

- https://github.com/invenia/PkgTemplates.jl : Generate Julia package skeletons using a simple template system.
- https://github.com/tpapp/PkgSkeleton.jl : Create new Julia packages, the easy way. Include templaye files for GitHub / GitLab CI.

### Prebuilt Binaries

- [Julia Packaging](https://github.com/JuliaPackaging) team.
- [Yggdrasil](https://github.com/JuliaPackaging/Yggdrasil) the binary repository.
- [Artifacts system](https://pkgdocs.julialang.org/v1/artifacts/) in Julia packaging.

---

- https://github.com/JuliaPackaging/BinaryBuilder.jl : Binary Dependency Builder for Julia.
- https://gitlab.com/aplavin/RunBinary.jl : running binary files from the `Yggdrasil` repo.

### Compilers

- https://github.com/JuliaHubOSS/llvm-cbe : A resurrected LLVM C Backend, with improvements for Julia.
- https://github.com/JuliaInterop/Clang.jl : Julia interface to libclang and C wrapper generator.
- https://github.com/JuliaLang/PackageCompiler.jl : Compiles your Julia environment into a system image or a standalone binary.
- https://github.com/tshort/StaticCompiler.jl : Compiles Julia code to a standalone library.

### Test-driven development (TDD)

- [Official docs: Unittest](https://docs.julialang.org/en/v1/stdlib/Test/)

---

- https://github.com/adolgert/UnitTestDesign.jl : chooses efficient combinations functional arguments to maximize test coverage.
- https://github.com/invenia/Mocking.jl : allowing temporary overwriting of Julia methods for testing purposes.
- https://github.com/julia-vscode/TestItemRunner.jl : run Julia tests in VSCode.
- https://github.com/JuliaCI/Coverage.jl : tracking code testing coverage and memory usage and optionally upload them to online services like Coveralls or Codecov.
- https://github.com/JuliaCloud/MockAWS.jl : patch functions for testing all AWS services.
- https://github.com/JuliaTesting/ReTest.jl : Testing framework for Julia, allowing deferred execution and filtered test sets.
- https://github.com/JuliaTesting/TestEnv.jl : `TestEnv.activate()` loads your test environment, so you can use your test dependencies in the REPL.
- https://github.com/rened/Watcher.jl : auto-run unit tests every time a file gets saved.
- https://github.com/Seelengrab/Supposition.jl : property-based testing using choice sequences. It's been heavily inspired by the testing framework [Hypothesis](https://hypothesis.readthedocs.io/en/latest/).
- https://github.com/wookay/Jive.jl : running test in parallel. It also supports watch folder function.
- https://github.com/YingboMa/SafeTestsets.jl : `@safetestset` puts `@testset` into a module to reduce global side effects.

### Logging

See also the built-in [Julia logging](https://docs.julialang.org/en/v1/stdlib/Logging/) facilities.

- https://github.com/JuliaLogging/ProgressLogging.jl : a package for defining progress logs.

## Benchmarking and Regression Testing

- [Julia Microbenchmarks against other programming languages](https://julialang.org/benchmarks/)

---

- https://github.com/awadell1/PkgJogger.jl : a benchmarking framework for Julia built on `BenchmarkTools.jl`, providing simple benchmark script loading and revision (by `Revise.jl`). It also enables continuous benchmarking.
- https://github.com/IanButterworth/SystemBenchmark.jl : Julia package for benchmarking a system's performance.
- https://github.com/JuliaCI/BenchmarkTools.jl : A benchmarking framework for the Julia language.
- https://github.com/JuliaCI/PkgBenchmark.jl : Easy benchmark tracking for packages
- https://github.com/JuliaCI/PkgEval.jl : Evaluate Julia packages for a range of Julia versions.
- https://github.com/JuliaOpt/ConicBenchmarkUtilities.jl : Julia utilities for the conic benchmark format for mathematical optimization.
- https://github.com/JuliaPlots/VisualRegressionTests.jl : Automated integrated regression tests for graphics libraries by comparing similarity between a newly generated image and a reference image.
- https://github.com/kimikage/ProfileSVG.jl : Write flame graphs to SVG format and explore them interactively in Jupyter, Pluto, etc.
- https://github.com/KristofferC/TimerOutputs.jl : Formatted output of timed sections in julia.
- https://github.com/schmrlng/CPUTime.jl : A module for CPU timing.
- https://github.com/timholy/ProfileView.jl : Visualization of Julia profiling data
- https://github.com/tkluck/StatProfilerHTML.jl : Show Julia profiling data in an HTML page.
- https://github.com/xiaodaigh/DataBench.jl : A package to benchmark data manipulation in Julia vs `R data.table`.

## Debugger

- [JuliaDebug](https://github.com/JuliaDebug) organization.

---

- https://github.com/dfdx/Ghost.jl : a code tracer for the Julia programming language. It lets you trace the function execution, recording all primitive operations onto a linearized tape.
- https://github.com/JuliaDebug/Debugger.jl : Julia debugger using the `@enter` macro.
- https://github.com/JuliaDebug/Infiltrator.jl : `@infiltrate` macro sets a "breakpoint" in a local context. All code is completely compiled.
- https://github.com/JuliaDebug/JuliaInterpreter.jl : Interpreter for Julia code.
- https://github.com/JuliaIO/Suppressor.jl :  Julia macros for suppressing output (STDOUT), warnings (STDERR) or both streams at the same time.
- https://github.com/MasonProtter/ToggleableAsserts.jl : Assertions that can be turned on or off with a switch, without runtime penalty when they're off.
- https://github.com/timholy/Rebugger.jl : An expression-level debugger for Julia, sans the ability to interact with or manipulate call stacks, but it can trace execution via the manipulation of Julia expressions.

## Documentation and report generation

[Julia docstrings](https://docs.julialang.org/en/v1/manual/documentation/)

---

- https://github.com/fredrikekre/Literate.jl : literate programming in Julia.
- https://github.com/JuliaBooks/Books.jl : generate books (or dashboards) in pdf/HTML/docx with embedded Julia output by pandoc document processor. Currently, this package is used to write the [Julia Data Science book](https://github.com/JuliaDataScience/JuliaDataScience).
- https://github.com/MichaelHatherly/CommonMark.jl : A CommonMark-compliant parser for Julia.
- https://github.com/JuliaDocs/Documenter.jl : The official documentation generator for Julia.
	- https://github.com/ali-ramadhan/DocumenterCitations.jl : uses https://github.com/Humans-of-Julia/Bibliography.jl to add support for BibTeX citations and references in documentation pages generated by https://github.com/JuliaDocs/Documenter.jl.
	- https://github.com/JuliaComputing/MultiDocumenter.jl : Aggregates documentations from multiple sources.
	- https://github.com/JuliaDocs/DocStringExtensions.jl : Extensions for Julia's documentation system.
- https://github.com/JunoLab/Weave.jl : A scientific report generator/literate programming tool for Julia based on Pweave and resembles Knitr and Sweave.
- https://github.com/piever/Remark.jl : A Julia package to create presentations from markdown using Remark.

## Integrated development environment (IDE)

[Julia editor suport](https://github.com/JuliaEditorSupport) organization.

- [Julia VSCode](https://www.julia-vscode.org/) : A powerful, free IDE for the Julia language.
- [jedit-julia](https://github.com/tuckerkevin/jedit-julia) : A [jEdit](http://jedit.org/) mode for Julia.
- [Julia.tmbundle](https://github.com/JuliaEditorSupport/Julia.tmbundle) : Julia language support for TextMate 2 (and Sublime Text).
- [LiClipse](https://www.liclipse.com/) : Eclipse plus some customizations, supports Julia.
- https://github.com/cormullion/juliamono : A monospaced font for Julia with unicode characters and ligatures.
- https://github.com/julia-vscode/LanguageServer.jl : An implementation of the Microsoft Language Server Protocol for the julia language.
- https://github.com/JunoLab/LNR.jl : Line numbering reader.

### Emacs

- [ESS support](https://github.com/emacs-ess/ESS/blob/master/lisp/ess-julia.el) for julia language, includes font-lock, indentation, sending code to sub-process, interactive documentation, imenu, completion and eldoc. Also see its [Installation instructions for Julia](https://github.com/emacs-ess/ESS/wiki/Julia)
- https://github.com/JuliaEditorSupport/julia-emacs : Julia support in Emacs.
- https://github.com/tpapp/julia-repl : Run an interior Julia REPL in a terminal inside Emacs.

### Vim

- https://github.com/JuliaEditorSupport/julia-vim
- https://github.com/bfredl/Neovim.jl by @bfredl : Neovim client for Julia.
- https://github.com/baruchel/vim-notebook : Vim users can use Julia from the `vim-notebook` plugin.

### Jupyter Notebooks

[Jupyter](https://github.com/jupyter)

- https://github.com/JuliaLang/IJulia.jl : Julia kernel for Jupyter.
- https://github.com/JuliaGizmos/Interact.jl : Library for interactive widgets in IJulia.
- https://github.com/stevengj/NBInclude.jl : Import code from IJulia Jupyter notebooks into Julia programs.

### Web IDE

[Wikipedia: web IDE](https://en.wikipedia.org/wiki/Web_integrated_development_environment)

- [Google colab Julia notebook](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_for_Pythonistas.ipynb)
- [Julia Hub](https://juliahub.com/ui/index.html)
- [Julia on the SageMath cloud server](https://cocalc.com/)
- [Repl.it](https://replit.com/)
- [Nextjournal](https://nextjournal.com/)
- [CodeBunk](https://codebunk.com) supports Julia for collaborative screen-sharing on the cloud.

## Shell scripting

- [Shell scripting](https://en.wikipedia.org/wiki/Shell_script)
- [Administrative scripting with Julia](https://github.com/ninjaaron/administrative-scripting-with-julia) : A guide for writing shell scripts in Julia.

## GUI

- https://github.com/barche/QML.jl : Small example for starting an interface to Qt5 QML.
- https://github.com/davidanthoff/Electron.jl : Julia wrapper for [Electron](https://www.electronjs.org/) with a more minimalistic feature set than `Blink.jl`.
- https://github.com/JuliaGizmos/Blink.jl : Julia wrapper around [Electron](https://www.electronjs.org/).
- https://github.com/JuliaGraphics/Gtk.jl : Julia interface to the GTK windowing toolkit.
- https://github.com/JuliaGraphics/Tk.jl : The Julia interface for the Tk windowing toolkit.


## Continuous integration (CI) providers

`PkgTemplates.jl` and `PkgSkeleton.jl` can generate the CI/CD configuration files.

### Gitlab-CI

- [GitlabJuliaDemo.jl](https://gitlab.com/tkpapp/GitlabJuliaDemo.jl) : A minimal example for setting up CI with Julia on Gitlab. The [blog post](https://tamaspapp.eu/post/julia-ci-gitlab/) describing how a Julia package repo in Gitlab can be setup with continuous integration and coverage summary. A sample CI file `.gitlab-ci.yml` is [here](https://gitlab.com/tkpapp/GitlabJuliaDemo.jl/-/blob/master/.gitlab-ci.yml).

### GitHub

[GitHub actions for Julia](https://github.com/julia-actions). [A sample CI file](https://github.com/tpapp/PkgSkeleton.jl/blob/master/.github/workflows/CI.yml).

- [setup-julia](https://github.com/julia-actions/setup-julia) : downloading a specified version of Julia and adding it to PATH.
- [cache](https://github.com/julia-actions/cache) : A shortcut action to cache Julia artifacts, packages, and registries.
- [julia-buildpkg](https://github.com/julia-actions/julia-buildpkg)
- [julia-runtest](https://github.com/julia-actions/julia-runtest)
- [julia-processcoverage](https://github.com/julia-actions/julia-processcoverage)
- [CompatHelper workflow](https://github.com/JuliaRegistries/CompatHelper.jl/blob/master/.github/workflows/CompatHelper.yml)

## Containers and Virtualization

[Virtualization](https://en.wikipedia.org/wiki/Category:Virtualization_software)

- [Julia docker image](https://hub.docker.com/_/julia) and the packaging [`DOCKERFILE`](https://github.com/docker-library/julia).
