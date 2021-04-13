---
authors:
- admin
categories:

date: "2020-12-13T00:00:00Z"
draft: false
featured: false
image:
  focal_point: ""
  placement: 2
  preview_only: false
lastmod: "2021-04-13T00:00:00Z"
projects: []
subtitle: 
summary: 
tags:

title: "R script for extracting geographic occurrences and climate data"
---
## Overview
[This github repository](https://github.com/tmoreperez/PGaCER) contains two scripts will extract the geographic occurrence data from the [BIEN](https://bien.nceas.ucsb.edu/bien/) database or the [GBIF](https://www.gbif.org/) database. After obtaing occurrence data, each script will then retrieve climate data for each occurrence, remove potentially erroneous occurrence data, and calculate the mean of selected climatic distributions for species with more than 15 occurrences. At a minimum, users will have to provide a the names of plant species of interest and a file-path to to climatic data. In the past I've used [WorldClim](https://www.worldclim.org/) data so the code is currently written to retrive Worldclim data from a local file where it is stored. Other climate databases of interest to users may include [Chelsa](https://chelsa-climate.org/) and [CRU](https://crudata.uea.ac.uk/cru/data/hrg/).

