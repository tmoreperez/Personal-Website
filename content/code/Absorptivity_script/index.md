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

title: "R script for calculating mean leaf absorptance, transmittance, and reflectance"
---
## Overview
Absorptance, transmittance, and reflectance are traits that influence leaf temperature. Included here is a [brief R script](https://github.com/tmoreperez/Absorptivity_script) for calculating mean leaf absorptance, transmittance, and reflectance for a CID Bio-Science Miniature Leaf Spectrometer CI-710. This script uses the output from a CID Bio-Science Miniature Leaf Spectrometer CI-710. Some sample data is provided. Due to the CID software, output files from the spectrometer have to be named a certain way. The naming structure is such that a species' unique ID is followed by a period (.), which is followed by the number of the leaf replicate, and then another period (.), and finally the type of measurement (reflectance or transmittance).

This script estimates mean absorptance, transmittance, and reflectance values across wavelengths 400nm-1000nm, but code could easily be altered to target specific wavelengths of interest.
