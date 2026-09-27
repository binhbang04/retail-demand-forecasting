# Retail Demand Forecasting

## Overview
End-to-end retail demand forecasting project using **statistical time series models** and **machine learning methods** on Walmart store sales data. The project compares traditional ML regressors, classical time series models, and advanced ensemble methods.

## Dataset
- **Walmart Store Sales** (`Walmart.csv`) — Weekly sales data across multiple stores
- Features: `Weekly_Sales`, `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`, `Holiday_Flag`, etc.

## Methodology

### 1. Exploratory Data Analysis (EDA)
- Sales trend analysis and seasonal decomposition
- Holiday impact analysis (boxplots)
- Correlation heatmap between features

### 2. Data Preprocessing
- Outlier detection and treatment
- Feature engineering (time-based features)
- Train/test splitting and feature scaling

### 3. Traditional ML Models
| Model | Description |
|-------|-------------|
| Linear Regression | Baseline model |
| Polynomial Regression | Non-linear relationships |
| Ridge / Lasso / ElasticNet | Regularized regression |
| Decision Tree | Non-parametric model |
| Random Forest | Ensemble bagging |
| Gradient Boosting | Ensemble boosting |

### 4. Statistical Time Series Models
- Moving Average
- Simple Exponential Smoothing (SES)
- Holt-Winters Exponential Smoothing
- ARIMA / SARIMA

### 5. Evaluation Metrics
- RMSE (Root Mean Squared Error)
- R² Score

## Tech Stack
- Python, NumPy, Pandas
- Scikit-learn (ML models)
- Statsmodels (time series)
- Matplotlib, Seaborn (visualization)

## Project Structure
```
├── code_retail_forecast.ipynb   # Main analysis notebook
├── Walmart.csv                  # Dataset
├── report_retail_forecast.pdf   # Detailed report
├── .gitignore
└── README.md
```

## How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
jupyter notebook code_retail_forecast.ipynb
```
