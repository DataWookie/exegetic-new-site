---
title: "Spatial Analysis"
topic: true
subjects: ['R']
subjects_weight: 120
draft: true
intro: INTRO TEXT 
duration: 2 days
who: R users interested in analysing spatial data.
objectives: WHAT DO WE AIM TO TEACH?
outcomes: WHAT SHOULD THEY BE ABLE TO DO AFTERWARDS?
requirements: Participants should have a solid understanding and experience in R. They should be comfortable using the pipe `%>%` operator and with manipulating data using `dplyr` verbs. They should have some experience with basic plotting using `ggplot`.
---

- Spatial Concepts
- Packages for spatial data
- Spatial Data
	- Raster data
	- Vector data
	- KML
- Coordinate Reference Systems
	- PROJ4
- Working with Raster Data
	- `raster`
	- Changing projection
	- Multi-band
	- Calculations
- Working with Vector Data
	- Shapefiles
	- GeoJSON
	- `sf`
	- Geometry types
	- Manipulating spatial data using `dplyr`
- Data Translation
	- `rgdal`
- Cartography
	- Types of maps
	- Choropleths
  		- ggplot
  		- plotly
  	- OpenStreetMap
- Visualisation
	- Static maps with `ggplot` and `tmap`
	- Animated maps with `gganimate`
	- ineractive maps with `leaflet` (and embedding in `shiny`)
- Geocoding
- Routing with Open Source Routing Machine (OSRM)
- Other useful packages:
  - `countrycode` - for dealing with country names and codes
- Showcase of applications
  - Transportation
  - Geomarketing
  - Ecology
