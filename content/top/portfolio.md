---
title: "Portfolio"
author: "Danny Coutts"
date: 2021-01-18T19:30:00-05:00
image: 'img/20200930_181240.jpg'
---

## Danny Coutts

I'm drawn to disentangling intricate geologic and geospatial relationships through the integration of numerous datasets and techniques. This has led me to use outcrop and subsurface geology, laboratory techniques, and modern data science workflows to analyze the rock record and provide insights into pointed industry-related problems. 

This portfolio consists of a range of projects that describes that demonstrate my abilities in the following fields:
- Sedimentary geology
- Geospatial analysis, remote sensing, and cartography
- R, RMarkdown, RShiny
- Data science (cleaning through modeling)

-----

##### stRat stat 
[GitHub Repo](https://github.com/ActiveMargins/stRatstat) || [shinyapps.io version](https://activemargins.shinyapps.io/stRat_stat/) || [CSPG 2020 Talk](https://www.youtube.com/watch?v=4cbkrBNZ2o4&ab_channel=CptCatastrophe) 

Graphic logs (i.e., drawn core logs or measured sections) are one of the most commonly used tools to illustrate geologic heterogenity of sedimentary deposits. Although they are very common, they are rarely leveraged for more than visual analysis and description. This project set out to develop an open-source GUI-based software that allows users to digitize then summarize these data for use in exploratory data analysis or modeling.


![alt="stRat stat workflow" ](/img/portfolio/stRatstat_workflow.png)

-----

##### ASTER sensor workflow
[GitHub Repo](https://github.com/ActiveMargins/ASTERSatelliteProcessing)

The ASTER sensor on the TERRA satellite is one of the premiere multispectral sensor for mapping geologic bodies. This project focused on creating an object-oriented stack of functions that processed ASTER data from 1LB to top of atmosphere reflectance. Additional functions mask vegetation and snow, create mineral indices, and produce principle component analysis RGB false colour composites.

-----

##### Upper Nanaimo Group chronostratigraphy
[Google Scholar](https://scholar.google.com/citations?user=RogRDGAAAAAJ&hl=en) || [PhD thesis](https://prism.ucalgary.ca/handle/1880/112547)

Deep-water sediment routing systems are more poorly understood compared to other sedimentary systems (e.g., fluvial or aeolian), as they difficult to monitor in the modern and are controlled by a number of upstream and downstream processes. My PhD work focused on deducing the allogenic controls on deep-water channel systems preserved in the upper Nanaimo Group, British Columbia, Canada. This was done by integrating field stratigraphy (field mapping, stratigraphic sections) with U-Pb detrital zircon techniques to constrain the timing of deep-water channel system sedimentation and compare it to the tectonic evolution of the near-by Coast Mountains. 

-----
 
##### Various RShiny dashboards and tools

These two projects were single day challenges I gave myself to test my ability to go from a schematic (list of functions+variables and a sketch of a UI) to a working prototype. Admittedly I have spent more than just those single days on each app polshing them at this point.  

**Geologic data visualizer** || [shinyapps.io version](https://activemargins.shinyapps.io/till_data_exploration/)

Geologic data can have spatial, temporal, numeric, and categorical properties. Lastly, it is almost always very messy. This project saw the design of a simple dashboard that can be used to visualize geologic data from multiple datasets that have a spatial component. The dashboard includes dataset selection, spatial visualization with dynamic user-controlled symbology (seen below), and dynamic x-y plotting.

![alt="Model GUI and example model of multiple channelbelts" ](/img/portfolio/TillGeochemistryMap.JPG)

**Simple stratigraphic forward model of fluvial deposits** || [GitHub Repo](https://github.com/ActiveMargins/FluvialStratSim) || [shinyapps.io version](https://activemargins.shinyapps.io/FluvialStratApp/) 

The ability to visualize sedimentary processes and how various parameters coalesce to build stratigraphy is a skill that takes a long time to develop but is fundamental to understanding, mapping, and predicting the nature of sedimentary sequences. An easy way to help individuals understand this field is through the use of numerical models that given a set of inputs stochastically produce a model of stratigraphy. In this project I designed a simple stratigraphic forward model of fluvial deposits that runs on a RShiny GUI. 

![alt="Model GUI and example model of multiple channelbelts" ](/img/portfolio/ForwardStratigraphicModel.JPG)
