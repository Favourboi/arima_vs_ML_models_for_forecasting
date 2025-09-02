Stock Price Forecasting: ARIMA vs Machine Learning Models

This project explores the comparative performance of statistical time series models and machine learning algorithms in forecasting stock prices on the Nigerian Exchange (NGX). Using Zenith Bank’s historical stock data (2000–2025), we evaluate how well different approaches capture price trends, seasonality, and volatility.

📌 Project Overview

Forecasting stock prices is a critical task in financial markets, influencing investment strategies, risk management, and policy decisions. Traditional models such as ARIMA are well-established for handling time series, but the rise of machine learning offers alternative perspectives for predictive modeling.

This project compares:

ARIMA (Auto-Regressive Integrated Moving Average) – a classical statistical model designed for time-dependent data.

Machine Learning Models – trained to capture non-linear patterns in historical stock data.

The comparison aims to provide insights into the strengths and weaknesses of both approaches when applied to real-world financial forecasting.

📊 Dataset

Source: NGX Stocks Dataset (2000–2025)

Focus Column: Price (Zenith Bank stock closing prices)

Features: Daily historical stock prices, including open, high, low, close, and volume.

⚙️ Methodology

Data Preprocessing

Cleaning missing values

Time-series indexing

Train-test split for evaluation

Modeling

ARIMA model fitting and residual diagnostics

Machine learning models (baseline regressors, advanced learners)

Evaluation Metrics

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Forecast visualization

Comparison & Analysis

Strengths and limitations of each approach

Insights for financial decision-making

📈 Results & Insights

ARIMA excels in short-term linear forecasting.

Machine learning models can capture non-linear trends and adapt better to complex behaviors.

Hybrid approaches may provide stronger predictive accuracy in financial contexts.

🚀 Technologies Used

Python

pandas, numpy, matplotlib, seaborn

statsmodels (ARIMA)

scikit-learn (ML models)

📬 Author

Favour Ugorji
Data Scientist | Financial Data Analytics Enthusiast
