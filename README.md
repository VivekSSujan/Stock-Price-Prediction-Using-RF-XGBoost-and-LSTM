# Stock-Price-Prediction-Using-Ensemble Models
Using Random Forest and XGBoost with smoothed exponential moving average features (SESClose) to predict stock price direction.

# Stock Price Prediction using Random Forest and SES Close Features

This project explores stock price prediction using a Random Forest model, XGBoost Classifier model and  enhanced with SES (Smoothed Exponential Smoothing) features. It focuses on building robust features and applying machine learning techniques to predict whether the price will go up or down the next day.

## 🔍 Project Overview

The goal is to predict stock price direction using:

- Lag features of stock prices
- Smoothed Exponential Smoothing (`SESClose`) as engineered features
- Random Forest classification model
- XGBoost Classifier
- Accuracy and performance metrics for evaluation

## 📊 Techniques & Tools

- **Random Forest and XGBoost Classifier** from `sklearn`
- **SES Feature Engineering** using `statsmodels`
- **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** for data processing and visualization
- **Train-test split** with evaluation on classification accuracy

## 📁 Files

- `RF_with_SESClose.ipynb`: Main notebook containing code, visualizations, and analysis
