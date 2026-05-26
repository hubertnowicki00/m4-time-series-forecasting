# M4 Hourly Time Series Analysis and Forecasting

## 1. Project Description

This project presents a comprehensive time series analysis, including statistical modeling and forecasting, performed on a dedicated hourly time series from the M4 Forecasting Competition. The primary goal of the analysis was to decompose the series, analyze its underlying patterns, and forecast the next 24 hours using statistical models.

The project includes:

- Exploratory Data Analysis (EDA) and descriptive statistics
- Time series visualizations (time plots, seasonal patterns, ACF)
- Classical time series decomposition ($X_t = m_t + s_t + Y_t$)
- Moving average trend estimation and polynomial trend re-estimation
- Residual diagnostics and independence testing (Ljung-Box test)
- ARIMA model selection via AIC Grid Search
- Predictive forecasting and evaluation against baseline models (Mean, Naïve, Seasonal Naïve)
- Error metric calculation (MAE and RMSE)

## 2. Data Source

The analysis was conducted using the **M4 Forecasting Competition Dataset**.

Dataset source:

- Kaggle / M4 Competition
- https://www.kaggle.com/datasets/yogesh94/m4-forecasting-competition-dataset

The specific dataset extracted for this project is the **H7 Hourly Time Series**, utilizing:

- `Hourly-train.csv` (700 observations for training)
- `Hourly-test.csv` (First 24 observations extracted for testing/validation)
- `m4_info.csv` (Metadata containing frequency and starting dates)

## 3. Tech Stack and Methodology

### Tech Stack

- **Python**
- **Pandas** — data manipulation and time series indexing
- **NumPy** — numerical operations and polynomial fitting
- **Matplotlib** — plotting and visualization
- **Statsmodels** — statistical tests (Ljung-Box), ACF/PACF plots, and ARIMA modeling
- **Scikit-learn** — model evaluation metrics (MAE, RMSE)


## 4. Repository Contents

```text
├── report.pdf
│
├── second_project.ipynb
│
└── README.md
