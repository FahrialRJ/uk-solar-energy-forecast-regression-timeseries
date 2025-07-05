# Solar Energy Forecasting in the UK (2010-2030)

This Python program analyzes and forecasts solar energy production in the United Kingdom using multiple statistical approaches. It was developed for academic purposes as part of a final project in statistics course. This program has several features:

- Loads data from Excel or uses sample fallback data
- Cleans, renames, and analyzes for outliers (IQR + boxplot)
- Calculates average historical growth of solar panel installations
- Applies Simple Moving Average time series forecasting, Linear Regression, and Hybrid Model combining regression with Simple Moving Average trend
- Evaluate models with RMSE, MAE, and MAPE
- Conducts Pearson correlation analysis, Hypothesis testing for regression coefficients, and Shapiro-Wilk for normality test of residuals
- Visualizes Time series with projections up to 2030, regressions with residual diagnostics, and performance comparison of all models
- Saves forecast results and summary metrics as .csv files