---
title: "Deep Learning — An Introduction"
topic: true
subjects: ['Python']
subjects_weight: 50
draft: false
intro: |
  Deep Learning is a vast and convoluted topic. It’s hard to know where to start. This workshop will help you take your first steps.

  We'll introduce you to the fundamental concepts behind Deep Learning and show you how to get started building models using Python and Keras. You'll learn some of the underlying maths (in a very non-threatening way: a PhD in Mathematics will not be required!) and work through a number of practical examples.

  You’ll walk away with an appreciation for what’s possible with Deep Learning and sufficient hands-on experience to start building your own models.

  All material will be available as Jupyter Notebooks.
duration: 2 days
who: This workshop is aimed at people with little or no prior experience with Deep Learning. If you're already a Deep Learning ninja, then this is not for you!
# objectives: 
# outcomes:
requirements: Familiarity with programming in Python. A basic understanding of Machine Learning concepts will be helpful but certainly not essential.
setup: |
  You'll need the following to get the most out of the workshop:

  - a laptop and
  - an account on [Google Colab](https://colab.research.google.com/) and
  - an account on [Kaggle](https://www.kaggle.com/).

  If you have not used Jupyter Notebooks before, then read through the following resources:

  - [What is a Jupyter Notebook?](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/What%20is%20the%20Jupyter%20Notebook.ipynb)
  - [Notebook Basics](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb)
  - [Running Code](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Running%20Code.ipynb) and
  - [Markdown Cells](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Working%20With%20Markdown%20Cells.ipynb).

  Take a look at these resources for some useful background information:

  - [Gradient](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/gradient-and-directional-derivatives/v/gradient)
  - [Gradient and graphs](https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/gradient-and-directional-derivatives/v/gradient-and-graphs) and
  - [How does backpropagation work?](https://brohrer.github.io/how_backpropagation_works.html)
---

<!--
	https://medium.com/intro-to-artificial-intelligence/deep-learning-series-1-intro-to-deep-learning-abb1780ee20
	https://medium.com/intro-to-artificial-intelligence/simple-image-classification-using-deep-learning-deep-learning-series-2-5e5b89e97926
	https://medium.com/intro-to-artificial-intelligence/traffic-sign-detection-selefdriving-car-deep-learning-series-3-1db4eda67979
	https://realpython.com/python-keras-text-classification/
	https://towardsdatascience.com/an-introduction-to-deep-learning-af63448c122c
	https://skymind.ai/wiki/lstm
	https://adventuresinmachinelearning.com/keras-lstm-tutorial/
	https://skymind.ai/wiki/generative-adversarial-network-gan
	https://medium.com/@jonathan_hui/gan-some-cool-applications-of-gans-4c9ecca35900
	https://towardsdatascience.com/image-generator-drawing-cartoons-with-generative-adversarial-networks-45e814ca9b6b
-->

- Deep Learning Showcase
- Working with Google Colab
	- Jupyter Notebooks
	- Kernels & Hardware
- Machine Learning: An Overview
	- Terminology
	- Building a Model
	- Feature Engineering
	- Lab — Feature Engineering on Synthetic Data
- Introduction to Neural Networks
	- Biological intuition
	- Neuron Model: Weights and bias
	- Activation functions
	- Loss functions
	- Chain rule and back-propagation
	- Optimisers
	- Batch & mini-batch training
	- Where neural networks fail: images
	- Lab — Binary Classifier on Synthetic Data
- TensorFlow
	- What is TensorFlow?
	- What is a tensor?
	- Types of tensor: constant and variable
	- Tensor operations
		- Arithmetic
		- Gradients
	- Optimisation
		- Implementing Linear Regression
	- Lab — Implementing Logistic Regression
- Keras
	- What is Keras?
	- Optimisers
	- Loss Functions
	- Layers
		- `Dense`
		- `Dropout`
	- Models
		- Sequential and Functional API
		- Building, Compiling and Fitting
	- Callbacks
	- Accessing layers
	- Saving & loading models
	- Lab — Binary Classifier on Synthetic Data
	- Lab — Banknote Authentication
	- Lab — Breast Cancer (CNN)
- Convolutional Neural Network 
	- Understanding Convolution
		- Stride and padding
	- More layers
		- `Conv2D`
		- `MaxPooling2D` and `AveragePooling2D`
		- `Flatten`
	- Data Augmentation
	- Lab — MNIST Fashion
	- Lab — Americal Sign Language
	- Lab — Santa versus Grinch
	- Lab — Chest X-rays
- Transfer Learning
	- What is Transfer Learning?
	- Pre-trained networks
	- Transfer Learning
	- Fine-Tuning
	- Lab — Impala versus Springbok
	- Lab — Monkey Species
	- Lab — Tutti Frutti
- Recurrent Neural Network (RNN)
	- Recursion, internal state and memory
	- Back-propagation through time
	- Long Short-Term Memory (LSTM)
	- Lab — Time Series prediction
	- Lab — Text prediction
	- Lab — Music generation
