---
title: Earth and Space Science
---

> Climate modeling, ecology, cartography, GIS, Meteorology, astrophysicas, astronomy, etc., in Julia.

## Seismology

[Wikipedia: Seismology](https://en.wikipedia.org/wiki/Seismology)

- [JUDI.jl](https://github.com/slimgroup/JUDI.jl): a framework for large-scale seismic modeling and inversion.

## Climatology

- [Wikipedia: Climatology](https://en.wikipedia.org/wiki/Category:Climatology)
- [JuliaClimate](https://github.com/JuliaClimate) organization

---

- [ClimateModels.jl](https://github.com/gaelforget/ClimateModels.jl) : Julia interface to various climate models. [JuliaCon 2023 📺](https://www.youtube.com/watch?v=_Y6mNrN7eWA)
- [ClimateTools.jl](https://github.com/JuliaClimate/ClimateTools.jl) : This package is a collection of commonly-used tools in Climate Science.
- [INMET.jl](https://github.com/JuliaClimate/INMET.jl) : Julia API to access data from the [Instituto Nacional de Metereologia (INMET)](https://portal.inmet.gov.br/).
- [Mimi.jl](https://github.com/mimiframework/Mimi.jl) : Integrated Assessment Modeling Framework for climate change.
- [OptiMimi.jl](https://github.com/jrising/OptiMimi.jl) : Optimization for the `Mimi.jl` modeling framework.
- [SpeedyWeather.jl](https://github.com/SpeedyWeather/SpeedyWeather.jl) : a global spectral atmospheric model with simple physics which is developed as a research playground. [JuliaCon 2023 📺](https://www.youtube.com/watch?v=qgmgg_Bzgyg).

## Ecology

- [Wikipedia: Ecology](https://en.wikipedia.org/wiki/Category:Ecology)
- [EcoJulia](https://github.com/EcoJulia) organization

---

- [Diversity.jl](https://github.com/EcoJulia/Diversity.jl) : Diversity analysis package for Julia, with submodules containing standard ecological and other diversity measures.
- [EcologicalNetworks.jl](https://github.com/EcoJulia/EcologicalNetworks.jl) : Measure various aspects of the structure of ecological networks in Julia.
- [SpeciesDistributionToolkit.jl](https://github.com/PoisotLab/SpeciesDistributionToolkit.jl) : Work with species distributions in Julia.
- [SpatialEcology.jl](https://github.com/EcoJulia/SpatialEcology.jl) : Julia framework for spatial ecology - data types and utilities.

### Aquatic Ecology

- [JuliaOcean](https://github.com/JuliaOcean) organization
- [Modeling Marine Ecosystems At Multiple Scales Using Julia](https://youtu.be/UCIRrXz2ZS0), a workshop @ JuliaCon 2021.

---

- [AIBECS.jl](https://github.com/JuliaOcean/AIBECS.jl) : Algebraic Implicit Biogeochemical Elemental Cycling System (AIBECS) for exploring global marine biogeochemical cycles.
- [OceanRobots.jl](https://github.com/gaelforget/OceanRobots.jl) : simulating data collected by autonomous, remotely operated, or manned vehicles in the Ocean. [JuliaCon 2021 video](https://youtu.be/oC-rikXfVo8)
- [PlanktonIndividuals.jl](https://github.com/JuliaOcean/PlanktonIndividuals.jl) : simulating the behaviors of an ensemble of phytoplankton individuals.

## Geographic information system (GIS)

- [Wikipedia: GIS](https://en.wikipedia.org/wiki/Geographic_information_system)
- [Wikipedia: Cartography](https://en.wikipedia.org/wiki/Category:Cartography)
- [Julia Geo](https://github.com/JuliaGeo)
- [Julia earth](https://github.com/JuliaEarth)

---

- [GDAL.jl](https://github.com/JuliaGeo/GDAL.jl) : Thin Julia wrapper for [GDAL](https://gdal.org/) - Geospatial Data Abstraction Library. See also [ArchGDAL](https://github.com/yeesian/ArchGDAL.jl) for a high level API for `GDAL.jl`.
- [Geodesy.jl](https://github.com/JuliaGeo/Geodesy.jl) : Work with points defined in various coordinate systems.
- [GeoInterface.jl](https://github.com/JuliaGeo/GeoInterface.jl) : A Julia Protocol for Geospatial Data.
- [GeoJSON.jl](https://github.com/JuliaGeo/GeoJSON.jl) : Utilities for working with GeoJSON data in Julia.
- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) : An extensible framework for high-performance geostatistics in Julia.
- [GeoStatsImages.jl](https://github.com/JuliaEarth/GeoStatsImages.jl) : Training images for geostastical simulation.
- [GMT.jl](https://github.com/GenericMappingTools/GMT.jl) :Julia wrapper for the [Generic Mapping Tools](https://github.com/GenericMappingTools/gmt)(GMT).
- [GslibIO.jl](https://github.com/JuliaEarth/GslibIO.jl) : Utilities to read/write extended GSLIB files in Julia.
- [OpenStreetMapPlotter.jl](https://github.com/juliusgeo/OpenStreetMapPlotter.jl) : Plotting focused library for OpenStreetMap data.
- [OpenStreetMapX.jl](https://github.com/pszufe/OpenStreetMapX.jl) : OpenStreetMap support for Julia 1.0. The package can parse `*.osm` and `*.pbf` (contributed by @blegat) files and generate a LightGraphs representation along the metadata. [JuliaCon2021 tutorial](https://pszufe.github.io/OpenStreetMapX_Tutorial/JuliaCon2021/)
- [OpenStreetMapXPlot.jl](https://github.com/pszufe/OpenStreetMapXPlot.jl) : plotting companion for the `OpenStreetMapX.jl` package.
- [Proj.jl](https://github.com/JuliaGeo/Proj.jl) : Julia wrapper for [PROJ](https://proj.org/).4 cartographic projections library.
- [SARProcessing.jl](https://github.com/AIRCentre/SARProcessing.jl): processing of synthetic aperture radar (SAR) data, including loading [Single-Look-Complex][] (SLC) and [Ground-Range-Detected][] (GRD) images, speckle reduction, object detection in SAR image, interferometry, and more. [JuliaCon 2023 📺](https://www.youtube.com/watch?v=HONx0bzFneU)
- [Turf.jl](https://github.com/philoez98/Turf.jl) : A geospatial engine encoding the collections of simple geographical features using the JS lib Turfjs in the GeoJSON format.

[Single-Look-Complex]: https://sentinels.copernicus.eu/web/sentinel/technical-guides/sentinel-1-sar/products-algorithms/level-1-algorithms/single-look-complex
[Ground-Range-Detected]: https://sentinels.copernicus.eu/web/sentinel/technical-guides/sentinel-1-sar/products-algorithms/level-1-algorithms/ground-range-detected

## GPS

- [NMEA.jl](https://github.com/RobBlackwell/NMEA.jl) : Julia package for parsing GPS NMEA messages.

## Aeronautics, Spacecraft, and astrodynamics

- [Wikipedia: Space science](https://en.wikipedia.org/wiki/Outline_of_space_science)
- [Wikipedia: Aeronautics](https://en.wikipedia.org/wiki/Aeronautics)
- [Wikipedia: Astrodynamics (Orbital_mechanics)](https://en.wikipedia.org/wiki/Orbital_mechanics)
- [Julia Space](https://github.com/JuliaSpace)
- [Julia Astro](https://github.com/juliaastro)
- [Julia AstroSim](https://github.com/JuliaAstroSim)

---

- [Airship.jl](https://github.com/ordovician/Airship.jl) : Julia code for performing temperature, pressure and volume and buoyancy calculations.
- [AstrodynamicalModels.jl](https://github.com/cadojo/AstrodynamicalModels.jl) : An extension of `ModelingToolkit.jl` which provides common astrodynamics models.
- [Astrodynamics.jl](https://github.com/JuliaSpace/Astrodynamics.jl) : An astrodynamics library in Julia.
- [GeneralAstrodynamics.jl](https://github.com/cadojo/GeneralAstrodynamics.jl) : Common astrodynamics calculations, plotting, and iterative Halo, Kepler, and Lambert solvers. [Talks on JuliaCon 2021](https://www.youtube.com/watch?v=WnvKaUsGv8w).
- [Orekit.jl](https://github.com/JuliaSpace/Orekit.jl) : Julia wrapper for the [Orekit](https://www.orekit.org) astrodynamics library.
- [ReferenceFrameRotations.jl](https://github.com/JuliaSpace/ReferenceFrameRotations.jl) : Functions related to rotations of coordinate frames, angle2dcm, dcm2angle.
- [SPICE.jl](https://github.com/JuliaAstro/SPICE.jl) : a Julia wrapper for the [SPICE toolkit](https://naif.jpl.nasa.gov/naif/index.html) which is provided by NASA's Navigation and Ancillary Information Facility (NAIF). It provides functionality to read SPICE data files and compute derived observation geometry such as altitude, latitude/longitude and lighting angles.

## Astronomy and astrophysics

- [Wikipedia: Astrophysics](https://en.wikipedia.org/wiki/Astrophysics)
- [Julia space](https://github.com/JuliaSpace)
- [Julia Astro](https://github.com/juliaastro)
- [Julia AstroSim](https://github.com/JuliaAstroSim)

### Algorithms

- [Astro.jl](https://github.com/cormullion/Astro.jl) : Jan Meeus astronomical formulas and some time/date code in Julia.
- [AstroLib.jl](https://github.com/JuliaAstro/AstroLib.jl) : Bundle of small astronomical and astrophysical routines, based on [IDL Astronomy User's Library](http://idlastro.gsfc.nasa.gov/homepage.html) (AstroLib).
- [AstroNbodySim.jl](https://github.com/JuliaAstroSim/AstroNbodySim.jl) : Unitful and differentiable gravitational N-body simulation code in Julia.
- [Cosmology.jl](https://github.com/JuliaAstro/Cosmology.jl) : Cosmology library for Julia.
- [DustExtinction.jl](https://github.com/JuliaAstro/DustExtinction.jl) : Tools for interstellar dust extinction in astronomy
- [ERFA.jl](https://github.com/JuliaAstro/ERFA.jl) : Julia wrapper for [liberfa](https://github.com/liberfa/erfa) (Essential Routines for Fundamental Astronomy), which is based on the [SOFA](http://www.iausofa.org) library.
- [Interplanetary.jl](https://github.com/crbinz/Interplanetary.jl) : Functions for low-fidelity interplanetary navigation and guidance simulations.
- [JPLEphemeris.jl](https://github.com/JuliaAstro/JPLEphemeris.jl) : The JPL Development Ephemerides are the results of simulations of the Solar System used for spacecraft navigation and astronomical purposes.
- [SkyCoords.jl](https://github.com/JuliaAstro/SkyCoords.jl) : Astronomical coordinate systems in Julia.
- [SatelliteToolbox.jl](https://github.com/JuliaSpace/SatelliteToolbox.jl) : A toolbox for satellite analysis written in Julia.
- [WCS.jl](https://github.com/JuliaAstro/WCS.jl) : Astronomical [World Coordinate System](https://www.atnf.csiro.au/people/mcalabre/WCS/) library for Julia.

### Visualizations

- [AstroImages.jl](https://github.com/JuliaAstro/AstroImages.jl) : Plots.jl and Images.jl integration of Astronomical Images ([FITS][]) for Julia.
- [FITSIO.jl](https://github.com/JuliaAstro/FITSIO.jl) : Flexible Image Transport System ([FITS][]) support for Julia.
- [RemoteS.jl](https://github.com/GenericMappingTools/RemoteS.jl) : Remote sensing satellite data processing.
- [Reproject.jl](https://github.com/JuliaAstro/Reproject.jl) : Reproject Astronomical Images from one world coordinate to another.

[FITS]: https://en.wikipedia.org/wiki/FITS
