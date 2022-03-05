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

![alt="GEOSCIENCE IN R" ](/img/2021_2_28-R-basedGeoscience/TopImage.png)

## R libraries for geoscience 
In a chat with another data-oriented geologist, they mentioned a popular R package for geochemistry data (rgr) that I had not heard of. After looking in to rgr a decided to troll through the list of current CRAN packages and find all the geoscience related packages. Again, this is just at list of the libraries that are up-to-date on CRAN, others may have not been kept up to date, but that doesn't mean we can't rally support for them. Additionally, I would be interested to learn about libraries hosted other repositories (e.g., GitHub). **If I've missed a R library that you use or know of, let me know! I would love to make the a more complete list!**

For non-R programmers, the Comprehensive R Archive Network (CRAN) is the main repository for R packages. Packages listed on CRAN (about 17206 of them) are tested daily on multiple systems to check for dependency issues as other packages in the R environment are updated. These have been more-or-less “peer-reviewed” by R experts, unit tested, and have standardized documentation. It is a fantastic resource that benefits the entire R community.

While going through the list of packages on CRAN I was blown away by the diversity of geoscience-related packages that are available. In this list I also wanted to highlight which packages have datasets built into the package. In my pursuit to develop stronger data analysis/science skills, having a variety of datasets on hand to play with is pretty handy. 

