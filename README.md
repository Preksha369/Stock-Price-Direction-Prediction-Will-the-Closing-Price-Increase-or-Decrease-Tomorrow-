# Stock Price Direction Prediction  
*Will the Closing Price Increase or Decrease Tomorrow?*

## Overview

This project focuses on predicting the **direction of stock price movement** — whether the *closing price* of HCL Technologies (HCLTECH.NS) will increase or decrease on the next trading day.  

Historical stock market data was collected using the `yfinance` API and used to build both traditional machine learning models and advanced deep learning models for binary classification.

## Objectives

- Predict whether the stock's closing price will go up or down tomorrow.
- Perform exploratory data analysis on stock market data.
- Engineer time-based and technical features.
- Build and compare:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier
  - LSTM (Long Short-Term Memory) network
  - GRU (Gated Recurrent Unit) network
- Visualize model performance using:
  - Accuracy scores
  - Confusion matrices
  - ROC curves
  - Precision-Recall curves

## Key Steps

- Data Collection via `yfinance`
- Data Cleaning & Preprocessing
- Feature Engineering (date-related and price-related features)
- Model Building & Evaluation
- Comparative Analysis of all models

## Results

The project demonstrated that predicting stock price direction is a challenging task, and while the models achieved varying levels of performance, perfect accuracy is not expected in such a noisy and unpredictable domain.  

Nevertheless, this project successfully built a framework for testing different classification models on stock data and provided insights into the behavior and limitations of each modeling approach.

## Tools & Libraries

- Python
- yfinance
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost
- tensorflow / keras
- statsmodels

## Disclaimer

This project is for educational and research purposes only and is not intended for real-world trading or financial advice.
