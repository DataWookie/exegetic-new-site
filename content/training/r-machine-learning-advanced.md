---
title: "Machine Learning (Advanced)"
topic: true
subjects: ['R']
draft: true
subjects_weight: 41
duration: 3 days
who: |
  The course is aimed at students, academics and professionals who already use Machine Learning techniques but want to build more powerful models.
objectives: |
  In this course you'll dig deeper into the following topics:

    - Generalised Linear Models (GLMs) and how they relate to Logistic and Poisson regression
    - Regularisation
    - Neural Networks and
    - XGBoost. 
outcomes: |
  Participants will understand a selection of advanced modelling techniques and be able to build powerful Machine Learning models.
requirements: |
  Participants should have completed the [Machine Learning]({{< ref "r-machine-learning.md" >}}) module.
---

### Day 1: Linear Methods

- Generalised Linear Models
	- Link Functions
	- Logistic Regression (revisited)
	- Poisson regression
- Regularisation
	* Lasso and Ridge Regression
	* {glmnet}
- Generalized Additive Models
- Mixed Effects Models

### Day 2: Neural Networks & Boosting

- Neural Networks
	* The brain as a network
	* Single Layer Perceptron
	* Feedforward Neural Network
		- Weights
		- Bias
		- Activation Functions
	* Back-propagation
	* {neuralnet}
		- Data preparation (scaling and shuffling)
		- Training
		- Visualising
		- Predictions
	* {caret}
		- Cross-validation
		- Parameter selection
- XGBoost
	* Boosted Trees
	* eXtreme Gradient Boosting
	* {xgboost}
		- Data preparation
		- Training
		- Predictions
		- Feature importance
		- Persisting models
		- Dealing with imbalanced data
	* {caret}
		- Parameter selection
- Let's Kaggle!