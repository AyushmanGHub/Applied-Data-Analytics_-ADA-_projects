## Project 01. **Time Series Analysis and Forecasting for Network Link Utilization**

### Introduction
This project analyzes hourly network utilization data to identify trends, seasonality, and patterns, and to forecast future link usage. Multiple forecasting models are applied and compared to determine the most accurate and reliable approach.

## Problem Statement
The project addresses key forecasting questions:  
- Which regression model best captures and predicts utilization for the next seven days?  
- What ARIMA model is appropriate, and how well does it perform?  
- Which exponential smoothing method suits the data, and how do its forecasts compare?  
- How accurate and reliable are the forecasts across models?  

### Solution and Approach
The solution is implemented follows these steps:  
1. **Data Preprocessing**: Clean dataset, convert timestamps, resample hourly, and create `total_KB`.  
2. **Exploratory Data Analysis (EDA)**: Visualize utilization trends and feature relationships.  
3. **Regression Model**: Apply linear regression with lag-based feature engineering.  
4. **ARIMA Model**: Identify suitable ARIMA parameters using stationarity tests and ACF/PACF.  
5. **Exponential Smoothing**: Fit Holt-Winters exponential smoothing for forecasting.  
6. **Comparative Analysis**: Compare models using R², MSE, RMSE, MAE, and MAPE.  

### Technologies Used
- Python, pandas, numpy, matplotlib, seaborn
- scikit-learn 
- statsmodels  
 
