# Applied DataAnalytics(ADA) Projects
This repository contains projects completed during my ADA course:


## Project 01. **Time Series Analysis and Forecasting for Network Link Utilization**
This project applies time series forecasting techniques to predict future **network link utilization** using hourly data. The workflow includes data cleaning, preprocessing, resampling to hourly frequency, feature engineering, and exploratory analysis. Three forecasting approaches are implemented: **Linear Regression** with lag features, **ARIMA**, and **Exponential Smoothing**. Each model generates a seven-day forecast, with performance evaluated using R², MSE, RMSE, MAE, and MAPE. The study compares model strengths and limitations, highlights trends and seasonality, and provides computational insights for reliable forecasting of network utilization.

## Project 02. **TrafficNet - ML Approach to Network Traffic Classification**
This TrafficNet Project applies machine learning approach for network traffic classification using flow-based features from the Unicauca dataset (2.7M+ rows, 50 features). The pipeline includes data exploration, feature selection, model training, and evaluation. Four algorithms—Random Forest, XGBoost, KNN, and LDA—were tested. Random Forest achieved the best performance (98% accuracy), followed by XGBoost (90%), while KNN and LDA underperformed. Results show that ensemble methods handle complex, non-linear relationships effectively, outperforming simple linear or distance-based models.

## Project 03. **NetGuard - ML for Network Intrusion Detection**
This project used machine learning (Random Forest, XGBoost, KNN) to detect network intrusions on the `netflow.csv` dataset (216M+ rows). After critical data balancing via oversampling, models were tested on both binary (Benign vs. Attack) and multi-class (attack type) tasks. All models excelled at binary classification (99%+ accuracy), with Random Forest leading (99.6%). Random Forest also performed best on the multi-class task (90.9% accuracy), followed by KNN (90.4%), proving it the most robust solution overall.

## Project 04. **GraphMinds - Algorithmic Exploration of Network Communities**
This project applies multiple community detection algorithms (Girvan–Newman, Louvain, Spectral Clustering, Label Propagation, Hierarchical Clustering) on the Enron Email Network (36K+ nodes, 183K+ edges) to uncover hidden organizational structures. The study compares scalability, interpretability, and structural clarity across methods. Louvain emerged as the most balanced and efficient approach for large-scale community detection, while Spectral and Hierarchical methods provided deeper structural insights. Girvan–Newman offered accurate modular partitions but was computationally expensive, and Label Propagation delivered fast yet less stable results — highlighting key trade-offs in real-world network analysis.


## Project 05. **Final Exam - Applied Data Science in Action**

This project consists of three comprehensive real-world data science problems covering economic analysis, environmental modeling, and predictive analytics. Each problem integrates exploratory data analysis, statistical modeling, diagnostics, and interpretation to deliver meaningful insights and scalable solutions.

1️. `Mobility Matters - The Commute & Opportunity Link` : This study investigates whether shorter commute times are associated with higher economic mobility across 729 U.S. communities. Using simple and multiple regression models with geographic and state controls, the analysis finds a strong and statistically significant positive relationship — even after accounting for regional heterogeneity. The results suggest that transportation access may play a meaningful role in upward mobility.

2️. `AirSense - Intelligent AQI Forecasting System` : This problem develops a predictive framework for estimating Air Quality Index (AQI), AQI category, and dominant pollutant using environmental and pollutant data from Pune. It conatins bias analysis and KNN-based missing value imputation, Random Forest modelling. The system is fully scalable for deployment across Indian cities and supports policy-driven automation.

3️. `BoxOfficeAI - Decoding Movie Revenue Drivers` : This project analyzes the determinants of movie revenue using metadata (genre, actors, runtime) and plot text features. Three models were compared — metadata-only, text-only, and combined — with the integrated model performing best (R² ≈ 0.35). The findings show that genre and narrative themes are stronger predictors than actors, revealing how structural and storytelling elements influence commercial success.

---
## 🤝 Let’s Connect!

I’m always open to meaningful conversations, collaborative projects, and idea exchanges.  
If you’re interested in exploring new insights, working together on related topics, or contributing to ongoing discussions — feel free to reach out!  

**Let’s learn and build together 🚀**
