# CO2 Forecasting

This repository contains Python code for forecasting CO2 levels using various time series forecasting techniques such as MA, ARMA and MLP (Multi-Layer Perceptron). The dataset used for forecasting is `co2_mm_mlo.csv`, which contains monthly average CO2 levels from 1958 to 2024, to forecast the CO2 value from 2024 to 2029.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Models Used](#models-used)
- [Methodology and Results](#methodology-and-results)
- [Conclusion](#conclusion)

## Introduction

The goal of this project is to forecast future CO2 levels based on historical data. The provided Python code preprocesses the data, applies different time series forecasting models, and compares their performance.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, statsmodels, scikit-learn, seaborn, tensorflow

## Usage

1. Clone the repository to your local machine.
2. Ensure that you have the required Python libraries installed.
3. Run the Python script `CO2_forecasting.py` in your preferred Python environment.
4. The script will load the dataset, preprocess it, apply different forecasting models, and plot the results.

## Models Used

1. SARIMAX (Seasonal Autoregressive Integrated Moving Average with Exogenous Factors)
2. MLP (Multi-Layer Perceptron)

## Methodology and Results

The model initially converts the non-stationary and seasonal time series data to stationary data and apply MA, ARMA and MLP to forecast future results. Now, the stationary data is converted to non-stationary and seasonal data using inverse function. The code generates plots showing the actual CO2 levels alongside the forecasted values from each model. 

## Conclusion

Based on the results, we can determine which forecasting model provides the most accurate predictions for CO2 levels. This information can be valuable for understanding and predicting trends in atmospheric CO2 concentration.

Feel free to explore the code, modify it according to your requirements, and contribute to the project!

