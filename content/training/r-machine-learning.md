---
title: "Machine Learning"
topic: true
subjects: ['R']
draft: false
subjects_weight: 41
---

## Details

**Duration** 3 days

**Who should attend?** The course is aimed at students, academics and professionals who want to use Machine Learning to build models and make predictions.

**Objectives**

Machine Learning is a big (and rather hot!) topic. In this course you'll learn how to apply Machine Learning to two types of problems: Classification and Regression. Although Machine Learning models are often treated as black boxes, you'll learn (in an unthreatening, low-math way) how these models work. You'll also learn how to appropriately prepare your data, how to build and test a model, and how to generate predictions.

**Outcomes**

Participantes will be able to build Classification and Regression models on real world data. They will understand how the models work and how to interpret model predictions.

**Requirements**

Participants are assumed to have prior exposure to R, or at least to programming of some variety. Ideally participants should have completed the [Data Wrangling]({{< ref "r-data-wrangling.md" >}}) and [Visualisation]({{< ref "r-visualisation.md" >}}) modules.

## Contents

### Day 1: Classifiction

- Introduction
	- Model Optimisation
		- Underfitting and Overfitting
	- Data Preparation
		- Transformations
			- `log()` and `sqrt()`
			- Box-Cox
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
	- Unbalanced Data
		* Oversampling
		* Undersampling
		* Synthetic Data Generation

### Day 2: Linear Models

- Linear Models
	- Motivating Example
	- k-Nearest Neighbours
	- Background
		- Residuals
		- Best fit and least squares
	- Linear Regression
		* Assumptions 
		* Multiple regression
		* Model evaluation (RMSE, [MAE](https://en.wikipedia.org/wiki/Mean_absolute_error) and [MPE](https://en.wikipedia.org/wiki/Mean_percentage_error))
		* Categorical and dummy variables
		* Formulae
			* Simple Formulae
			* Interactions
		* Example: Prostate Cancer Data
		* Example: Prostate Cancer Data with Interactions
		* Polynomial regression
		* LOESS
	- Validating Model Assumptions
		* Fit Diagnostics
	- Using [`{broom}`](https://github.com/tidyverse/broom)
	- Logistic Regression
		* Odds, Log Odds and the Logit Function
		* Example: Synthetic Data
		* Principle of Parsimony
		* Multicollinearity
		* Example: Myopia Data
	- Generalised Linear Models
		- Logistic Regression
			* Odds, Log Odds and the Logit Function
			* Example: Synthetic Data
			- Thresholding and classification
			* Principle of Parsimony
			* Multicollinearity
			* Example: Myopia Data
			- Beyond binary: One-versus-rest models
			- Model evaluation
		- Poisson regression
	- Feature Importance
	- Feature Selection
	  	* Stepwise (forward selection and backward elimination)
	- Regularisation
		* Lasso and Ridge Regression
	- Generalized Additive Models
	- Mixed Effects Models
	- Using [`{caret}`](http://topepo.github.io/caret/index.html)
		* pre-processing;
		* train/test splitting;
		* feature importance and feature selection;
		* model evaluation (using cross validation and bootstrapping);
		* model tuning.

### Day 3: Validation & Ensembles

- Validation
	- Why Validation?
	- k-Fold Cross-Validation
	- Repeated Cross-Validation
	- Leave-One-Out Cross-Validation
	- Bootstrap
	- Model Tuning / Parameter Selection
- Ensembles
	- The Idea: "Wisdom of the Crowd"
	- Homogeneous and Heterogeneous Ensembles
	- Bagging
		* Random Forests
	- Boosting
		* Gradient Boosting Machine
		* XGBoost
	- Heterogeneous Ensembles

## Prior Knowledge

We assume that participants have prior experience with R, ideally having completed both the the [Introduction to R]({{< ref "r-introduction.md" >}}) and [Data Wrangling]({{< ref "r-data-wrangling.md" >}}) courses.