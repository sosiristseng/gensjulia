---
Created: 2025-11-20, 20:53:54
Modified: 2025-11-22, 16:58:33
title: Development Tools
---
# Development Tools

> Julia development tools, compilers, debuggers, [DevOps](https://en.wikipedia.org/wiki/DevOps).

## Organizations

- [Julia debug](https://github.com/JuliaDebug)
- [Julia editor support](https://github.com/JuliaEditorSupport)
- [Julia packaging](https://github.com/JuliaPackaging)

## Resources

- [Awesome devops](https://github.com/wmariuss/awesome-devops)
- [JuliaHub](https://juliahub.com/ui/Home)
- [General registry](https://github.com/JuliaRegistries/General) : The official registry of general Julia packages.

## Static analysis

- [AllocCheck.jl](https://github.com/JuliaLang/AllocCheck.jl) : a Julia package that statically checks if a function call may allocate by analyzing the generated LLVM IR of it and its callees.
- [JET.jl](https://github.com/aviatesk/JET.jl) : experimental code analyzer for Julia.
- [Lint.jl](https://github.com/tonyhffong/Lint.jl) : A lint tool to hunt for imperfections and dodgy structures that could be improved for Julia code.
- [StaticLint.jl](https://github.com/julia-vscode/StaticLint.jl) : Static Code Analysis for Julia.

## Style Guidelines

[Official Julia style guide](https://docs.julialang.org/en/v1/manual/style-guide/)

- [BlueStyle](https://github.com/invenia/BlueStyle) : A Julia style guide.
- [YASGuide](https://github.com/jrevels/YASGuide) : Yet Another Style Guide For Julia.
- [Aqua.jl](https://github.com/JuliaTesting/Aqua.jl) : Auto Quality Assurance (automated checks) for Julia packages.

## Developing Julia packages

- [Compat.jl](https://github.com/JuliaLang/Compat.jl): ease interoperability between older and newer versions of [Julia](http://julialang.org/).
- [FromFile.jl](https://github.com/Roger-luo/FromFile.jl) : providing a macro `@from include()` importing objects from files without including files repeatedly.
- [PrecompileTools.jl](https://github.com/JuliaLang/PrecompileTools.jl) : Reduce time-to-first-execution of Julia code.
- [Reexport.jl](https://github.com/simonster/Reexport.jl) : Julia macro for re-exporting one module from another.
- [VersionParsing.jl](https://github.com/JuliaInterop/VersionParsing.jl) : parsing version-number strings into Julia's built-in `VersionNumber` type.

### Package registry

- [LocalRegistry.jl](https://github.com/GunnarFarneback/LocalRegistry.jl) : Create and maintain local package registries for Julia packages.
- [Registrator.jl](https://github.com/JuliaRegistries/Registrator.jl) : Julia [package](https://pkg.julialang.org/) registration bot.

### Package templates

- [PkgTemplates.jl](https://github.com/invenia/PkgTemplates.jl) : Generate Julia package skeletons using a simple template system.
- [PkgSkeleton.jl](https://github.com/tpapp/PkgSkeleton.jl) : Create new Julia packages, the easy way. Include template files for GitHub / GitLab CI.

### Prebuilt Binaries

- [Julia Packaging](https://github.com/JuliaPackaging) team.
- [Yggdrasil](https://github.com/JuliaPackaging/Yggdrasil) the binary repository.
- [Artifacts system](https://pkgdocs.julialang.org/v1/artifacts/) in Julia packaging.

---

- [BinaryBuilder.jl](https://github.com/JuliaPackaging/BinaryBuilder.jl) : Binary Dependency Builder for Julia.
- [RunBinary.jl](https://gitlab.com/aplavin/RunBinary.jl) : running binary files from the `Yggdrasil` repo.

### Compilers

- [Clang.jl](https://github.com/JuliaInterop/Clang.jl) : Julia interface to libclang and C wrapper generator.
- [llvm-cbe](https://github.com/JuliaHubOSS/llvm-cbe) : A resurrected LLVM C Backend, with improvements for Julia.
- [PackageCompiler.jl](https://github.com/JuliaLang/PackageCompiler.jl) : Compiles your Julia environment into a system image or a standalone binary.
- [StaticCompiler.jl](https://github.com/tshort/StaticCompiler.jl) : Compiles Julia code to a standalone library. (experimental)
### Test-driven development (TDD)

- [Official docs: Unittest](https://docs.julialang.org/en/v1/stdlib/Test/)
- [Julia Test](https://github.com/JuliaTesting/) organization

---

- [Coverage.jl](https://github.com/JuliaCI/Coverage.jl) : tracking code testing coverage and memory usage and optionally upload them to online services like Coveralls or Codecov.
- https://github.com/JuliaCloud/MockAWS.jl : patch functions for testing all AWS services.
- [Jive.jl](https://github.com/wookay/Jive.jl) : running test in parallel. It also supports watch folder function.
- [Mocking.jl](https://github.com/JuliaTesting/Mocking.jl) : allowing temporary overwriting of Julia methods for testing purposes.
- [ReTest.jl](https://github.com/JuliaTesting/ReTest.jl) : Testing framework for Julia, allowing deferred execution and filtered test sets.
- [SafeTestsets.jl](https://github.com/YingboMa/SafeTestsets.jl) : `@safetestset` puts `@testset` into a module to reduce global side effects.
- [Supposition.jl](https://github.com/Seelengrab/Supposition.jl) : property-based testing using choice sequences. It's been heavily inspired by the testing framework [Hypothesis](https://hypothesis.readthedocs.io/en/latest/).
- [TestEnv.jl](https://github.com/JuliaTesting/TestEnv.jl) : `TestEnv.activate()` loads your test environment, so you can use your test dependencies in the REPL.
- [TestItemRunner.jl](https://github.com/julia-vscode/TestItemRunner.jl) : run Julia tests with `@testitem` in VSCode.
- [UnitTestDesign.jl](https://github.com/adolgert/UnitTestDesign.jl) : chooses efficient combinations functional arguments to maximize test coverage.
- [Watcher.jl](https://github.com/rened/Watcher.jl) : auto-run unit tests every time a file gets saved.

## Logging

The built-in [Julia logging](https://docs.julialang.org/en/v1/stdlib/Logging/) facilities.

- [ProgressLogging.jl](https://github.com/JuliaLogging/ProgressLogging.jl) : a package for defining progress logs, supported by REPL ([TerminalLoggers.jl](https://github.com/JuliaLogging/TerminalLoggers.jl)), VS Code, Pluto.

## Benchmarking and Regression Testing

- [Julia Microbenchmarks against other programming languages](https://julialang.org/benchmarks/)

---

- [BaseBenchmarks.jl](https://github.com/JuliaCI/BaseBenchmarks.jl): A collection of Julia benchmarks available for CI tracking from the JuliaLang/julia repository.
- [BenchmarkTools.jl](https://github.com/JuliaCI/BenchmarkTools.jl) : A benchmarking framework for the Julia language.
- [PkgBenchmark.jl](https://github.com/JuliaCI/PkgBenchmark.jl) : Easy benchmark tracking for packages
- [PkgEval.jl](https://github.com/JuliaCI/PkgEval.jl) : Evaluate Julia packages for a range of Julia versions.
- [PkgJogger.jl](https://github.com/awadell1/PkgJogger.jl) : a benchmarking framework for Julia built on `BenchmarkTools.jl`, providing simple benchmark script loading and revision (by `Revise.jl`). It also enables continuous benchmarking.
- [SystemBenchmark.jl](https://github.com/IanButterworth/SystemBenchmark.jl) : Julia package for benchmarking a system's performance.
- [TimerOutputs.jl](https://github.com/KristofferC/TimerOutputs.jl) : Formatted output of timed sections in julia.
- [VisualRegressionTests.jl](https://github.com/JuliaPlots/VisualRegressionTests.jl) : Automated integrated regression tests for graphics libraries by comparing similarity between a newly generated image and a reference image.

### Profilers

Analyzing how much time is spent on individual line(s). Julia docs: https://docs.julialang.org/en/v1/manual/profile/

- [ProfileSVG.jl](https://github.com/kimikage/ProfileSVG.jl) : Write flame graphs to SVG format and explore them interactively in Jupyter, Pluto, etc.
- [ProfileView.jl](https://github.com/timholy/ProfileView.jl) : Visualization of Julia profiling data
- [StatProfilerHTML.jl](https://github.com/tkluck/StatProfilerHTML.jl) : Show Julia profiling data in an HTML page.

## Debugger

- [JuliaDebug](https://github.com/JuliaDebug) organization.
- [Debugging Julia in VS Code](https://www.julia-vscode.org/docs/stable/userguide/debugging/)

---

- [Cthulhu.jl](https://github.com/JuliaDebug/Cthulhu.jl) : Cthulhu can help you debug type inference issues by recursively showing the type-inferred code until you find the exact point where inference gave up, messed up, or did something unexpected. Using the Cthulhu interface, you can debug type inference problems faster.
- [Debugger.jl](https://github.com/JuliaDebug/Debugger.jl) : Julia debugger using the `@enter` macro.
- [Infiltrator.jl](https://github.com/JuliaDebug/Infiltrator.jl) : `@infiltrate` macro sets a "breakpoint" in a local context. All code is completely compiled and faster than `Debugger.jl`. [JuliaCon 2024 video](https://youtu.be/N4OUN8Js1S0)
- [JuliaInterpreter.jl](https://github.com/JuliaDebug/JuliaInterpreter.jl) : Interpreter for Julia code.
- [Suppressor.jl](https://github.com/JuliaIO/Suppressor.jl) :  Julia macros for suppressing output (STDOUT), warnings (STDERR) or both streams at the same time.

## Documentation and report generation

[Julia docstrings](https://docs.julialang.org/en/v1/manual/documentation/)

---

- [Books.jl](https://github.com/JuliaBooks/Books.jl) : generate books (or dashboards) in pdf/HTML/docx with embedded Julia output by pandoc document processor. Currently, this package is used to write the [Julia Data Science book](https://github.com/JuliaDataScience/JuliaDataScience).
- [Literate.jl](https://github.com/fredrikekre/Literate.jl) : literate programming in Julia.
- [QuartoNotebookRunner.jl](https://github.com/PumasAI/QuartoNotebookRunner.jl) : Julia code evaluation engine used by [Quarto](https://quarto.org/docs/computations/julia.html).
- [Remark.jl](https://github.com/piever/Remark.jl) : A Julia package to create presentations from markdown using [Remark](https://github.com/gnab/remark).
- [Weave.jl](https://github.com/JunoLab/Weave.jl) : A scientific report generator/literate programming tool for Julia based on Pweave and resembles Knitr and Sweave.
- [Documenter.jl](https://github.com/JuliaDocs/Documenter.jl) : The official documentation generator for Julia.
	  - [DocumenterCitations.jl](https://github.com/ali-ramadhan/DocumenterCitations.jl) : uses [Bibliography.jl](https://github.com/Humans-of-Julia/Bibliography.jl) to add support for BibTeX citations and references in documentation pages generated by Documenter.jl.
	  - [MultiDocumenter.jl](https://github.com/JuliaComputing/MultiDocumenter.jl) : Aggregates documentations from multiple sources.
	  - [DocStringExtensions.jl](https://github.com/JuliaDocs/DocStringExtensions.jl) : Extensions for Julia's documentation system.

## Integrated development environment (IDE)

[Julia editor suport](https://github.com/JuliaEditorSupport) organization.

- [Julia VSCode](https://www.julia-vscode.org/) : A powerful, free IDE for the Julia language.
	- [LanguageServer.jl](https://github.com/julia-vscode/LanguageServer.jl) : An implementation of the Microsoft Language Server Protocol for the julia language.
- [Julia.tmbundle](https://github.com/JuliaEditorSupport/Julia.tmbundle) : Julia language support for TextMate 2 (and Sublime Text).
- [Julia in Quarto](https://quarto.org/docs/computations/julia.html): An open-source scientific and technical publishing system.
- [LiClipse](https://www.liclipse.com/) : Eclipse plus some customizations, supports Julia.
- [juliamono](https://github.com/cormullion/juliamono) : A monospaced font for Julia with unicode characters and ligatures.

### Emacs

- [ESS support](https://github.com/emacs-ess/ESS/blob/master/lisp/ess-julia.el) for julia language, includes font-lock, indentation, sending code to sub-process, interactive documentation, imenu, completion and eldoc. Also see its [Installation instructions for Julia](https://github.com/emacs-ess/ESS/wiki/Julia)
- [julia-emacs](https://github.com/JuliaEditorSupport/julia-emacs) : Julia support in Emacs.
- [julia-repl](https://github.com/tpapp/julia-repl) : Run an interior Julia REPL in a terminal inside Emacs.

### Vim

- [julia-vim](https://github.com/JuliaEditorSupport/julia-vim)
- [Neovim.jl](https://github.com/bfredl/Neovim.jl) by @bfredl : Neovim client for Julia.
- [vim-notebook](https://github.com/baruchel/vim-notebook) : Vim users can use Julia from the `vim-notebook` plugin.

### Jupyter notebooks

[Jupyter](https://github.com/jupyter)

- [IJulia.jl](https://github.com/JuliaLang/IJulia.jl) : Julia kernel for Jupyter.
- [Interact.jl](https://github.com/JuliaGizmos/Interact.jl) : Library for interactive widgets in IJulia.
- [NBInclude.jl](https://github.com/stevengj/NBInclude.jl) : Import code from IJulia Jupyter notebooks into Julia programs.

### Pluto notebooks

- [Pluto.jl](https://github.com/fonsp/Pluto.jl) : Reactive notebooks for Julia.
- [PlutoPages.jl](https://github.com/JuliaPluto/PlutoPages.jl) : `PlutoPages.jl` is a site generation system inspired by https://www.11ty.dev/.
- [PlutoSliderServer.jl](https://github.com/JuliaPluto/PlutoSliderServer.jl) : Web server to host Pluto notebooks supporting static conversion to HTML files.
- [PlutoStaticHTML.jl](https://github.com/rikhuijzer/PlutoStaticHTML.jl) : Convert Pluto notebooks to pure HTML files. [Template for Julia tutorials](https://rikhuijzer.github.io/JuliaTutorialsTemplate/).
- [PlutoUI.jl](https://github.com/JuliaPluto/PlutoUI.jl) : A small package with interactive elements to be used in Pluto.jl.

### Web IDE

[Wikipedia: web IDE](https://en.wikipedia.org/wiki/Web_integrated_development_environment)

- [Google colab Julia notebook](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_for_Pythonistas.ipynb)
- [Julia Hub](https://juliahub.com/ui/index.html)
- [Julia on the SageMath cloud server](https://cocalc.com/)
- [Repl.it](https://replit.com/)
- [Nextjournal](https://nextjournal.com/)

## User interface

- [[cli|Command-line interface]]
- [[gui|Graphical User Interface]]

## Containers and Virtualization

[Virtualization](https://en.wikipedia.org/wiki/Category:Virtualization_software)

- [Julia docker image](https://hub.docker.com/_/julia) and the packaging [`DOCKERFILE`](https://github.com/docker-library/julia).

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
- [Julia TagBot](https://github.com/JuliaRegistries/TagBot) : Creates tags, releases, and changelogs for your Julia packages when they're registered.