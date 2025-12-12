---
title: Graphics
created: 2025-12-04, 12:33:20
modified: 2025-12-04, 15:47:40
---

> Computer Vision, Graphics, geometry in Julia.

See also

- [[graph]] for graph theory in mathematics
- [[audio-video]] for videos
- [[visualization]] for visualization libraries

## Organizations

- [Julia Geometry Organization](https://github.com/JuliaGeometry)
- [Julia GL Organization](https://github.com/JuliaGL)
- [Julia Graphics Organization](https://github.com/JuliaGraphics)
- [Julia Images Organization](https://github.com/JuliaImages)

## Image Formats

- [AndorSIF.jl](https://github.com/JuliaIO/AndorSIF.jl) : This implements support for reading [Andor SIF](https://andor.oxinst.com/support/) image files in the Julia programming language. Note: The Andor `.SIF` format changes with each version.
- [FITSIO.jl](https://github.com/JuliaAstro/FITSIO.jl) : Flexible Image Transport System (FITS) support for Julia.
- [ImageIO.jl](https://github.com/JuliaIO/ImageIO.jl) : Load images in Julia.
- [ImageMagick.jl](https://github.com/JuliaIO/ImageMagick.jl) : Thin Wrapper for the library ImageMagick, for general-purpose image saving and loading.
- [Images.jl](https://github.com/JuliaImages/Images.jl) : An image library for Julia.
- [LibImageQuant.jl](https://github.com/ericphanson/LibImageQuant.jl) : Julia wrapper for [libimagequant](https://github.com/ImageOptim/libimagequant) to shrink PNG files.
- [Netpbm.jl](https://github.com/JuliaIO/Netpbm.jl) : Julia support for Netpbm (`.ppm`, `.pgm`, `.pbm`).
- [NRRD.jl](https://github.com/JuliaIO/NRRD.jl) : Julia support for the Nearly Raw Raster Data (`NRRD`) image file format
- [OMETIFF.jl](https://github.com/tlnagy/OMETIFF.jl) : I/O operations for OME-`TIFF` files in Julia with a focus on correctness.
- [QuartzImageIO.jl](https://github.com/JuliaIO/QuartzImageIO.jl) : Thin wrapper around OSX's native image format saving and loading.
- [TiffImages.jl](https://github.com/tlnagy/TiffImages.jl) : Pure-Julia TIFF I/O.

## Bindings for external libraries

- [Cairo.jl](https://github.com/JuliaGraphics/Cairo.jl) : Bindings to the [Cairo](https://www.cairographics.org/) graphics library.
- [DevIL.jl](https://github.com/JuliaGL/DevIL.jl) : [DevIL](https://github.com/DentonW/DevIL) / OpenIL binding for Julia.
- [FreeType.jl](https://github.com/JuliaGraphics/FreeType.jl) : Font FreeType 2 bindings API wrapper. See also [FreeTypeAbstraction.jl](https://github.com/JuliaGraphics/FreeTypeAbstraction.jl)
- [MeshCat.jl](https://github.com/rdeits/MeshCat.jl) : Julia bindings to the MeshCat WebGL viewer.
- [MiniFB.jl](https://github.com/aviks/MiniFB.jl) : A Julia wrapper around https://github.com/emoon/minifb , a small cross platform library that makes it easy to render 32 bit pixels in a window.
- [ModernGL.jl](https://github.com/JuliaGL/ModernGL.jl) : OpenGL 3+ bindings for Julia.
- [OCReract.jl](https://github.com/leferrad/OCReract.jl) : A simple Julia wrapper for [Tesseract](https://tesseract-ocr.github.io/tessdoc/Installation.html) OCR.
- [OpenCV.jl](https://github.com/JuliaImages/OpenCV.jl) : [OpenCV](https://docs.opencv.org/) in Julia. [Introduction to Julia OpenCV Binding](https://docs.opencv.org/4.x/d8/da4/tutorial_julia.html).
- [Skia.jl](https://github.com/stensmo/Skia.jl) : Support for the [Skia](https://skia.org/) library in Julia.
- [Vulkan.jl](https://github.com/JuliaGPU/Vulkan.jl) : Wrapper of Vulkan, Khronos next generation OpenGL API.
- [XCB.jl](https://github.com/JuliaGL/XCB.jl) : [XCB](https://xcb.freedesktop.org/) windowing library wrapper.

## Computer Vision (CV)

[Wikipedia: Computer Vision](https://en.wikipedia.org/wiki/Category:Computer_vision)

- [ActiveAppearanceModels.jl](https://github.com/dfdx/ActiveAppearanceModels.jl) : Active Appearance Models.
- [Bezier.jl](https://github.com/dronir/Bezier.jl) : Julia functions for computing a Bezier curve.
- [ColorBrewer.jl](https://github.com/JuliaGraphics/ColorBrewer.jl) : A Julia library for generating color brewer color schemes.
- [ConstructiveSolidGeometry.jl](https://github.com/jtramm/ConstructiveSolidGeometry.jl) : A Constructive Solid Geometry (CSG) and ray tracing package for Julia.
- [Contour.jl](https://github.com/JuliaGeometry/Contour.jl) : Calculating contour curves for 2D scalar fields in Julia.
- [Fontconfig.jl](https://github.com/JuliaGraphics/Fontconfig.jl) : provides basic binding to [fontconfig](https://www.freedesktop.org/wiki/Software/fontconfig/).
- [Luxor.jl](https://github.com/JuliaGraphics/Luxor.jl) : an easy-to-use sugary coating in Julia for the Cairo graphics package.
- [Porta.jl](https://github.com/iamazadi/Porta.jl) : This project helps with Eric Weinstein's the Graph-Wall-Tome (GWT) project.

### Image Processing

- [ImageClipboard.jl](https://github.com/hyrodium/ImageClipboard.jl) : Copy and Paste images with Julia.
- [ImageFeatures.jl](https://github.com/JuliaImages/ImageFeatures.jl) : Image feature detection for Julia.
- [ImageProjectiveGeometry.jl](https://github.com/peterkovesi/ImageProjectiveGeometry.jl) : Projective geometry for computer vision in Julia.
- [ImageQuilting.jl](https://github.com/JuliaEarth/ImageQuilting.jl) : Image quilting for texture synthesis in Julia .
- [ImageSegmentation.j](https://github.com/JuliaImages/ImageSegmentation.jl) : Partitioning images into meaningful regions.
- [ImageView.j](https://github.com/JuliaImages/ImageView.jl) : Interactive display of images and movies.
- [MeshIO.jl](https://github.com/JuliaIO/MeshIO.jl) : IO for Meshes.
- [RegisterQD.jl](https://github.com/HolyLab/RegisterQD.jl) : It performs image registration using the global optimization routine `QuadDIRECT.jl`. Unlike many other registration packages, this is not "greedy" descent based on an initial guess---it attempts to find the globally-optimal alignment of your images.
- [SubpixelRegistration.jl](https://github.com/JuliaHCI/SubpixelRegistration.jl) : Efficient subpixel image registration algorithm implementation that allows you to register arrays of arbitrary dimensions (not just 2d). Functions are written for AbstractArrays and should work for Images.
- [TestImages.j](https://github.com/JuliaImages/TestImages.jl) : Loading standard test images into Julia.

### Vector Graphics

[Wikipedia: Vector Graphics](https://en.wikipedia.org/wiki/Category:Vector_graphics)

- [Compose.jl](https://github.com/GiovineItalia/Compose.jl) : Compose is a vector graphics library for Julia. [Gadfly.jl](https://github.com/GiovineItalia/Gadfly.jl) is built upon this package.
- [ImageCore.jl](https://github.com/JuliaImages/ImageCore.jl) : Julia types for representing images.
- [Rsvg.jl](https://github.com/lobingera/Rsvg.jl) : An adaptation of the [librsvg](https://wiki.gnome.org/Projects/LibRsvg) to render SVG to Cairo surfaces.
- [TikzGraphs.jl](https://github.com/JuliaTeX/TikzGraphs.jl) : Graph layout package using algorithms built into [PGF/TikZ 3.0+](https://www.ctan.org/pkg/pgf).
- [TikzPictures.jl](https://github.com/JuliaTeX/TikzPictures.jl) : Library interface to PGF/TikZ, that allows one to create PGF/TikZ pictures and images can be saved as PDF, SVG, and TEX. If using IJulia, it will output SVG images.

## Geometry

- [Wikipedia: Geometry](https://en.wikipedia.org/wiki/Geometry)
- [Wikipedia: Algebraic Geometry](https://en.wikipedia.org/wiki/Category:Algebraic_geometry)
- [Wikipedia: Computational Geometry](https://en.wikipedia.org/wiki/Computational_geometry)
- [Wikipedia: Discrete Geometry](https://en.wikipedia.org/wiki/Category:Discrete_geometry)
- [Wikipedia: Solid Geometry](https://en.wikipedia.org/wiki/Solid_geometry)

---

- [CDDLib.jl](https://github.com/JuliaPolyhedra/CDDLib.jl) : A wrapper for [cdd](https://www.inf.ethz.ch/personal/fukudak/cdd_home/), the library for polyhedra manipulation such as double description and Fourier-Motzkin elimination. This module can either be used in a **lower level** using the API of cdd or using the higher level interface of Polyhedra.jl.
- [CliffordNumbers.jl](https://github.com/brainandforce/CliffordNumbers.jl) : a simple, statically sized multivector (Clifford number) implementation for Julia. [JuliaCon 2025](https://youtu.be/F1p5naXstns)
- [ConvexHull.jl](https://github.com/JuliaPolyhedra/ConvexHull.jl) : A Julia library for polyhedral computations.
- [CoordinateTransformations.jl](https://github.com/JuliaGeometry/CoordinateTransformations.jl) : A fresh approach to coordinate transformations.
- [Descartes.jl](https://github.com/JuliaGeometry/Descartes.jl) : A research project into the representation of solid geometry.
- [Ganja.jl](https://github.com/chakravala/Ganja.jl) : Visualization for geometric algebra, not just algebra, using [ganja.js](https://github.com/enkimute/ganja.js)
- [GeometricalPredicates.jl](https://github.com/JuliaGeometry/GeometricalPredicates.jl) : Fast, robust 2D and 3D geometrical predicates on generic point types. Implementation follows algorithms described in the Arepo paper and used (for e.g.) in the Illustris Simulation.
- [GeometryOps.](https://github.com/JuliaGeo/GeometryOps.jl) : a package for geometric calculations on (primarily 2D) geometries. [JuliaCon 2024 video](https://github.com/JuliaGeo/GeometryOps.jl)
- [GeometryTypes.j](https://github.com/JuliaGeometry/GeometryTypes.jl) : Geometry types and for Julia, based on FixedSizeArrays.
- [Grassmann.jl](https://github.com/chakravala/Grassmann.jl) : ⟨Leibniz-Grassmann-Clifford-Hestenes⟩ differential geometric algebra / multivector simplical complex.
- [ImageFiltering.jl](https://github.com/JuliaImages/ImageFiltering.jl) : ImageFiltering implements blurring, sharpening, gradient computation, and other linear filtering operations, as well nonlinear filters like min/max.
- [ImageMorphology.j](https://github.com/JuliaImages/ImageMorphology.jl) : This package provides morphology-related functionality to the `Images.jl` project.
- [LRSLib.jl](https://github.com/JuliaPolyhedra/LRSLib.jl) : A wrapper for `lrs`.
- [Meshes.jl](https://github.com/JuliaGeometry/Meshes.jl) : Generation and manipulation of triangular meshes for a type of polygon mesh in computer graphics.
- [OctTrees.jl](https://github.com/JuliaGeometry/OctTrees.jl) : Fast quad and oct-trees.
- [Polyhedra.jl](https://github.com/JuliaPolyhedra/Polyhedra.jl) : It provides an unified interface for Polyhedra Manipulation Libraries such as `CDDLib.jl`.
- [QHull.jl](https://github.com/JuliaPolyhedra/QHull.jl) : A Julia wrapper around a PyCall wrapper around the qhull Convex Hull library.
- [RayTraceEllipsoid.jl](https://github.com/JuliaGeometry/RayTraceEllipsoid.jl) : Ray trace ellipsoid-shaped domes i.e. finds intersection points and refract/reflect according to the refractive indices.
- [Rotations.j](https://github.com/JuliaGeometry/Rotations.jl) : Implementations for various 3D rotation parametrizations.
- [SignedDistanceFields.j](https://github.com/JuliaGraphics/SignedDistanceFields.jl) : Simple and efficient SDF calculation.
- [TetGen.jl](https://github.com/JuliaGeometry/TetGen.jl) : [TetGen](https://wias-berlin.de/software/index.jsp?id=TetGen) wrapper.
- [TriangleIntersect.jl](https://github.com/JuliaGeometry/TriangleIntersect.jl) : Fast ray-triangle intersections for ray tracing.
- [VoronoiCells.jl](https://github.com/JuliaGeometry/VoronoiCells.jl) : Manipulate Voronoi cells in 2D.
- [VoronoiDelaunay.jl](https://github.com/JuliaGeometry/VoronoiDelaunay.jl) : Fast and robust Voronoi & Delaunay tessellation creation with Julia.

## Misc

[julia-logo-graphics](https://github.com/JuliaLang/julia-logo-graphics) : official versions of the Julia logo.

---

- [FIGlet.jl](https://github.com/kdheepak/FIGlet.jl) : Fonts port of FIGlet, doing ASCII Art.
