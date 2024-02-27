# -Customer-Behavior-Prediction-towards-Interest-Rate-Changes-using-Macroeconomic-Variables

## Introduction
This project aims to predict customer behavior in response to changes in interest rates by analyzing macroeconomic variables. By exploring the relationship between macroeconomic indicators such as inflation, long-term interest rates, unemployment rates, short-term interest rates, and the Household Credit Card Rate (HCCR), we seek to understand how shifts in these factors influence customer decisions and behaviors.

## Objective
The primary goal is to analyze how changes in macroeconomic factors affect customer behavior, particularly regarding interest rates. This analysis will enable financial institutions to make informed decisions about interest rate adjustments and other financial policies, ultimately enhancing customer satisfaction and optimizing financial strategies.

## Methodology
Importing Libraries
The project utilizes essential libraries such as pandas, numpy, matplotlib, and scikit-learn for data manipulation, visualization, and machine learning tasks.

### Data Importation
The dataset, which includes various macroeconomic variables along with the target variable (HCCR), is imported and prepared for analysis.

### Exploratory Data Analysis (EDA)
An initial exploration of the dataset is performed to understand the distributions of variables, identify correlations, and visualize trends through heatmaps and time series plots.

### Normalization
Data normalization is applied to ensure all variables are on the same scale, which is crucial for the effectiveness of certain machine learning algorithms.

### Principal Component Analysis (PCA)
PCA is used to reduce the dataset's dimensionality, simplifying the analysis and improving computational efficiency while retaining important information.

### Regression Algorithms
Various regression algorithms, including Multiple Linear Regression, Polynomial Regression, Decision Tree Regression, and Random Forest Regression, are employed to model the relationship between macroeconomic variables and HCCR.

### Ordinary Least Squares (OLS) Method
The OLS method is utilized to estimate the parameters of the linear regression model, providing insights into the significance of different macroeconomic variables.

### Time Series Analysis
Time series analysis techniques, including the Autocorrelation Function (ACF), Partial Autocorrelation Function (PACF), and ARIMA modeling, are used to analyze temporal patterns and forecast future values of HCCR.

## Conclusion
This project provides valuable insights into the dynamics of customer behavior in response to interest rate changes, informed by an analysis of key macroeconomic variables. By leveraging machine learning and time series analysis techniques, financial institutions can gain a deeper understanding of market dynamics, enabling data-driven decision-making to optimize interest rate policies.
