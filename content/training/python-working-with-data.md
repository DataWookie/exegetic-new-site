---
title: "Working with Data"
topic: true
subjects: ['Python']
subjects_weight: 10
draft: false
duration: 1 day
who: |
  The course is aimed at students, academics and professionals who conduct data analysis using other tools like Excel. It's assumed that participants already have some familiarity with Python.
objectives: |
  Python is a effective tool for working with data. Being able to lay out the steps in an analysis as a script means that the analysis is repeatable and can also be version controlled. One of the first steps in any analysis is the preparation of the data. The Numpy and Pandas packages have a wide range of functionality to aid in the data preparation process.
outcomes: |
  Participants will be able to utilize a core set of functions from Numpy and Pandas to process data.
---

This course covers two major packages:

- Numpy &mdash; data in arrays and
- Pandas &mdash; data in tables.

Almost all Data Analysis or Machine Learning projects will use either one or both of these packages for data manipulation.

### NumPy

- Array fundamentals
	- Array creation <!-- `array()`, `arange()` & `random()` -->
	- Special arrays <!-- `eye()`, `diag()` & `zeros()` -->
	- Data types
	- Dimension and shape
	- Indexing (slicing and dicing)
- Manipulation
	- Reshaping <!-- `reshape()` & `resize()`  -->
	- Concatenation <!-- `hstack()` & `vstack()` -->

<!--
Exercises:

- Working with images (see https://www.datacamp.com/courses/biomedical-image-analysis-in-python)
-->

### Pandas

- Series and DataFrame objects
- Creating DataFrames
	- From dictionaries and lists
	- From a file (CSV, XLSX and JSON)
- Manipulating Data Frames
	- Column types
	- Column names
	- Selecting columns
	- Index
		- Hierarchical index
	- Filtering rows
	- Sorting
	- Inserting and manipulating columns
	- Aggregation
- Plotting
- Time Series data <!-- https://www.datacamp.com/courses/pandas-foundations -->
- Data Layout
	- Splitting compound columns
	- Dealing with missing data
- Pivoting, Stacking and Joining
	- Long versus wide data formats
	- Types of joins
- Functional programming
	- Mapping functions <!-- `apply()` -->
