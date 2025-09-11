---
title: Graphics
---

> Computer Vision, Graphics, games, geometry in Julia.

- [Julia Geometry Organization](https://github.com/JuliaGeometry)
- [Julia GL Organization](https://github.com/JuliaGL)
- [Julia Graphics Organization](https://github.com/JuliaGraphics)
- [Julia Images Organization](https://github.com/JuliaImages)

From graph theory in mathematics, see [[graph]].

## File IO

See [[fileio]].

## Computer Vision (CV)

[Wikipedia: Computer Vision](https://en.wikipedia.org/wiki/Category:Computer_vision)

- https://github.com/aviks/MiniFB.jl : A Julia wrapper around https://github.com/emoon/minifb , a small cross platform library that makes it easy to render 32 bit pixels in a window.
- https://github.com/dfdx/ActiveAppearanceModels.jl : Active Appearance Models.
- https://github.com/dronir/Bezier.jl : Julia functions for computing a Bezier curve.
- https://github.com/iamazadi/Porta.jl : This project helps with Eric Weinstein's the Graph-Wall-Tome (GWT) project.
- https://github.com/jtramm/ConstructiveSolidGeometry.jl : A Constructive Solid Geometry (CSG) and ray tracing package for Julia.
- https://github.com/JuliaGeometry/Contour.jl : Calculating contour curves for 2D scalar fields in Julia.
- https://github.com/JuliaGL/DevIL.jl : https://github.com/DentonW/DevIL / OpenIL binding for Julia.
- https://github.com/JuliaGraphics/Cairo.jl : Bindings to the [Cairo](https://www.cairographics.org/) graphics library.
- https://github.com/JuliaGraphics/ColorBrewer.jl : A Julia library for generating color brewer color schemes.
- https://github.com/JuliaGraphics/Fontconfig.jl : provides basic binding to [fontconfig](https://www.freedesktop.org/wiki/Software/fontconfig/).
- https://github.com/JuliaGraphics/Luxor.jl : an easy-to-use sugary coating in Julia for the Cairo graphics package.
- https://github.com/JuliaPlots/VisualRegressionTests.jl : Automated integrated regression tests for graphics libraries.
- https://github.com/peterkovesi/PerceptualColourMaps.jl : Perceptually Uniform Color Maps for Julia.
- https://github.com/rened/ShapeModels.jl : Statistical shape models / point distribution models.
- https://github.com/shashi/Reel.jl : Computations caught on camera.
- https://github.com/stensmo/Skia.jl : Support for the [Skia](https://skia.org/) library in Julia.
- https://github.com/timholy/HalideCall.jl : Use shared libraries created by Halide from Julia.

### Image Processing

- https://github.com/HolyLab/RegisterQD.jl : It performs image registration using the global optimization routine `QuadDIRECT.jl`. Unlike many other registration packages, this is not "greedy" descent based on an initial guess---it attempts to find the globally-optimal alignment of your images.
- https://github.com/hyrodium/ImageClipboard.jl : Copy and Paste images with Julia.
- https://github.com/JuliaEarth/ImageQuilting.jl : Image quilting for texture synthesis in Julia .
- https://github.com/JuliaHCI/SubpixelRegistration.jl : Efficient subpixel image registration algorithm implementation that allows you to register arrays of arbitrary dimensions (not just 2d). Functions are written for AbstractArrays and should work for Images.
- https://github.com/JuliaImages/ImageFeatures.jl : Image feature detection for Julia.
- https://github.com/JuliaImages/ImageSegmentation.jl : Partitioning images into meaningful regions.
- https://github.com/JuliaImages/ImageView.jl : Interactive display of images and movies.
- https://github.com/JuliaImages/TestImages.jl : Loading standard test images into Julia.
- https://github.com/JuliaIO/MeshIO.jl : IO for Meshes.
- https://github.com/peterkovesi/ImageProjectiveGeometry.jl : Projective geometry for computer vision in Julia.

### OpenCV API

- https://github.com/JuliaImages/OpenCV.jl : [OpenCV](https://docs.opencv.org/) in Julia. [Introduction to Julia OpenCV Binding](https://docs.opencv.org/4.x/d8/da4/tutorial_julia.html).

### OpenGL and Vulkan API

- https://github.com/JuliaGL/ModernGL.jl : OpenGL 3+ bindings for Julia.
- https://github.com/JuliaGPU/Vulkan.jl : Wrapper of Vulkan, Khronos next generation OpenGL API.
- https://github.com/rdeits/MeshCat.jl : Julia bindings to the MeshCat WebGL viewer.

### Vector Graphics

[Wikipedia: Vector Graphics](https://en.wikipedia.org/wiki/Category:Vector_graphics)

- https://github.com/GiovineItalia/Compose.jl : Compose is a vector graphics library for Julia. <https://github.com/GiovineItalia/Gadfly.jl> is built upon this package.
- https://github.com/JuliaImages/ImageCore.jl : Julia types for representing images.
- https://github.com/JuliaTeX/TikzGraphs.jl : Graph layout package using algorithms built into [PGF/TikZ 3.0+](https://www.ctan.org/pkg/pgf).
- https://github.com/JuliaTeX/TikzPictures.jl : Library interface to PGF/TikZ, that allows one to create PGF/TikZ pictures and images can be saved as PDF, SVG, and TEX. If using IJulia, it will output SVG images.
- https://github.com/lobingera/Rsvg.jl : An adaptation of the [librsvg](https://wiki.gnome.org/Projects/LibRsvg) to render SVG to Cairo surfaces.

### OCR

- https://github.com/leferrad/OCReract.jl : A simple Julia wrapper for [Tesseract](https://tesseract-ocr.github.io/tessdoc/Installation.html) OCR.

## Geometry

- [Wikipedia: Geometry](https://en.wikipedia.org/wiki/Geometry)
- [Wikipedia: Algebraic Geometry](https://en.wikipedia.org/wiki/Category:Algebraic_geometry)
- [Wikipedia: Computational Geometry](https://en.wikipedia.org/wiki/Computational_geometry)
- [Wikipedia: Discrete Geometry](https://en.wikipedia.org/wiki/Category:Discrete_geometry)
- [Wikipedia: Solid Geometry](https://en.wikipedia.org/wiki/Solid_geometry)

---

- https://github.com/chakravala/Ganja.jl : Visualization for geometric algebra, not just algebra, using https://github.com/enkimute/ganja.js
- https://github.com/chakravala/Grassmann.jl : ⟨Leibniz-Grassmann-Clifford-Hestenes⟩ differential geometric algebra / multivector simplical complex.
- https://github.com/JuliaGeometry/CoordinateTransformations.jl : A fresh approach to coordinate transformations.
- https://github.com/JuliaGeometry/Descartes.jl : A research project into the representation of solid geometry.
- https://github.com/JuliaGeo/GeometryOps.jl : a package for geometric calculations on (primarily 2D) geometries. [JuliaCon 2024 video](https://github.com/JuliaGeo/GeometryOps.jl)
- https://github.com/JuliaGeometry/GeometricalPredicates.jl : Fast, robust 2D and 3D geometrical predicates on generic point types. Implementation follows algorithms described in the Arepo paper and used (for e.g.) in the Illustris Simulation.
- https://github.com/JuliaGeometry/GeometryTypes.jl : Geometry types and for Julia, based on FixedSizeArrays.
- https://github.com/JuliaGeometry/Meshes.jl : Generation and manipulation of triangular meshes for a type of polygon mesh in computer graphics.
- https://github.com/JuliaGeometry/OctTrees.jl : Fast quad and oct-trees.
- https://github.com/JuliaGeometry/RayTraceEllipsoid.jl : Ray trace ellipsoid-shaped domes i.e. finds intersection points and refract/reflect according to the refractive indices.
- https://github.com/JuliaGeometry/Rotations.jl : Implementations for various 3D rotation parametrizations.
- https://github.com/JuliaGeometry/TetGen.jl : [TetGen](https://wias-berlin.de/software/index.jsp?id=TetGen) wrapper.
- https://github.com/JuliaGeometry/TriangleIntersect.jl : Fast ray-triangle intersections for ray tracing.
- https://github.com/JuliaGeometry/VoronoiCells.jl : Manipulate Voronoi cells in 2D.
- https://github.com/JuliaGeometry/VoronoiDelaunay.jl : Fast and robust Voronoi & Delaunay tessellation creation with Julia.
- https://github.com/JuliaGraphics/SignedDistanceFields.jl : Simple and efficient SDF calculation.
- https://github.com/JuliaImages/ImageFiltering.jl : ImageFiltering implements blurring, sharpening, gradient computation, and other linear filtering operations, as well nonlinear filters like min/max.
- https://github.com/JuliaImages/ImageMorphology.jl : This package provides morphology-related functionality to the `Images.jl` project.
- https://github.com/JuliaPolyhedra/CDDLib.jl : A wrapper for cdd, the library for polyhedra manipulation such as double description and Fourier-Motzkin elimination. This module can either be used in a **lower level** using the API of cdd or using the higher level interface of Polyhedra.jl.
- https://github.com/JuliaPolyhedra/ConvexHull.jl : A Julia library for polyhedral computations.
- https://github.com/JuliaPolyhedra/LRSLib.jl : A wrapper for `lrs`.
- https://github.com/JuliaPolyhedra/Polyhedra.jl : It provides an unified interface for Polyhedra Manipulation Libraries such as `CDDLib.jl`.
- https://github.com/JuliaPolyhedra/QHull.jl : A Julia wrapper around a PyCall wrapper around the qhull Convex Hull library.

## Games

- https://github.com/aviks/GameZero.jl : Zero overhead game development library for the Julia programming language.
- https://github.com/ChristianKurz/REPLTetris.jl : A small Tetris-implementation to be used directly form the Julia REPL.
- https://github.com/JuliaML/AtariAlgos.jl : Models/algorithms for use with the Arcade Learning Environment (ALE).
- https://github.com/JuliaMultimedia/CSFML.jl : Julia wrapper for CSFML, the official binding of https://github.com/SFML/SFML for C, a simple, fast, cross-platform and object-oriented multimedia API.
- https://github.com/JuliaMultimedia/SimpleDirectMediaLayer.jl : Bindings for the Simple DirectMedia Layer ([SDL](https://www.libsdl.org/)) library.
- https://github.com/JuliaReinforcementLearning/ArcadeLearningEnvironment.jl : This package is a Julia wrapper for https://github.com/mgbellemare/Arcade-Learning-Environment .
- https://github.com/Kyjor/JulGame.jl : JulGame is a game engine based on the Julia programming language with the help of SDL2.
- https://github.com/romstad/Chess.jl : Julia chess programming library.
- https://github.com/sebastianpech/JuliaKara.jl : A julia port of the learning environment [Kara](https://www.swisseduc.ch/informatik/karatojava/).
- https://github.com/xiaodaigh/Game2048.jl : Simulation of the game 2048 in Julia. The base package is https://github.com/xiaodaigh/Game2048Core.jl .
- https://kyjor.itch.io/super-mango-julia : Super Mango is a short 2D platformer game crafted with the Julia programming language, which was created as an example for all of https://github.com/Kyjor/JulGame.jl.
- https://github.com/Gesee-y/ReactiveECS.jl : Building high-performance, modular, and reactive simulations, with a focus on game development and scientific applications. [Julia forum thread](https://discourse.julialang.org/t/reactiveecs-jl-v2-0-0-breaking-changes-for-massive-performance-boosts/130564/1)
- https://github.com/Gesee-y/Cruise.jl : A modular Game engine in Julia. [Julia forum thread](https://discourse.julialang.org/t/cruise-v0-1-0-a-julia-game-engine/130708)

## Misc

[julia-logo-graphics](https://github.com/JuliaLang/julia-logo-graphics) : official versions of the Julia logo.

---

- https://github.com/kdheepak/FIGlet.jl : Fonts port of FIGlet, doing ASCII Art.
- https://github.com/JuliaGraphics/FreeType.jl : Font FreeType 2 bindings API wrapper. See also https://github.com/JuliaGraphics/FreeTypeAbstraction.jl
- https://github.com/JuliaGL/XCB.jl : [XCB](https://xcb.freedesktop.org/) windowing library wrapper.
