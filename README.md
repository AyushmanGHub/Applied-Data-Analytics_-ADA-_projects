# Applied DataAnalytics(ADA) Projects
This repository contains projects completed during my ADA course:


## Project 01. **Time Series Analysis and Forecasting for Network Link Utilization**
This project applies time series forecasting techniques to predict future **network link utilization** using hourly data. The workflow includes data cleaning, preprocessing, resampling to hourly frequency, feature engineering, and exploratory analysis. Three forecasting approaches are implemented: **Linear Regression** with lag features, **ARIMA**, and **Exponential Smoothing**. Each model generates a seven-day forecast, with performance evaluated using R², MSE, RMSE, MAE, and MAPE. The study compares model strengths and limitations, highlights trends and seasonality, and provides computational insights for reliable forecasting of network utilization.

## Project 02. **TrafficNet - ML Approach to Network Traffic Classification**
This TrafficNet Project applies machine learning approach for network traffic classification using flow-based features from the Unicauca dataset (2.7M+ rows, 50 features). The pipeline includes data exploration, feature selection, model training, and evaluation. Four algorithms—Random Forest, XGBoost, KNN, and LDA—were tested. Random Forest achieved the best performance (98% accuracy), followed by XGBoost (90%), while KNN and LDA underperformed. Results show that ensemble methods handle complex, non-linear relationships effectively, outperforming simple linear or distance-based models.

## Project 03. **NetGuard - ML for Network Intrusion Detection**
This project used machine learning (Random Forest, XGBoost, KNN) to detect network intrusions on the `netflow.csv` dataset (216M+ rows). After critical data balancing via oversampling, models were tested on both binary (Benign vs. Attack) and multi-class (attack type) tasks. All models excelled at binary classification (99%+ accuracy), with Random Forest leading (99.6%). Random Forest also performed best on the multi-class task (90.9% accuracy), followed by KNN (90.4%), proving it the most robust solution overall.


---
## 🤝 Let’s Connect!

I’m always open to meaningful conversations, collaborative projects, and idea exchanges.  
If you’re interested in exploring new insights, working together on related topics, or contributing to ongoing discussions — feel free to reach out!  

**Let’s learn and build together 🚀**
