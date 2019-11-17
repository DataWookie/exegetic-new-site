---
title: "Visualisation"
topic: true
subjects: ['R']
draft: false
subjects_weight: 32
intro: |
  This course will cover two *libraries* for creating visualisations with R:
  
    - ggplot2 — static and dynamic visualisations
    - plotly — interactive visualisations.
duration: 2 days
who: The course is aimed at students, academics and professionals who need to visualise data. It's assumed that participants already have some familiarity with R.
objectives: Being able to communicate the results of an analysis is as important as doing the analysis itself. In this course you'll learn how to use two R packages (ggplot2 and plotly) to create effective, visually pleasing and reproducible visualisations.
outcomes: Participants will be able to create static and animated visualisations with ggplot2 and interactive visualisations using plotly. They will also be able to customise the presentation characteristics of these visualisations.
requirements: |
  Participants are assumed to have prior experience with R, ideally having completed both the the [Introduction to R](https://www.exegetic.biz/training/r-introduction/) and [Data Wrangling](https://www.exegetic.biz/training/r-data-wrangling/) courses.
---

### Day 1: ggplot2

The [ggplot2](https://github.com/tidyverse/ggplot2) package has become the *de facto* standard for making plots in R. It's possible to quickly put together a simple plot for exploratory purposes. However, with a bit of effort such a plot can be transformed into a work of art.

This course will introduce the basic components of ggplot2 and show how they can be combined to form sophisticated visualisations. We'll then take a look at extensions for labelling points in congested scatterplots and producing animations.

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
- Extensions
	- Labelling points with [ggrepel](https://github.com/slowkow/ggrepel)
	- Animation with [gganimate](https://github.com/thomasp85/gganimate)

### Day 2: plotly

<!-- https://plotly-book.cpsievert.me/ -->

[Plotly](https://github.com/ropensci/plotly) is an open source JavaScript library for creating interactive graphs and dashboards. In this course you'll learn how to easily create sophisticated interactive visualisations from within R using Plotly.

- Fundamentals
	- ggplot to plotly with `ggplotly()`
	- Online and offline plotting
- Plot types
	- Scatter and Line plots
	- Box plots
	- Histogram and Bar plots
	- Heat maps and Contour plots
	- Polar plots
- Interactivity
	- Hover information (tooltips)
	- Custom controls (buttons, selectors and sliders)
- Style
	- Markers
	- Colour scales
	- Fonts
	- Legends
	- Axes
- Maps
- Combining plots
	- Sub-plots
	- Inset plots
	- Multiple axes
- Dashboards
- Animation
- Exporting static images
