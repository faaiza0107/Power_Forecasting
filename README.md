# ⚡ PJM Power Prediction & Forecasting

An end-to-end time-series forecasting project for analyzing PJM hourly electricity demand and generating a 30-day ahead power demand forecast using Python, data preprocessing, feature engineering, and an interactive Streamlit dashboard.

## 📌 Project Overview

This project analyzes historical PJM electricity consumption data to identify hourly, weekly, monthly, and seasonal demand patterns and generate future electricity demand predictions.

The project includes data cleaning, anomaly handling, feature engineering, exploratory data analysis, forecasting, model evaluation, and interactive visualization.

## 🚀 Key Features

- Historical PJM electricity demand analysis
- Data cleaning and preprocessing
- Duplicate timestamp handling
- Missing-value detection and time-based interpolation
- Outlier/anomaly correction
- Hourly, weekly, monthly, and seasonal pattern analysis
- 30-day hourly electricity demand forecasting
- Confidence interval visualization
- Forecast performance metrics
- Interactive Streamlit dashboard
- Downloadable forecast CSV
- Date-wise forecast filtering

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Plotly
- Streamlit
- OpenPyXL

## 📊 Data Preprocessing

The dataset is processed through:

1. Chronological sorting
2. Duplicate timestamp handling
3. Hourly frequency conversion
4. Missing-value detection
5. Time-based interpolation
6. Outlier correction
7. Feature engineering

Time-based features include Hour, Day of Week, Month, Year, Weekend indicator, and Season.

## 📈 Exploratory Data Analysis

The dashboard provides analysis of:

- Historical electricity demand
- Load distribution
- 24-hour demand patterns
- Weekday vs. weekend demand
- Monthly demand trends
- Seasonal electricity consumption

## 🔮 Forecasting

The application generates hourly forecasts for a configurable number of days, with 30 days as the default forecast horizon.

The forecast dashboard provides:

- Predicted electricity demand in MW
- Lower and upper confidence bounds
- Historical vs. predicted demand visualization
- Forecasted peak and trough
- Average forecasted demand
- Downloadable forecast results

## 📏 Model Evaluation

The forecasting section evaluates predictions using:

- MAE — Mean Absolute Error
- RMSE — Root Mean Squared Error
- R² Score
- MAPE — Mean Absolute Percentage Error

## 💻 Run the Project Locally

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit application

```bash
streamlit run app.py
```

## 📁 Project Structure

```text
PJM-Power-Prediction/
│
├── app.py
├── requirements.txt
├── PJMW_MW_Hourly.xlsx
├── pjm_30day_forecast.csv
└── README.md
```

## 🎯 Project Objective

The objective of this project is to demonstrate how data science and time-series forecasting techniques can be applied to electricity demand data to understand consumption patterns and support future power-demand planning.

## 👩‍💻 Author

**Faaiza Mastani**

B.Tech — Electrical & Electronics Engineering  
Aspiring Data Scientist | Machine Learning & Data Analytics
