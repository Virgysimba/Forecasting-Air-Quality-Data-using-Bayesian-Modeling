# Forecasting-Air-Quality-Data-using-Bayesian-Modeling

# Overview

This project aims to predict the concentration of PM2.5, a key air pollutant, based on 23 environmental parameters. The study utilizes pollutant data from Taiwan’s Environmental Protection Administration. Crucial workflow steps, including data preprocessing, splitting into training and testing sets, and applying models are implemented. Ensemble, Gaussian Process Regression(GPR), Long Short-Term Memory (LSTM) with HMM, Long Short-Term Memory (LSTM), and Bayesian Ridge are applied to model and predict the possible concentration (PM2.5). Performance evaluation metrics such as MSE, MAE, and R² help identify the Bayesian Ridge Regression model as the best performer for predicting PM2.5 concentrations.

The data set is ideal for researchers and individuals interested in studying air quality and low-cost sensors in PM measurement. The dataset is stored in CSV format and can be opened using editors like Microsoft Excel, Google Sheets, LibreOffice Calc, etc.  . We consider these models from a performance perspective and use evaluation metrices such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²) measures. The best model was determined to be the Bayesian Ridge Regression model with BCIS results being higher than their respective actual values, making the model ideal for air quality prediction
