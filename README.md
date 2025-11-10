# EDS-223: [Homework 3](https://eds-223-geospatial.github.io/assignments/HW3.html)

### 2021 Texas Blackout and Income Disparity

This repository contains the analyses and visual outputs from four data sources to evaluate the impacts of the February 2021 Texas snowstorm on Houston residents. NASA Worldview satellite data was used to estimate areas that experienced blackouts due to the snowstorm in Houston. OpenStreetMap (OSM) data was used to exclude highway lights from blackout information and estimate the number of houses impacted by blackouts. U.S. Census data was used to identify potential socioeconomic disparities between groups impacted by the storm.

## Data Access

Data was publicly available and accessed from the U.S. Census Bureau's American Community Survey from 2019. OSM is an open access source of geographic data. OSM data was subsetted from GeoFabrik, a third party distibutor of geographic data. NASA night lights data is distributed from the Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC).

## Author: Nathalie Bonnet

Instructor: Annie Adams

Teaching Assistant: Ale Vidal Meza

## Folders and Files

-   .gitignore

Contains instructions for hiding specific files. This project's data file is contained under .gitignore

-   eds-223-texas-blackouts.Rproj

setup instructions for R project

-   texas-blackout.qmd:

Contains all processing and data analysis code to produce pdf output with maps and figure

-   ejscreen.html: 

Rendered output page from texas-blackout.qmd

-   README.md: 

README document

## Contents
Data: Contains folders with U.S. census data, OSM, and NASA night lights

eds-223-homework-2.html:

Rendered output

eds-223-homework-2.qmd: 

data processing, analysis, and visualization code

README.md: contains project overview information

```
│   .gitignore
│   .Rhistory
│   eds-223-texas-blackouts.Rproj
│   README.md
│   texas_blackout.html
│   texas_blackout.qmd
|
├───data
│   ├───ACS_2019_5YR_TRACT_48_TEXAS.gdb
│   ├───gis_osm_buildings_a_free_1.gpkg
│   ├───gis_osm_roads_free_1.gpkg
│   └───VNP46A1
└───texas_blackout_files
    ├───figure-html
    └───libs
        ├───bootstrap
        ├───clipboard
        └───quarto-html
            ├───axe
            └───tabsets
```

## References

| Data | Citation | Sources |
|---------------------------|------------------|---------------------------|
| OpenStreetMap | OpenStreetMap Contributors. (2025). OpenStreetMap database. https://planet.openstreetmap.org/| <https://planet.openstreetmap.org/> |
| Geofabrik distribution | OpenStreetMap Data Extracts. Geofabrik Download Server. https://download.geofabrik.de/ | <https://download.geofabrik.de/> |
| U.S. Census Data | U.S. Census Bureau. (2020). TIGER/Line Shapefiles and American Community Survey 2019 (5-Year-Estimates), Texas-Census Tract Level (ACS_2019_5YR_TRACT_48_TEXAS). U.S. Department of Commerce. https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-data.html | <https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-data.html> |
| NASA VNP46 | Earth Science Data Systems, N. (2024, July 23). Level-1 and Atmosphere Archive and Distribution System Distributed Active Archive Center. https://www.earthdata.nasa.gov/centers/laads-daac | <https://ladsweb.modaps.eosdis.nasa.gov/> |