### General geoscience and mapping
- [geoscale](https://cran.r-project.org/web/packages/geoscale/index.html) - geological time scale plotting
- [astrochron](https://cran.r-project.org/web/packages/astrochron/index.html) - a package for conducting, and learning about: (1) paleoclimate time series analysis, (2) astronomical time scale construction, and (3) the statistical integration of astrochronologies with other geochronologic/chronostratigraphic data.
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
- [GeoChemical Data ToolKIT](http://www.gcdkit.org/download) - The GeoChemical Data ToolKIT, or in short GCDkit, is a system for handling and recalculation of whole-rock analyses from igneous rocks. It is written in R, a language and environment for statistical computing and graphics. 
- [OrgMassSpecR](https://cran.r-project.org/web/packages/OrgMassSpecR/index.html) - Organic/biological mass spectrometry data analysis
- [CHNOSZ](https://cran.r-project.org/web/packages/CHNOSZ/index.html) - Thermodynamic calculations and diagrams for geochemistry
- [ggtern](https://cran.r-project.org/web/packages/ggtern/index.html) - An extension to 'ggplot2', for the creation of ternary diagrams - *datasets included*
- [phreeqc](https://cran.r-project.org/web/packages/phreeqc/index.html) - R Interface to Geochemical Modeling Software

### Geostatistics
- [geotoolsR](https://cran.r-project.org/web/packages/geotoolsR/index.html) - Tools to improve the use of geostatistic
- [georob](https://cran.r-project.org/web/packages/georob/index.html) - Robust geostatistical analysis of spatial data - *datasets included*
- [gear](https://cran.r-project.org/web/packages/gear/index.html) - Geostatistical analysis in R - *datasets included*
- [gstat](https://cran.r-project.org/web/packages/gstat/index.html) - Spatial and spatio-temporal geostatistical modeling, prediction, and simulation - *datasets included*
- [geostats](https://cran.r-project.org/web/packages/geostats/index.html) - An introduction to statistics for geoscientists - *datasets included*

### Hydrology
- [GWSDAT](https://cran.r-project.org/web/packages/GWSDAT/index.html) - Groundwater spatiotemporal data analysis tool - **includes RShiny data exploration tool!**
- [streamDepletr](https://cran.r-project.org/web/packages/streamDepletr/index.html) - Estimate streamflow depletion due to groundwater pumping - *datasets included*
- [GlacierSMBM](https://cran.r-project.org/web/packages/glacierSMBM/index.html) - Glacier surface mass balance model - *datasets included*

### Oil and Gas
- [Rmbal](https://cran.r-project.org/web/packages/Rmbal/index.html) - Estimate original hydrocarbon in place and reservoir performance
- [Rpvt](https://cran.r-project.org/web/packages/Rpvt/index.html) - Estimate the PVT properties of reservoir fluids
- [zFactor](https://github.com/f0nzie/zFactor) - **GitHub Repo** - Computational tools for chemical, petrochemical and petroleum engineers

### Paleontology
- [tidypaleo](https://cran.r-project.org/web/packages/tidypaleo/index.html) - Provides a set of functions with a common framework for age-depth model management, stratigraphic visualization, and common statistical transformations. See Dunnington et al. (2021) doi:10.18637/jss.v101.i07.
- [velociraptr](https://cran.r-project.org/web/packages/velociraptr/index.html) - Functions for downloading, cleaning, and analyzing fossil data from the Paleobiology Database
- [paleobioDB](https://cran.r-project.org/web/packages/paleobioDB/index.html) - Download and process data from the paleobiology batabase
- [fossil](https://cran.r-project.org/web/packages/fossil/index.html) - Palaeoecological and palaeogeographical analysis tools - *datasets included*
- [FossilSim](https://cran.r-project.org/web/packages/FossilSim/index.html) - Simulating taxonomy and fossil data on phylogenetic trees under mechanistic models of speciation, preservation and sampling
- [strap](https://cran.r-project.org/web/packages/strap/index.html) - Stratigraphic tree analysis for paleontology - *datasets included*
- [folio](https://cran.r-project.org/web/packages/folio/index.html) - Datasets for teaching archaeology and paleontology - *datasets included*
- [chronosphere](https://cran.r-project.org/web/packages/chronosphere/index.html) - A package to facilitate spatially explicit analyses of (paleo)environmental/ecological research - *datasets included*
- [vegan](https://cran.r-project.org/web/packages/vegan/index.html) - Ordination methods, diversity analysis and other functions for community and vegetation ecologists.

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
- [EMMAgeo](https://cran.r-project.org/web/packages/EMMAgeo/index.html) - End-member modeling of grain-size data
- [DecomposeR](https://cran.r-project.org/web/packages/DecomposeR/index.html) - Empirical model decomposition for cyclostratigraphy
- [stRat stat](https://github.com/ActiveMargins/stRatstat) - **GitHub Repo** - My R-based digitizer for turning hand-drawn graphic logs into a digital/numeric format

### Structural Geology
- [RockFab](https://cran.r-project.org/web/packages/RockFab/index.html) - Rock fabric and strain analysis tools

## Non-CRAN resources
 - Steven Holland, of the University of Georgia, has a "Data Analysis in the Geosciences" course that incorporates R scripts for [sandstone provenance](http://strata.uga.edu/8370/rtips/provenance.html), [ternary plots](http://strata.uga.edu/8370/rtips/ternaryPlots.html),  and [rose diagrams](http://strata.uga.edu/8370/rtips/roseDiagrams.html). 
- [GRAN - Geological Survey R Archive Network](https://owi.usgs.gov/R/gran.html) - GRAN is a repository of curated R packages developed by USGS employees for USGS and external use



## For those learning R
For those who do not know R but may have found a package that interests them, I suggest you check out the [“swirl” package](https://cran.r-project.org/web/packages/swirl/index.html) that allows you to learn R in the R console! swirl was built by a student at Johns Hopkins University and houses a lot of different coursers ranging from introduction to R, data cleaning, visualization in R, and all the way to inferential statistics and regression models. I’ve used swirl in Coursera’s/John Hopkins Biostatistics’ “Data Science in R” course series – it’s fantastic.

If you're looking to pick up some basic R then blast right into more complex topics like geostatistics, there is the [“geostats” package](https://cran.r-project.org/web/packages/geostats/index.html) by Pieter Vermeesch. This package is the companion code and datasets for a course run at University College London. The CRAN repository has a link to a short .pdf textbook for the course, which includes a short introduction to R. The .pdf textbook also has exercises for each chapter that use datasets built into the package.

Lastly, if you're looking to increase your data analysis skills and R at the same time, Steve Holland's course [Data Analysis in the Geosciences](http://strata.uga.edu/8370/index.html) has lots of online material.  

## For those looking for datasets to play with
### Geoscience-related datasets
As I said up top, having a variety of datasets to play around with is fantastic. I wanted to highlight the packages that include datasets within them. These datasets are great to practice skills visualization and modeling skills, as many of them have been cleaned, but most of all, they are more interesting than mtcars…

[provenance](https://cran.r-project.org/web/packages/provenance/index.html) – provenance includes a large  dataset composed of detrital zircon ages, compositional bulk petrography data, heavy mineral composition, and major and trace element data.

[folio](https://cran.r-project.org/web/packages/folio/index.html) – Datasets for teaching quantitative approaches and modeling in archaeology and paleontology. Geological datasets include ice core data, δ18O data foram and sea level data. The archaeological datasets, however, are very interesting radiocarbon dating examples and trace element data from ancient ceramics.

[geostats](https://cran.r-project.org/web/packages/geostats/index.html) – geostats includes 23 different datasets that are all used in examples/exercise throughout the .pdf textbook. Some highlights are:
- AFM - 630 calc-alkali basalts from the Cascade Mountains and 474 tholeiitic basalts from Iceland
- declustered - 28267 earthquakes between 1769 and 2016, with aftershocks and precursor events removed
- DZ – Detrital zircon U-Pb data of 13 sand samples from China.
- forams – Planktic foraminifera counts in surface sediments in the Atlantic Ocean
fractures – A 512 × 512 pixel image of a fracture network.

[strap](https://cran.r-project.org/web/packages/strap/index.html) – A package for building, analyzing, and visualizing phylogenic trees of taxa. It includes family trees of lungfish (dipnoans), trilobites (Asaphidae), and a structured version of regional stages for the Ordovician in Britain. 

[ggtern](https://cran.r-project.org/web/packages/ggtern/index.html) - A package that extends ggplot2 to create ternary plots. This package includes:
 - Feldspar - feldspar composition data
 - Fragments - sand composition data related to morphometric information of drainages in the Coweeta Basin, North Carolina
 - SkyeLava - AFM compositions of 23 aphyric Skye lavas

### Non-geoscience related
For non-geoscience-related datasets there three main packages that contain classic datasets. An advantage of using these is that are you can easily find multiple solutions to a single dataset and see how people approached and dissected these problems. The main packages composed of datasets are: 
- [datasets](https://cran.r-project.org/web/packages/datasets.load/index.html) – A package of datasets including cars, ChickWeight, and AirPassengers.
- [MASS](https://cran.r-project.org/web/packages/MASS/index.html) – A package functions and datasets to support the textbook “Modern Applied Statistics with S” (Venables and Ripley, 2002).
- [mlbench](https://cran.r-project.org/web/packages/mlbench/index.html) – A packages that includes benchmark datasets for machine learning. It includes classic datasets like BostonHousing, Ionosphere, and BreastCancer.

Last updated: 03/05/2022
