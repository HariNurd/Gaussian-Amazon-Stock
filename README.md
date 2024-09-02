# Amazon Stock Prediction Using Gaussian Process Regression

This repository contains the implementation of a machine learning model for predicting the closing price of Amazon stock using Gaussian Process Regression (GPR). The project was conducted as part of a final project for a Data Analyst Bootcamp, focusing on the application of advanced statistical methods to financial data.
Project Overview

Stock markets are one of the most dynamic and influential investment instruments in the global economy. Among the various stocks traded, Amazon.com, Inc. (AMZN) is a key focus for investors and market analysts. This project aims to predict Amazon's stock price by constructing a GPR model, analyzing historical data, and comparing its effectiveness against other statistical methods.

## Objectives

The main objectives of this project are:

- To construct a Gaussian Process Regression model to predict Amazon's stock closing price using data on Open, High, Low, and Volume (OHLV).
- To evaluate the model's performance using metrics such as RMSE, MAE, MAPE, and R-squared.
- To optimize the model's hyperparameters using techniques like Grid Search to improve prediction accuracy.

## Methodology

### Data Source

The data used in this project is sourced from Kaggle: Amazon: Historical Data & Market Trends. The dataset includes:

- Open, High, Low, and Close prices
- Volume of stocks traded
- Dividends and Stock Splits

The dataset spans from April 26, 2024, from 09:30 to 15:59, with data recorded at one-minute intervals.

## Results

The Gaussian Process Regression model, optimized using Grid Search, was effective in capturing the trends in Amazon's stock price.

## Insights & Recommendations

Insights: 
- The GPR model effectively captured the closing price trends of Amazon stock. The features such as Open, High, and Low prices had strong correlations with the Close price.

Recommendations:
- Consider using a more extensive dataset or real-time data for more accurate predictions, especially given the fast-paced nature of the stock market.
- Investors should consider dollar-cost averaging strategies due to the model’s uncertainty under volatile conditions.

## License

This work is protected under the terms set by the smartpath. Unauthorized reproduction or distribution of this material is prohibited without explicit permission.

## Acknowledgements

This project was completed by Hari Nurdianto, Kelvin Antholin, Asep Supriatna, and Achmad Yusuf as part of the Data Analyst Bootcamp. Special thanks to our mentors, javas alfreda, and the smartpath team for their guidance and support.
