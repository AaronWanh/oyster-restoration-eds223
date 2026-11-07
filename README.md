# Homework Assignment 3

In this assignment, we explore the significance of marine aquaculture, specifically oysters, and how global seafood demands could be met using less than 0.015% of ocean area. Exclusive Economic Zones (EEZ) are areas in the ocean that permit coastal nations to have rights over a specific maritime zone for natural resources, exploration, and conservation. Our goal is to determine which EEZ areas of the west coast of the US are suitable for optimal oyster growth utilizing sea surface temperature and bathymetry as indicators for suitability. We will analyze which areas in the west coast have both a sea surface temperature between 11-30°C and a depth between 0-70 meters below sea level showcasing appropriate conditions for oyster growth. 

## Inside the Repo:

This repository contains a data folder that holds raster data of average annual sea surface temperature from 2008 to 2012 and bathymetry of the west coast of U.S. The data folder also contains a shape file of the EEZ that separates the west coast into 5 different zones. However we have a gitignore file to prevent the large dataset from bloating the repository. The main code and graphs are within the quarto document hw3.qmd. Finally the README.md file is a summary of what is contained inside the repository and what it accomplishes. 

```text
C:.
|   .gitignore
|   hw3.qmd
|   README.md
|   
\---data
        average_annual_sst_2008.tif
        average_annual_sst_2009.tif
        average_annual_sst_2010.tif
        average_annual_sst_2011.tif
        average_annual_sst_2012.tif
        depth.tif
        wc_regions_clean.shp
        wc_regions_clean.shx
```

## Authors/Collaborators:
- Aaron Wang
- Annie Adams https://github.com/annieradams 


## Citations:
* NOAA Coral Reef Watch. (2018, updated daily). NOAA Coral Reef Watch Version 3.1 Daily Global 5km Satellite Sea Surface Temperature Anomaly Product. College Park, Maryland, USA: NOAA Coral Reef Watch. Accessed November 7, 2026, at https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php
* GEBCO Bathymetric Compilation Group 2026. (2026). The GEBCO_2026 Grid – a continuous terrain model for oceans and land at 15 arc-second intervals. https://doi.org/10.5285/4f68d5c7-45eb-f999-e063-7086abc036fa
* Flanders Marine Institute. (2023). Maritime Boundaries Geodatabase: Maritime Boundaries and Exclusive Economic Zones (200NM), version 12. https://doi.org/10.14284/632
