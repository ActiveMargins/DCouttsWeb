---
title: 'R libraries for geoscience'
author: Danny
date: '2021-02-28'
slug: []
categories:
  - Blog
tags:
  - Geology
  - R
subtitle: 'Trolling through CRAN finding all the geoscience related libraries'
description: 'There is a great deal of fantastic geoscience-related code on CRAN that is a few keystrokes away. I did the hard part, look through 6000+ packages on CRAN. Now can do the fun part, use this code to do better geoscience!'
---

![alt="GEOSCIENCE IN R" ](/img/2021_2_28-R-basedGeoscience/TopImage.jpg)

## R libraries for geoscience 
In a chat with another data-oriented geologist, they mentioned a popular R package for geochemistry data (rgr) that I had not heard of. After looking in to rgr a decided to troll through the list of current CRAN packages and find all the geoscience related packages.

For non-R programmers, the Comprehensive R Archive Network (CRAN) is the main repository for R packages. Packages listed on CRAN (about 17 206 of them) are tested daily on multiple systems to check for dependency issues as other packages in the R environment are updated. Packages on CRAN have been more-or-less “peer-reviewed”, unit tested, and have standardized documentation. It is a fantastic resource that benefits the entire R community.

While going through the list of packages on CRAN I was blown away by the diversity of geoscience-related packages that are available. In this list I also wanted to highlight which packages have datasets built into the package. In my pursuit to develop stronger data analysis/science skills, having a variety of datasets on hand to play with is pretty handy. 

