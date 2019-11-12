---
title: "Working with Data"
topic: true
subjects: ['Python', 'Data Science']
subjects_weight: 10
draft: true
duration: 1 day
who: |
  The course is aimed at students, academics and professionals who conduct data analysis using other tools like Excel. It's assumed that participants already have some familiarity with Python.
objectives: |
  Python is a effective tool for working with data. Being able to lay out the steps in an analysis as a script means that the analysis is repeatable and can also be version controlled.  One of the first steps in any analysis is the preparation of the data. The package Pandas has a wide range of functionality to aid in the data preparation process.
outcomes: |
  Participants will be able to utilize a core set of functions from Pandas to process data.
---

### NumPy
- Array fundamentals
	- Array creation with `np.array()`, `np.arange()` & `np.random()`
	- Special arrays `np.eye()`, `np.diag()` & `np.zeros()`
	- Data types
	- Indexing and shapes
- Manipulation
	- Reshaping with `np.reshape()` & `np.resize()` 
  - Concatenation with `np.hstack()` & `np.vstack()`
- Common matrix operations
  - Dot product with `np.dot()`

### Pandas

<!--
What is Data Science?
Grabbing data from various sources
Working with Series and DataFrame objects
Dealing with funky data (missing data and outliers)
Overview of Machine Learning
Keeping it simple using Nearest Neighbours
Capturing a trend: LinearRegression
Predicting categories: DecisionTreeClassifier
Binary outcomes: LogisticRegression
Using Pipeline to streamline your workflow
Cross Validation

Unit 1: Introduction to Python

Python is a high-level programming language. You will learn the basic syntax and data structures in Python. We demonstrate and run codes within Ipython notebook, which is a great tool providing a robust and productive environment for interactive and exploratory computing.
Introduction to Ipython notebook
Basic objects in Python
Variables and self-defining functions
Control flow
Data structures
Unit 2: Explore Deeper with Python

Python is an object-oriented programming (OOP) language. Having some basic knowledge of OOP will help you understand how Python codes work. More often than not, you will have to deal with data that is dirty and unstructured. You will learn many ways to clean your data such as applying regular expressions.
Introduction to object-oriented programming
How to deal with files
Run Python scripts
Handling and processing strings
Unit 3: Scientific Computation Tools

There are two modules for scientific computation that make Python powerful for data analysis: Numpy and Scipy. Numpy is the fundamental package for scientific computing in Python. SciPy is an expanding collection of packages addressing scientific computing.
Numpy
Scipy
Unit 4: Data Visualization

Python can also generate graphics easily using “Matplotlib” and “Seaborn”. Matplotlib is the most popular Python library for producing plots and other 2D data visualizations. Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing statistical graphics.
Seaborn
Matplotlib
Unit 5: Data manipulation with Pandas

Pandas provides rich data structures and functions for working with structured data. The “DataFrame” object in Pandas is just like the “data.frame” object in R. Pandas makes data manipulation (filter, select, group, aggregate, etc.) as easy as in R.
Pandas
Final Project

After 20 hours of structured lectures, students are encouraged to work on an exploratory data analysis project based on their own interests. A project presentation demo will be arranged afterwards.

-->

- Loading data from files
	- CSV, XLSX and JSON using base and [pandas.read_csv](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html)
- Manipulating Data Frames 
	- Selecting columns with `df[], df.loc() & df.iloc()`
	- Filtering rows with `df.query()`
	- Sorting with `df.sort_values()`
	- Adding and changing columns with `df.assign()` and `df.column`
	- Aggregation with `df.groupby()`,`df.describe()` & `df.aggregate()`
- Pivoting 
	- Long versus wide data formats
	- Going wide with `df.melt()`
	- Getting long with `pandas.wide_to_long()`
	- Splitting compound columns using string methods `df.column.str.split()`
	- Explicit missing values with `df.fillna()` & `df.replace()`
- Functional programming
	- Mapping functions of a single variable with `df.apply()`
	- Mapping to a specific data type with `df.astype` 
	- Mapping functions of many variables with annonymous functions, `lambda`, and `df.apply()`
	- Handling errors and exceptions with `try` & `except`
