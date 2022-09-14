---
title: "SpatialMeta (Online MALDI data analysis server)"
date: 2022-09-05T10:40:25+08:00
categories:
- category
- subcategory
tags:
- SpatialMeta
- Brain Atlas
- shiny app
- Multi-omics
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /img/
thumbnailImagePosition: left
#thumbnailImage: //example.com/image.jpg
---

> A online interactive website for analyzing MALDI and spatial metabolomics/proteomics data.

<!--more-->

---
# Introduction
MALDI MSI, also known as matrix-assisted laser desorption/ionization mass spectrometry imaging, is a
an instrument to evaluate the spatial distribution of analytes (proteins, peptides, medicines, lipids, and metabolites) in thin tissue sections.


# Step 1
- **Data format convertion**\
We have tested datas from the Bruker MALDI-TOF system. Data from Bruker MALDI-TOF system can be easily exported as .imzML and .ibd format. Our SpatialMeta accept these two input formats for downstream analysis pipeline.

You may need [imzMLConverter](https://github.com/AlanRace/imzMLConverter),
in order to get ready, you need to do as following:
- Download the latest version of imzMLConverter
- Install Java SE 8 JRE
- Install ProteoWizard
- [Optional] Install [MS Data Converter (SCIEX)](https://sciex.com/form-pages/sw-downloads-form?d=ab_sciex_ms_data_converter_V1.3%20beta.zip&asset=software&softwareProduct=MS%20Data%20Converter%20(Beta%20Version%201.3)) to enable conversion of data from AB SCIEX data instruments




# Step 2
- **Data upload**



# Step 3
- **Start your analysis**




---
### Vendor instruments
1. [AP/MALDI (ng) UHR](https://www.apmaldi.com/main/products/apmaldi-ng-uhr/), MassTech
    - The AP-MALDI(ng) UHR is available for all mass spectrometers currently supported by the regular AP-MALDI. The AP-MALDI(ng) UHR includes upgraded optics, source housing and eliminates the use of optical fiber which allow for a focused laser spot less than 10 micron in diameter.
    - AP-MALDI(ng) UHR includes an upgraded laser – it is still a solid state Nd:YAG laser at 355 nm wavelength, but the output frequency is up to 10 kHz.
    
![apmaldiuhr](/img/Snipaste_2022-09-10_15-26-39.png)

---
2. [rapifleX®](https://www.bruker.com/en/products-and-solutions/mass-spectrometry/maldi-tof/rapiflex.html), MALDI-TOF/TOF system, Bruker
    - **Speed**, Make the best decisions in the shortest amount of time with the 10 kHz scanning smartbeam 3D laser, for throughput up to 20 times faster than traditional MALDI-TOF systems.
    - **Robustness**, Most robust, yet easy to access ion source enables straightforward cleaning, designed for maximum uptime in 24/7 operations.
    
    
    
    
    