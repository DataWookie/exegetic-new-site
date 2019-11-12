---
title: "Machine Learning"
topic: true
subjects: ['Python', 'Data Science']
subjects_weight: 20
draft: true
duration: X days
who: |
  The course is aimed at students, academics and professionals who want to use Machine Learning to build models and make predictions, utilizing the Python and the scikit-learn package.
objectives: |
  Machine Learning is a big, convoluted topic. In this course you'll learn how to apply Machine Learning to two types of problems: Classification and Regression. Although Machine Learning models are often treated as black boxes, you'll learn (in an unthreatening, low-math way) how these models work. You'll also learn how to appropriately prepare your data, how to build and test a model, and how to generate predictions.
outcomes: |
  Participants will be able to build Classification and Regression models on real world data. They will understand how the models work and how to interpret model predictions.
requirements: |
  Participants are assumed to have prior exposure to Python, or at least to programming of some variety. Ideally participants should have completed the [Data Wrangling](https://www.exegetic.biz/training/python-working-with-data/) and [Visualisation](https://www.exegetic.biz/training/python-visualisation/) modules.
---

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

Unit 1: Introduction and Regression

What is Machine Learning
Simple Linear Regression
Multiple Linear Regression
Numpy/Scikit-Learn Lab
Unit 2: Classification I

Logistic Regression
Discriminant Analysis
Naive Bayes
Supervised Learning Lab
Unit 3: Resampling and Model Selection

Cross-Validation
Bootstrap
Feature Selection
Model Selection and Regularization lab
Unit 4: Classification II

Support Vector Machines
Decision Trees
Bagging and Random Forests
Decision Tree and SVM Lab
Unit 5: Unsupervised Learning

Principal Component Analysis
Kmeans and Hierarchical Clustering
PCA and Clustering Lab
-->

### Day 1: Classification

- Introduction
	- What is Machine Learning?
	- Regression and Classification
		- Concepts of Accuracy
		- Residuals
		- Best fit and least squares
	- Model Optimisation (Underfitting and Overfitting)
- Classification
	- k-Nearest Neighbours (kNN)
		- How it works
		- Finding a good value for k
		- Importance of normalising data
	- Naive Bayes
		- Background on Bayesian Methods
		- Probabilistic model
		- Flavours of Naive Bayes
		- Laplace smoothing
		- Document/Spam Classifier
	- Model Evaluation
		* Confusion Matrix
		* Accuracy
		* Recall / Sensitivity
		* Precision
		* Specificity
		* Positive/Negative Predictive Value
		* F Measure
		* ROC and AUC
	- Costs of Errors
	- Data Preparation
		- Transformations (`log()`, `sqrt()` and Box-Cox)
		- Missing Data
		- Unbalanced Data
			* Oversampling
			* Undersampling
			* Synthetic Data Generation
		- [`{recipes}`](https://github.com/tidymodels/recipes)
	- Decision Trees
		- Recursive Partitioning algorithm
		- Pruning
		- Model parameters (preventing underfitting and overfitting)
		- A variation: Conditional Inference Trees
	- Support Vector Machine
		- Maximum Margin Classifiers
		- Support Vector Classifiers
		- The Kernel Trick
		- Non-Linear Boundaries
			* Polynomial Kernel
			* Radial Kernel

### Day 2: Linear Models & Dimension Reduction

- Linear Models
	- Motivating Example
	- k-Nearest Neighbours
	- Linear Regression
		* Assumptions 
		* Multiple regression
		* Model evaluation (RMSE, [MAE](https://en.wikipedia.org/wiki/Mean_absolute_error) and [MPE](https://en.wikipedia.org/wiki/Mean_percentage_error))
		* Categorical variables
			* One-Hot Encoding (low-cardinality variables)
			* Target Encoding (high-cardinality variables)
		* Formulae
			* Simple Formulae
			* Interactions
		* Example: Prostate Cancer with Interactions
		* Polynomial regression
	- Validating Model Assumptions
		* Fit Diagnostics
	- Logistic Regression
		* Odds, Log Odds and the Logit Function
		* Example: Synthetic Data
		* Thresholding and classification
		* Principle of Parsimony
		* Multicollinearity
		* Example: Myopia Data
		* Beyond binary: One-versus-rest models
	- Feature Importance
	- Feature Selection
	  	* Stepwise (forward selection and backward elimination)
- Dimension Reduction
	- PCA
	- Linear Discriminant Analysis

### Day 3: Scikit-learn, Validation & Ensembles

- Validation
	- Why Validation?
	- k-Fold Cross-Validation
	- Repeated Cross-Validation
	- Leave-One-Out Cross-Validation
	- Bootstrap
	- Model Tuning / Parameter Selection
- Using [`scikit-learn`](https://scikit-learn.org/stable/index.html)
	* Pre-processing
		- Dealing with missing data
		- Handling unbalanced data
	* Train/test splitting
	* Feature importance and feature selection
	* Model evaluation (using cross validation and bootstrapping)
	* Model tuning
- Ensembles
	- The Idea: "Wisdom of the Crowd"
	- Homogeneous and Heterogeneous Ensembles
	- Bagging
		* Random Forests
- Machine Learning at Scale
	- Building many models (automation)

<!--
### Day 4: H2O
-->
