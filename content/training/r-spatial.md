---
title: "Spatial Analysis"
topic: true
subjects: ['R']
subjects_weight: 120
draft: true
intro: INTRODUCTION  TEXT
duration: 2 days
who: R users interested in analysing spatial data.
objectives: In this course, you'll learn how to read, explore, analyse, manipulate and enhance spatial data in R, create insightful maps and understand some interesting, relevant applications.
outcomes: |
  After this course, you will

  - have an understanding of the R spatial ecosystem;
  - be able to import, wrangle and perform analyses with various types of spatial data;
  - understand coordinate reference systems and how to transform spatial data between projections;
  - create static and dynamic, interactive maps;
  - be able to geocode addresses into locations; and 
  - be able to spin up and use OSRM for spatial optimization and routing problems in R.

requirements: Participants should have a solid understanding and experience in R. They should be comfortable using the pipe `%>%` operator and with manipulating data using `dplyr` verbs. They should have some experience with basic plotting using `ggplot`.
---

- Spatial Concepts
- Packages for spatial data
- Spatial Data Types
	- Raster data
	- Vector data
- Spatial Data Formats
	- Shapefile
	- GeoJSON
	- GeoTIFF
	- KML
- Coordinate Reference Systems
	- PROJ4
- Working with Raster Data
	- `{raster}`
	- `{ceramic}` for satellite imagery
	- Changing projection
	- Multi-band
	- Calculations
- Working with Vector Data
	- `{sf}`
	- Geometry types
	- Manipulating spatial data using `dplyr`
- Data Translation
	- `{rgdal}`
- Cartography
	- Types of maps
	- Static maps with `{ggplot2}` and `{tmap}`
	- Animated maps with `{gganimate}`
	- Interactive maps with `{plotly}` and `{leaflet}` (and embedding in Shiny)
	- Choropleths
  	- OpenStreetMap
- Geocoding
- Routing with Open Source Routing Machine (OSRM)
- Other useful packages:
  	- `{countrycode}` - for dealing with country names and codes
- Showcase of applications
  	- Transportation
  	- Geomarketing
  	- Ecology
