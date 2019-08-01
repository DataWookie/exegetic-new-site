---
title: "Introduction to the Tidyverse"
topic: true
subjects: ['R']
subjects_weight: 20
draft: false
intro: |
  The Tidyverse is a collection of integrated packages for performing Data Science by applying "tidy" data principles. The packages are all based on a common design philoshophy and implement consistent grammar and data structures. They form a broad basis for a wide range of analyses in R.

  This course is an excellent entry point to working with data in R.
duration: 1 day
who: This course is suitable for anybody who uses a spreadsheet to work with data. No prior programming knowledge required.
objectives: Learn to use the Tidyverse for basic data analysis and visualisation.
outcomes: |
  Participants will be comfortable using packages from the Tidyverse to work with with data. Specifically they will be able to:

  - import data from CSV and spreadsheets;
  - perform an array of data cleaning and manipulation operations; and
  - create attractive visualisations.
setup: A laptop with recent versions of R and RStudio.
---

- Introduction
- `{tibble}` --- An alternative to the `data.frame`
- `{magrittr}` --- Pipes!
- `{readr}` and `{readxl}` --- Reading Data
	- CSV (and other delimited) files
	- Spreadsheets
- `{dplyr}` --- Wrangling Data
	- Working with columns: `select()`, `rename()` and `mutate()`
	- Working with rows: `filter()` and `arrange()`
	- Aggregation
- `{ggplot2}` --- Plotting Data
	- Components of a visualisation (geoms)
	- Mapping data to components (aesthetics)
	- Faceting
	- Themes
- `{tidyr}` --- Pivoting Data
	- What is "tidy data"?
	- Pivoting data with `gather()` and `spread()`
	- Splitting and combining data with `separate()` and `unite()`
- `{stringr}` and `{glue}` --- Working with Strings
	- Splitting and combining strings
	- Extracting substrings
	- Pattern matching (and a short introduction to Regular Expressions)
	- Dealing with whitespace
	- String interpolation
- `{lubridate}` --- Working with Dates and Times
	- `{anytime}` --- Handling dates and times in a *wide* variety of formats!
- `{forcats}` --- Working with Categorical Data
	- Renaming levels
	- Changing order of levels
	- Dropping empty levels
	- Lumping levels
- `{purrr}` --- Functional Programming Tools
	- Introduction to Functional Programming
	- Applying a function to elements of a vector (or list) with `map()`
	- Using `map2()` and `pmap()` for multivariate functions
	- Generating side-effects with `walk()`
	- Dealing with errors `insistently()` and using delays