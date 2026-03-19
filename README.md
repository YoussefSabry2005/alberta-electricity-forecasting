# ⚡ Alberta Electricity Demand Forecasting

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python)
![R](https://img.shields.io/badge/R-4.0+-276DC3?style=flat&logo=r)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-red?style=flat)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat)

A time series forecasting project that predicts electricity demand in Alberta using AESO (Alberta Electric System Operator) data, applying ARIMA and XGBoost models in Python and R.

---

## 📌 Project Overview

Accurate electricity demand forecasting is critical for grid stability, energy planning, and reducing operational costs. This project analyzes historical electricity consumption patterns in Alberta and builds forecasting models to predict future demand with high accuracy.

---

## 🎯 Objectives

- Collect and process historical electricity demand data from AESO
- Perform time series analysis to identify trends and seasonality
- Build ARIMA model for statistical forecasting
- Build XGBoost model for machine learning-based forecasting
- Compare model performance and generate demand predictions
- Visualize forecasts with interactive charts

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.10+** | Core programming language |
| **R 4.0+** | Statistical modeling and ARIMA |
| **Pandas** | Data manipulation |
| **XGBoost** | Gradient boosting forecasting model |
| **Statsmodels** | ARIMA implementation in Python |
| **Matplotlib / Seaborn** | Visualization |
| **Jupyter Notebook** | Development environment |

---

## 📂 Dataset

- **Source:** [Alberta Electric System Operator (AESO)](https://www.aeso.ca/market/market-and-system-reporting/data-requests/historical-pool-price/)
- **Contents:** Historical hourly electricity demand, pool prices, and generation data
- **Coverage:** Multi-year Alberta grid data
- **Frequency:** Hourly observations

---

## 🔬 Methodology

1. **Data Collection** — Download AESO historical demand data
2. **Data Preprocessing** — Handle missing values, normalize, resample
3. **EDA** — Analyze trends, seasonality, and anomalies
4. **Stationarity Testing** — ADF test, differencing
5. **ARIMA Modeling** — ACF/PACF analysis, parameter selection, model fitting
6. **XGBoost Modeling** — Feature engineering, lag features, training
7. **Model Evaluation** — RMSE, MAE, MAPE comparison
8. **Forecasting** — Generate short and long-term demand predictions

---

## 📊 Expected Results

- Short-term (24-hour) and long-term (monthly) demand forecasts
- Comparison of ARIMA vs XGBoost performance metrics
- Identification of seasonal patterns in Alberta electricity demand
- Interactive visualization of actual vs predicted demand

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/YoussefSabry2005/alberta-electricity-forecasting.git

# Navigate to project directory
cd alberta-electricity-forecasting

# Install Python dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

# For R analysis
# Open R scripts in /r_analysis folder
```

---

## 📁 Project Structure

```
alberta-electricity-forecasting/
│
├── data/               # Raw and processed AESO datasets
├── notebooks/          # Jupyter notebooks for EDA and modeling
├── r_analysis/         # R scripts for ARIMA modeling
├── src/                # Python scripts
├── visualizations/     # Forecast charts and plots
├── requirements.txt    # Python dependencies
└── README.md
```

---

## 🌍 Why Alberta?

Alberta has a unique deregulated electricity market — one of the few in Canada. This makes it an interesting case study for demand forecasting as prices and consumption are directly influenced by market forces, weather, and industrial activity (particularly oil sands operations).

---

## 👤 Author

**Youssef Sabry**
- 📍 Edmonton, Alberta, Canada
- 🎓 BSc Data Science — MacEwan University (Graduating Winter 2028)
- 💼 [LinkedIn](https://www.linkedin.com/in/youssef-sabry)
- 🐙 [GitHub](https://github.com/YoussefSabry2005)

---

## 📌 Status

🔄 **In Progress** — Currently in data collection and preprocessing phase

---

*Part of my Data Science portfolio. Built to demonstrate time series analysis and forecasting skills for internship and job applications.*
