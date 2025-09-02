# ARIMA vs Machine Learning Models: Forecasting NGX Stock Prices

This repository contains a comprehensive analysis and forecasting project that compares **ARIMA (AutoRegressive Integrated Moving Average)** models with modern **machine learning techniques** for predicting stock prices of companies listed on the **Nigerian Exchange (NGX)**.  

The primary objective of this project is to evaluate the effectiveness of traditional time series models versus machine learning approaches in capturing stock price trends, patterns, and volatility over time.

---

## 📂 Project Structure

- **NGX Stocks 2000 - 2025.csv**  
  Historical dataset of NGX stock prices from 2000 to 2025.  

- **arima_vs_ml_models.ipynb**  
  Jupyter Notebook with step-by-step analysis, preprocessing, visualization, and model comparison.  

---

## ⚡ Methodology

1. **Data Preparation**  
   - Cleaning, handling missing values, and formatting time series data.  
   - Exploratory Data Analysis (EDA) with plots and descriptive statistics.  

2. **Modeling**  
   - **ARIMA**: Captures autocorrelation, trends, and seasonality.  
   - **Machine Learning Models**:  
     - Linear Regression  
     - Random Forest Regressor  
     - Support Vector Regression (SVR)  
     - (Other models can be added for extension)  

3. **Evaluation Metrics**  
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Error (RMSE)  
   - R² Score  

4. **Visualization**  
   - Actual vs Predicted stock price trends.  
   - Residual analysis.  
   - Model comparison plots.  

---

## 🚀 Key Findings

- ARIMA models are effective for capturing short-term dependencies but may struggle with nonlinear relationships.  
- Machine learning models provide flexibility and can capture complex patterns, but they often require more tuning and larger datasets.  
- Combining both approaches may yield improved forecasting performance.  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Statsmodels  

---

## 📌 How to Use

1. Clone this repository:  
   ```bash
   git clone https://github.com/Favourboi/arima_vs_ML_models_for_forecasting.git
   cd arima_vs_ML_models