### General Geology and Mapping
- [geoscale](https://cran.r-project.org/web/packages/geoscale/index.html) - geological Time Scale Plotting
- [GEOmap](https://cran.r-project.org/web/packages/GEOmap/index.html) - Topographic and geologic mapping - *datasets included*
- [geomapdata](https://cran.r-project.org/web/packages/geomapdata/index.html) - Set of data for use in package GEOmap - *datasets included*
- [Globe](https://cran.r-project.org/web/packages/globe/index.html) - Plot 2D and 3D Views of the Earth - *datasets included*
- [terrainr](https://cran.r-project.org/web/packages/terrainr/index.html) - Landscape Visualizations in R and 'Unity'
- [terrainmeshr](https://cran.r-project.org/web/packages/terrainmeshr/index.html) - Triangulate and simplify 3D terrain meshes
- [RSAGA](https://cran.r-project.org/web/packages/RSAGA/index.html) - SAGA geoprocessing and terrain analysis - *datasets included*
- [rayshader](https://cran.r-project.org/web/packages/rayshader/index.html) - Create Maps and Visualize Data in 2D and 3D
- [earthtones](https://cran.r-project.org/web/packages/earthtones/index.html) - Derive a color palette from a particular location on Earth

### Geochemistry
- [rgr](https://cran.r-project.org/web/packages/rgr/index.html) - Applied geochemistry exploratory data analysis
- [isoplotR](https://cran.r-project.org/web/packages/IsoplotR/index.html) - Statistical toolbox for radiometric geochronology - *datasets included*
- [OrgMassSpecR](https://cran.r-project.org/web/packages/OrgMassSpecR/index.html) - Organic/biological mass spectrometry data analysis
- [CHNOSZ](https://cran.r-project.org/web/packages/CHNOSZ/index.html) - Thermodynamic calculations and diagrams for geochemistry

### Geostatistics
- [geotoolsR](https://cran.r-project.org/web/packages/geotoolsR/index.html) - Tools to improve the use of geostatistic
- [georob](https://cran.r-project.org/web/packages/georob/index.html) - Robust geostatistical analysis of spatial data - *datasets included*
- [gear](https://cran.r-project.org/web/packages/gear/index.html) - Geostatistical analysis in R - *datasets included*
- [gstat](https://cran.r-project.org/web/packages/gstat/index.html) - Spatial and spatio-temporal geostatistical modelling, prediction, and simulation - *datasets included*
- [geostats](https://cran.r-project.org/web/packages/geostats/index.html) - An introduction to statistics for geoscientists - *datasets included*

### Hydrology
- [GWSDAT](https://cran.r-project.org/web/packages/GWSDAT/index.html) - Groundwater spatiotemporal data analysis tool - **includes RShiny data exploration tool!**
- [streamDepletr](https://cran.r-project.org/web/packages/streamDepletr/index.html) - Estimate streamflow depletion due to groundwater pumping - *datasets included*
- [GlacierSMBM](https://cran.r-project.org/web/packages/glacierSMBM/index.html) - Glacier surface mass balance model - *datasets included*


### Oil and Gas
- [Rmbal](https://cran.r-project.org/web/packages/Rmbal/index.html) - Estimate original hydrocarbon in place and reservoir performance
- [Rpvt](https://cran.r-project.org/web/packages/Rpvt/index.html) - Estimate the PVT properties of reservoir fluids

### Paleontology
- [velociraptr](https://cran.r-project.org/web/packages/velociraptr/index.html) - Functions for downloading, cleaning, and analyzing fossil data from the Paleobiology Database
- [paleobioDB](https://cran.r-project.org/web/packages/paleobioDB/index.html) - Download and process data from the paleobiology batabase
- [fossil](https://cran.r-project.org/web/packages/fossil/index.html) - Palaeoecological and palaeogeographical analysis tools - *datasets included*
- [FossilSim](https://cran.r-project.org/web/packages/FossilSim/index.html) - Simulating taxonomy and fossil data on phylogenetic trees under mechanistic models of speciation, preservation and sampling
- [strap](https://cran.r-project.org/web/packages/strap/index.html) - Stratigraphic tree analyiss for paleontology - *datasets included*
- [folio](https://cran.r-project.org/web/packages/folio/index.html) - Datasets for teaching archaeology and paleontology - *datasets included*
- [chronosphere](https://cran.r-project.org/web/packages/chronosphere/index.html) - A package to facilitate spatially explicit analyses of (paleo)environmental/ecological research - *datasets included*

### Provenance Analysis
- [fingerPro](https://cran.r-project.org/web/packages/fingerPro/index.html) - Sediment source fingerprinting
- [provenance](https://cran.r-project.org/web/packages/provenance/index.html) - Statistical toolbox for sedimentary provenance analysis - *datasets included*
- [isoplotR](https://cran.r-project.org/web/packages/IsoplotR/index.html) - Statistical toolbox for radiometric geochronology

### Seismicity
- [ETAS](https://cran.r-project.org/web/packages/ETAS/index.html) - Modeling earthquake data using 'ETAS' model *datasets included*
- [bayesainETAS](https://cran.r-project.org/web/packages/bayesianETAS/index.html) - Bayesian estimation of the ETAS model for earthquake occurrences
- [GRTo](https://cran.r-project.org/web/packages/GRTo/index.html) - Tools for the analysis of Gutenberg-Richter distributions of earthquake magnitudes
- [TauP.R](https://cran.r-project.org/web/packages/TauP.R/index.html) - Earthquake traveltime calculations for 1D earth models - *datasets included*


### Stratigraphy
- [stratigrapheR](https://cran.r-project.org/web/packages/StratigrapheR/index.html) - Integrated stratigraphy tools for plotting stratigraphic data
- [SDAR](https://cran.r-project.org/web/packages/SDAR/index.html) - A tool for plotting and facilitating the analysis of stratigraphic and sedimentological data - *includes datasets*
- [coreCT](https://cran.r-project.org/web/packages/coreCT/index.html) - Programmatic analysis of sediment cores using computed tomography imaging - *includes datasets*
- [G2sd](https://cran.r-project.org/web/packages/G2Sd/index.html) - Grain-size statistics and description of sediment - *includes datasets*
- [EMMAgeo](https://cran.r-project.org/web/packages/EMMAgeo/index.html) - End-member modelling of grain-size data
- [DecomposeR](https://cran.r-project.org/web/packages/DecomposeR/index.html) - Empirical model decomposition for cyclostratigraphy


### Structural Geology
- [RockFab](https://cran.r-project.org/web/packages/RockFab/index.html) - Rock fabric and strain analysis tools

## For those learning R
For those who do not know R but may have found a package that interests them, I suggest you check out the [“swirl” package](https://cran.r-project.org/web/packages/swirl/index.html) that allows you to learn R in R! swirl was built by a student at Johns Hopkins University and houses a lot of different coursers ranging from introduction to R, data cleaning, visualization in R, and all the way to inferential statistics and regression models. I’ve used swirl in Coursera’s/John Hopkins Biostatistics’ “Data Science in R” course series – it’s fantastic.

For those looking to pick up basic R then blast right into more complex topics like geostatistics, there is the [“geostats” package](https://cran.r-project.org/web/packages/geostats/index.html) by Pieter Vermeesch. This package is the companion code and datasets for a course run at University College London. The CRAN repository has a link to a short .pdf textbook for the course, which includes a short introduction to R. The .pdf textbook also has exercises for each chapter that use datasets built into the package.

## For those looking for datasets to play with
### Geoscience-related datasets
As I said up top, having a variety of datasets to play around with is fantastic. I wanted to highlight the packages that are chalked full of datasets that could be used by others to develop their skills or are teaching R basics and wanted datasets that are more geoscience focused than mtcars…
provenance – A large provenance dataset composed of detrital zircon ages, compositional bulk petrography data, heavy mineral composition, and major and trace element data.

[folio](https://cran.r-project.org/web/packages/folio/index.html) – Datasets for teaching quantitative approaches and modeling in archaeology and paleontology. Geological datasets include ice core data, δ18O data foram and sea level data. The archeological datasets, however, are very interesting radiocarbon dating examples and trace element data from ancient ceramics.

[“geostats” package](https://cran.r-project.org/web/packages/geostats/index.html) – geostats includes 23 different datasets that are all used in examples/exercise throughout the .pdf textbook. Some highlights are:
- AFM - 630 calc-alkali basalts from the Cascade Mountains and 474 tholeiitic basalts from Iceland
declustered - 28267 earthquakes between 1769 and 2016, with aftershocks and precursor events removed
- DZ – Detrital zircon U-Pb data of 13 sand samples from China.
- forams – Planktic foraminifera counts in surface sediments in the Atlantic Ocean
fractures – A 512 × 512 pixel image of a fracture network.

[strap](https://cran.r-project.org/web/packages/strap/index.html) – a package for building, analyzing, and visualizing phylogenic trees of taxa. It includes family trees of lungfish (dipnoans), trilobites (Asaphidae), and a structured version of regional stages for the Ordovician in Britain. 

### Non-geoscience related
For non-geoscience-related datasets there three main packages that contain classic datasets. An advantage of using these is that are you can easily find multiple solutions to a single dataset and see how people approached and dissected these problems. The main packages composed of datasets are: 
- [datasets](https://cran.r-project.org/web/packages/datasets.load/index.html) – A package of datasets including cars, ChickWeight, and AirPassengers.
- [MASS](https://cran.r-project.org/web/packages/MASS/index.html) – A package functions and datasets to support the textbook “Modern Applied Statistics with S” (Venables and Ripley, 2002).
- [mlbench](https://cran.r-project.org/web/packages/mlbench/index.html) – A packages that includes benchmark datasets for machine learning. It includes classic datasets like BostonHousing, Ionosphere, and BreastCancer.
