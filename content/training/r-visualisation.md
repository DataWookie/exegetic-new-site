---
title: "Visualisation with ggplot2"
topic: true
subjects: ['R']
draft: false
subjects_weight: 32
---

The [ggplot2](https://github.com/tidyverse/ggplot2) package has become the *de facto* standard for making plots in R. It's possible to quickly put together a simple plot for exploratory purposes. However, with a bit of effort such a plot can be transformed into a work of art.

This hands-on workshop will introduce the basic components of ggplot2 and show how they can be combined to form sophisticated visualisations. We'll then take a look at extensions for labelling points in congested scatterplots and producing animations.




<!-- https://plotly-book.cpsievert.me/ -->

[Plotly](https://github.com/ropensci/plotly) is an open source JavaScript library for creating interactive graphs and dashboards.

In this course you'll learn how to easily create sophisticated interactive visualisations from within R using Plotly.

**Need to separate out the two descriptions above, which were originally for separate ggplot and plotly courses.**

## Course Description

### Day 1: ggplot

- Introduction
	- Grammar of Graphics
- Components of a plot
	- Data
	- Aesthetics
	- Layers
	- Facets
	- Themes
- Aesthetics
- Layers
	- Points
	- Lines
	- Box and Violin plots
	- Histogram, Density and Bar plots
	- Smooth
	- Stats versus Geoms
	- Position
- Facets
- Scales, Legends and Coordinates
- Themes
	- Builtin themes
	- Other themes
	- Customising

### Day 2: ggplot Extensions & Plotly

- Extensions
	- Labelling points with [ggrepel](https://github.com/slowkow/ggrepel)
	- Animation with [gganimate](https://github.com/thomasp85/gganimate)

PLOTLY

- Fundamentals
	- ggplot to plotly with `ggplotly()`
- Plot types
	- Scatter and Line plots
	- Box plots
	- Histogram and Bar plots
	- Heat maps and Contour plots
	- Polar plots
- Maps
- Combining plots
	- Sub-plots
	- Inset plots
	- Multiple axes
- Custom controls
- Dashboards
- Animation
- Exporting static images
