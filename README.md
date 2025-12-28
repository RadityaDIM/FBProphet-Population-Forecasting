# Implementation of Facebook Prophet for Indonesian Population Prediction
This repository contains the implementation of the Facebook Prophet algorithm for forecasting Indonesia's annual population. Using historical data from 1961 to 2024, this project demonstrates how machine learning can provide an efficient alternative to decennial censuses for continuous demographic monitoring.

## Overview
Monitoring population growth is critical as it directly impacts energy demand, economic stability, and sustainable development. This study optimizes the FB Prophet model to capture long-term trends and seasonality in Indonesia’s demographic data, achieving **high predictive accuracy** compared to traditional models like ARIMA and SVR.

## Key Features
- Time Series Forecasting: Utilizes FB Prophet's additive decomposition to handle trends and seasonal variations.
- Hyperparameter Tuning: Optimization of Changepoint Prior Scale (CPS), Seasonality Prior Scale (SPS), and N-changepoints.
- Comparative Analysis: Performance benchmarking against ARIMA and Support Vector Regression (SVR).
- Highly Accurate Results: Achieved a Mean Absolute Percentage Error (MAPE) of 2.65%.
