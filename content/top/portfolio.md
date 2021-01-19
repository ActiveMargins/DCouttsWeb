---
title: "Portfolio"
author: "Danny Coutts"
date: 2021-01-18T19:30:00-05:00
---

### Portfolio

This portfolio consists of a range of projects that describes that demonstrate the range of level of my abilities in the following fields:
- Sedimentary geology
- Geospatial analysis, remote sensing, and cartography
- R, RMarkdown, RShiny
- Data science (cleaning through modeling)

-----

##### stRat stat 
[shinyapps.io version](https://activemargins.shinyapps.io/stRat_stat/) | [GitHub Repo](https://github.com/ActiveMargins/stRatstat) |[CSPG 2020 Talk](https://www.youtube.com/watch?v=4cbkrBNZ2o4&ab_channel=CptCatastrophe) 

Graphic logs (i.e., drawn core logs or measured sections) are one of the most commonly used tools to illustrate geologic heterogenity of sedimentary deposits. Although they are very common, they are rarely leveraged for more than visual analysis and description. This project set out to develop an open-source GUI-based software that allows users to digitize then summarize these data for use in exploratory data analysis or modeling.
This project required:
 - Domain expertise - sedimentary geology and the requirements/desires of subsurface geological datasets.
 - Knowledge of tidy data framework - used to created powerful export files. 
 - Advanced R knowledge, RShiny - advanced work with manipulable plots and user-generated user interfaces.

-----

##### ASTER sensor workflow
The ASTER sensor on the TERRA satellite is one of the premiere multispectral sensor for mapping geologic bodies. This project focused on creating an object-oriented stack of functions that processed ASTER data from 1LB to top of atmosphere reflectance. Additional functions mask vegetation and snow, create mineral indices, and produce principle component analysis RGB false colour composites.This project required:
 - Advanced R knowledge - function scoping and functions with few dependencies
 - Ability to learn quickly - re-learning previous course-content from my undergrad and running with it!

-----

##### Upper Nanaimo Group Chronostratigraphy
Deep-water sediment routing systems are more poorly understood compared to other sedimentary systems (e.g., fluvial or aeolian), as they difficult to monitor in the modern and are controlled by a number of upstream and downstream processes. My PhD work focused on deducing the allogenic controls on deep-water channel systems preserved in the upper Nanaimo Group, British Columbia, Canada. This was done by integrating field stratigraphy (field mapping, stratigraphic sections) with U-Pb detrital zircon techniques to constrain the timing of deep-water channel system sedimentation and compare it to the tectonic evolution of the near-by Coast Mountains. 
This project required:
 - Domain expertise - deep-water systems, sedimentary basins, and tectonics.
 - VBA and R - used to create numerical models and visualize field data. 
 - Geospatial methods - databases for field data and integrate additional datasets (e.g., lidar).
 - Technical writing - presentation skills producing peer-reviewed academic journal articles, industry talks, and academic talks.

-----
 
##### Various RShiny Dashboards and tools
**Geologic data visualizer** | [shinyapps.io version](https://activemargins.shinyapps.io/till_data_exploration/)

Geologic data can be spatial, temporal, numeric, and categorical. Lastly, it is almost always very messy. This project saw the design of a simple dashboard that can be used to visualize geologic data from multiple datasets that have a spatial component. The dashboard includes dataset selection, spatial visualization with dynamic user-controlled symbology, and dynamic x-y plotting.

**Simple stratigraphic forward model of fluvial deposits** | [shinyapps.io version](https://activemargins.shinyapps.io/FluvialStratApp/) | [GitHub Repo](https://github.com/ActiveMargins/FluvialStratSim)

The ability to visualize sedimentary processes and how various parameters coalesce to build stratigraphy is a skill that takes a long time to develop but is fundamental to understanding, mapping, and predicting the nature of sedimentary sequences. An easy way to help individuals understand this field is through the use of numerical models that given a set of inputs stochastically produce a model of stratigraphy. In this project I designed a simple stratigraphic forward model of fluvial deposits that runs on a RShiny GUI. 

These two projects required:
 - Advanced R and RShiny knowledge
 - Quick learning and ability to "figure it out"
 - Agile mentality and ability to pivot design