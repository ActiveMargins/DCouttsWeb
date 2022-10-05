---
title: Building digital capacity in geoscience education
author: Danny
date: '2022-10-05'
slug: []
categories:
  - Blog
tags:
  - Geology
  - Education
  - Digital Geoscience
subtitle: How do we better prepare geoscience students for modern geology?
description: Modern geoscience is rapdily eovlving, but some of our main tools are still analog. After some discussion with friends in the post-secondary education space I've jotted some notes down on a pathway forward for digital geoscience education.
image: 'img/2021_1_21-BehindstRatstat/header_valdes_small.jpg'
---

There's a lot of buzz in the geoscience community around data science and machine learning applications. However, these topics are not the starting point in journey that those who use these tools took. Additionally, not all geoscientists need to know how to tune machine learning models, interpret regression coefficients, or understand the basis of natural language processing. This is actually an incredibly small subset. What the vast majority geoscientists need to do is manipulate, summarize, interpret, and display data (often with a spatial component), which many geoscientists still struggle with.

## Core competency of modern geoscientists
Geoscientists interact with all sorts of data to understand earth system processes: analog data (e.g. paper maps or core logs), unstructured data (a folder of associated .csv or .shp files), and structured data (e.g., drilling databases). Because of this, digital geoscientists need all manor of skills to wrangle data in to datasets they can then derive insights from. I would say there are three main core competencies that are required of modern geoscientists working in a digital framework. 

1. Fundamental data types
   - fundamental data structures
   - spatial vs non spatial
   - vector vs raster
   - projections
   - implicit vs. explicit modelling

2. Data wrangling
   - data combinations and links - non/spatial joins, parent-child relationships
   - summarized - non/spatial summaries to calculate descriptive statistics
   - transformed - long-to-narrow transformations, interpolation, points-to-raster and vice versa.

3. Data visualization
   - numeric, categorical, tabular, time series, etc.
   - cartographic skills

In my experience, these topics were covered in a disparate collection of classes that I had to seek out, some in university and other through MOOCs. Skills beyond these core competencies (e.g., statistical methods, machine learning) are used by a small subset of geoscientists. Exposure to them is great, as it may spark the interest of some students, but everyone needs to be able to make a map and summarize data.


## Progression

The main hurdle I've noted from friends and colleagues in learning digital skills is the abstract working space of programming workspaces. If that's the case, then a fundamental education in data transformation in Excel or a geographic information system (GIS) is much more approachable. Introduction to problem solving can then be done with a GIS modeler where geoprocessing tools are strung together from inputs to create a desired output, or an Excel macro where steps can be physically mapped out. A key point here is that not everyone needs to progress onwards from this point. If students finish their undergraduate education with a high level of Excel or GIS fluency, that would be incredible. However, I do believe that exposure to programming is desirable in the modern workforce, but not required by any stretch.  Below are some key scaffolding steps for each step along the way.


1. Excel - there is a reason Excel rules the world, it is easy to use and very powerful.
   - formulas - things like v-lookup introduce indexing
   - data conversions - reading .csv, long to narrow transformations
   - visualization
   - extend to macros (recorded or in VBA) to automate tasks
2. GIS 
   - spatial data - raster vs. vector and projections. Vector files are just like Excel, but with build in geometry.
   - data types - spatial file formats are composed of attributes that are numeric, integer, boolean, 
   - joins, column calculations, spatial summaries, model building - These are largely extensions of Excel formulas but run with simple commands.
   - introduction to digitalisation through map rectification and digitization.
3. Basic Programming language - repeat the same as above. Geoscience specific programming packages.
4. Introduction to Machine learning and descriptive and inferential statistics - there are a million ways to skin this cat.


## Why is a GIS the best entry point?
I firmly believe that my early introduction to GIS during my undergrad made learning programming and later data science fundamentals very easy. Before doing any programming, I had already done spatial joins, summaries, and lots of data visualization. These are the core of modern data science approaches and should be the focus of each step of the progression. Along with learning about data structures and doing some basic scripting through visual models and macros. Along with the introduction of concepts, a GIS interface is much more tactile than a programming development space, which for largely analog geologists, is more approachable. From the GIS that friendly graphical user interface can slowly be stripped away and students can move into a more abstract space where all the loaded data is "still there" but not visually represented until you ask for it to be.

## Conclusion/TL:DR
Geologist, on the whole, are a very analog type of scientists (geophysicists not so much). As such, we should recognize that and not let it be a limitation when it comes to embracing digital workflows and the capabilities of the modern computing landscape.  There are many options to build digital capacity in geoscience education, where students can progress from tactile graphical user interfaces, to more abstract programming languages, and then apply those skills to model or predict earth system phenomena.  Not every student needs to be able to design neural networks, but every student should be able to wrangle .csv's, make a map, and summarize a digital dataset.