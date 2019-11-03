---
title: "Forecasting & Time Series Analysis"
topic: true
subjects: ['R']
subjects_weight: 43
draft: false
intro: |
  A Time Series model allows you to make predictions about the future based on observations from the past. These models have important applications in science, industry and commerce.

  > *Prediction is very difficult, especially if it's about the future.*<br>&mdash; Niels Bohr, Nobel Laureate (Physics)

  Niels Bohr was right: predicting the future is a tough problem. Some things, like lottery numbers, are inherently unpredictable. Others, like air temperatures and rainfall, are reasonably predictable. Time series analysis makes it possible to assess whether or not predictions are possible and, if they are, build a model which can generate informed predictions for the future with realistic estimates of uncertainty.

  > *The best qualification of a prophet is to have a good memory.*<br>&mdash; George Savile

  This course will provide you with an understanding of the theory behind time series models and the ability to build such models in R. By the end of the course you'll be able to select the appropriate model for your data, train a model and start making predictions.
duration: 2 days
why: |
  1. Understand tools and methods of forecasting.
  2. Select appropriate forecasting techniques.
  3. Predict trends and estimate uncertainty.
  4. Use forecasting to improve decision-making and strategic planning.
  5. Evaluate and iteratively improve forecast accuracy.
who: |
  Anybody interested in predicting the future will benefit from this course.

  - Analysts and strategic planners.
  - Managers (sales, marketing, product, business, financial, HR, inventory and supply chain).
  - Researchers.
objectives: |

outcomes: |

requirements: |
  We assume that participants have prior experience with R, ideally having completed both the the [Introduction to R](https://www.exegetic.biz/training/r-introduction/) and [Data Wrangling](https://www.exegetic.biz/training/r-data-wrangling/) courses.
---

### Day 1

- Introduction
    * What is a Time Series?
    * Examples
- Time Series Objects
    * Base Representation
        - Creating a `ts` object
        - Visualisation: plots and seasonal plots
        - Data quality, outliers and missing data
    * Other Representations
        - `xts`
        - `zoo`
- Correlation
    - Covariance and correlation
    - Cross-Correlation
        * Correlation and causality
        * Significance
    - Autocorrelation (ACF)
    - Partial autocorrelation (PACF)
- Basic Models
    * White Noise
    * Random Walk
    * Stationarity
- Decomposition
    * Moving averages and smoothing
    * Additive and Multiplicative Decomposition
    * Trend
    * Seasonality
    * STL Decomposition
    * Decomposition and Forecasting
- Model Principles
    * Accuracy and Precision
    * Training and Testing
    * Accuracy metrics
    * Rare Events and Black Swans
- Exponential Smoothing
    - Simulation
    - Model estimation and forecasting
    - Adding trend and seasonality: Holt and Holt-Winters methods
- Autoregressive (AR) Models
    - Simulation
    - PACF and autoregression
    - Model estimation and forecasting
- Moving Average (MA) Models
    - Simulation
    - ACF and moving average
    - Model estimation and forecasting

### Day 2
- ARIMA Models
    - Simulation
    - Integrating for non-stationarity
    - Model estimation and forecasting
    - Automating with `auto.arima()`
- Exogenous Variables
    * Examples
    * Adding Exogenous Variables to a model
    * ARMAX and ARIMAX models
    * Predicting with Exogenous Variables
- Prophet
    - Non-linear and changing trends
    - Multiple seasonalities
    - Non-uniform sampling and missing data
- Hierarchical Models
    - Bottom-up approach
    - Top-down approach
    - Middle-out approach
- Anomaly Detection
