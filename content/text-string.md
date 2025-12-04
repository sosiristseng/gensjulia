---
title: Text and String
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:49:29
---

## Text and String

> Text and string data type and processing

- [JuliaStrings](https://github.com/JuliaStrings/)
- [Julia-i18n](https://github.com/Julia-i18n)

### Text data type

- [FixedSizeStrings.jl](https://github.com/JuliaComputing/FixedSizeStrings.jl ): A type for efficiently storing short strings of known size.
- [WeakRefStrings.jl](https://github.com/JuliaData/WeakRefStrings.jl) : a minimal String type for Julia that allows for efficient string representation and transfer.
- [VersionParsing.jl](https://github.com/JuliaInterop/VersionParsing.jl) : flexible VersionNumber parsing in Julia.
- [Formatting.jl](https://github.com/JuliaIO/Formatting.jl) : A Julia package to provide Python-like formatting support.
- [Format.jl](https://github.com/JuliaString/Format.jl) : This Julia package provides C and Python-style types and functions formatting support.
- [ShortStrings.jl](https://github.com/JuliaString/ShortStrings.jl) : A fast and efficient string format implementation for storing strings of size less than 15 bytes.
- [StringLiterals.jl](https://github.com/JuliaString/StringLiterals.jl : Implement improved )string literals with Swift-style syntax for interpolation, hex, & unicode characters, plus C & Python style formatting and Unicode, HTML, LaTeX, and Emoji entities.
- [StringDistances.jl](https://github.com/matthieugomez/StringDistances.jl) : String Distances in Julia.

### International languages and Unicode tools

- [Gettext](https://github.com/Julia-i18n/Gettext.jl) : An interface to the [gettext](https://www.gnu.org/software/gettext/manual/html_node/index.html) internationalization/translation interface.
- [ICU.jl](https://github.com/JuliaStrings/ICU.jl) : Julia wrapper for the [International Components for Unicode (ICU) libraries](http://site.icu-project.org/).

### Document Processors

[Document Processors](https://en.wikipedia.org/wiki/Document_processor) for Word, Excel, and PDF files.

- [PPTX.jl](https://github.com/ASML-Labs/PPTX.jl) : Generate PowerPoint PPTX files from Julia.
- [Taro.jl](https://github.com/aviks/Taro.jl) : Excel, Word, and PDF documents in Julia.
- [XLSX.jl](https://github.com/felipenoris/XLSX.jl) : Excel file reader/writer coded in pure Julia.
- [ExcelReaders.jl](https://github.com/queryverse/ExcelReaders.jl) : A package that provides functionality to read Excel files.
- [LabelNumerals.jl](https://github.com/sambitdash/LabelNumerals.jl) : Numbers used as labels like page number like alpha, roman numerals or prefixed like A-1,2 etc.
- [PDFIO.jl](https://github.com/sambitdash/PDFIO.jl) : PDF Reader Library for native Julia.
- [OdsIO.jl](https://github.com/sylvaticus/OdsIO.jl) : Open Document Format Spreadsheet (ODS) I/O for Julia using the python [ezodf](https://github.com/T0ha/ezodf) module.
- [WriteDocx.jl](https://github.com/PumasAI/WriteDocx.jl) : A Julia package to create docx files for Microsoft Word from scratch.

### Markdown

[Markdown in Julia stdlib](https://docs.julialang.org/en/v1/stdlib/Markdown/)

- [CommonMark.jl](https://github.com/MichaelHatherly/CommonMark.jl) : A CommonMark-compliant parser for Julia.

### LaTeX

- [Expr2LaTeX.jl](https://github.com/oxinabox/Expr2LaTeX.jl) : Take a julia `Expr` and render it as LaTeX.
- [Handcalcs.jl](https://github.com/co1emi11er2/Handcalcs.jl) : converting Julia calculations into rendered LaTeX.
- [jlcode](https://github.com/wg030/jlcode) : A LaTeX package for displaying Julia code with the listings package.
- [Latexify.jl](https://github.com/korsbo/Latexify.jl) : Convert julia objects to LaTeX equations, arrays or other environments.
- [LatexPrint.jl](https://github.com/scheinerman/LatexPrint.jl) : Print Julia objects in a form suitable for LaTeX mathematics mode.
- [LaTeXStrings.jl](https://github.com/stevengj/LaTeXStrings.jl) : This is a small package to make it easier to type LaTeX equations in string literals in the Julia language.
- [SummaryTables.j](https://github.com/PumasAI/SummaryTables.jl) : A Julia package for creating publication-ready summary tables in HTML, docx, LaTeX and Typst.
- [Tectonic.jl](https://github.com/MichaelHatherly/Tectonic.jl) : Julia interface for the [tectonic](https://github.com/tectonic-typesetting/tectonic) LaTeX engine.
- [VerTeX.jl](https://github.com/chakravala/VerTeX.jl) : typeset scattered graph data rewriter based on LaTeX nodes.

### Citations

- [Bibliography.jl](https://github.com/Humans-of-Julia/Bibliography.jl) : a Julia package for handling both import/export from various bibliographic format (e.g. BibTeX).