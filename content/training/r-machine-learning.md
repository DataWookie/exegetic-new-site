---
title: "Machine Learning"
topic: true
subjects: ['R']
draft: false
subjects_weight: 40
duration: 3 days
who: |
  The course is aimed at students, academics and professionals who want to use Machine Learning to build models and make predictions.
objectives: |
  Machine Learning is a big (and rather hot!) topic. In this course you'll learn how to apply Machine Learning to two types of problems: Classification and Regression. Although Machine Learning models are often treated as black boxes, you'll learn (in an unthreatening, low-math way) how these models work. You'll also learn how to appropriately prepare your data, how to build and test a model, and how to generate predictions.
outcomes: |
  Participants will be able to build Classification and Regression models on real world data. They will understand how the models work and how to interpret model predictions.
requirements: |
  Participants are assumed to have prior exposure to R, or at least to programming of some variety. Ideally participants should have completed the [Data Wrangling]({{< ref "r-data-wrangling.md" >}}) and [Visualisation]({{< ref "r-visualisation.md" >}}) modules.
---

<!--
Unit 1: Foundations of Statistics and Simple Linear Regression

Understand your data
Statistical inference
Introduction to machine learning
Simple linear regression
Diagnostics and transformations
The coefficient of determination
Unit 2: Multiple Linear Regression and Generalized Linear Model

Multiple linear regression
Assumptions and diagnostics
Extending model flexibility
Generalized linear models
Logistic regression
Maximum likelihood estimation
Model interpretation
Assessing model fit
Unit 3: kNN and Naive Bayes, the Curse of Dimensionality

The K-Nearest Neighbors Algorithm
The choice of K and distance measure
Conditional probability: Bayes’ Theorem
The Naive Bayes’ Algorithm
The Laplace estimator
Dimension reduction
The PCA procedure
Ridge and Lasso regression
Cross-validation
Unit 4: Tree Models and SVMs

Decision trees
Bagging
Random forests
Boosting
Variable Importance
Hyperplanes and maximal margin classifier
Sort margin and support vector classifier
Kernels and support vector machines
Unit 5: Cluster Analysis and Neural Networks

Cluster analysis
K-means clustering
Hierarchical clustering
Neural networks and perceptrons
Sigmoid neurons
Network topology and hidden features
Back propagation learning with gradient descent
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
		- Document Classifier
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
		* LOESS
	- Validating Model Assumptions
		* Fit Diagnostics
	- Using [`{broom}`](https://github.com/tidyverse/broom)
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

### Day 3: Caret, Validation & Ensembles

- Validation
	- Why Validation?
	- k-Fold Cross-Validation
	- Repeated Cross-Validation
	- Leave-One-Out Cross-Validation
	- Bootstrap
	- Model Tuning / Parameter Selection
- Using [`{caret}`](http://topepo.github.io/caret/index.html)
	* Pre-processing
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
