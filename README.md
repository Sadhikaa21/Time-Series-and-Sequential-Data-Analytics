# Time Series and Sequential Data Analytics

This repository contains a collection of experiments and implementations focused on time series data analysis, feature engineering, visualization, and forecasting techniques. The experiments cover both univariate and multivariate time series using classic and advanced models such as ARMA, ARIMA, SARIMA, and State Space models.

---

## Dataset Sources

- [Daily Minimum Temperatures in Melbourne, Australia](https://raw.githubusercontent.com/jbrownlee/Datasets/master/daily-min-temperatures.csv)
- [Monthly Sunspot Activity](https://raw.githubusercontent.com/jbrownlee/Datasets/master/monthly-sunspots.csv)
- [Ozone Level Detection Dataset](https://archive.ics.uci.edu/ml/datasets/Ozone+Level+Detection)
- [Wholesale Price Index Dataset (State Space Modeling)](https://www.stata-press.com/data/r17/wpi1.dta)

---

## List of Experiments

### 1. Load and Explore Time Series Data
- Load a time series dataset and visualize the first few rows.
- Query data using datetime indexing.
- Generate and interpret summary statistics.

### 2. Feature Engineering on Time Series
- Develop datetime-based features (day, month, year, etc.).
- Create lag features and rolling window statistics.
- Implement expanding window features for cumulative insights.

### 3. Temporal Relationship Exploration
- Visualize temporal patterns using:
  - Line plots
  - Scatter plots
  - Autocorrelation plots
- Analyze data distribution:
  - Histograms and density plots
  - Boxplots and heatmaps for seasonal variation

### 4. Resampling and Interpolation
- Perform **up-sampling** and interpolate missing data using:
  - Linear
  - Quadratic
  - Nearest neighbor
- Perform **down-sampling** and visualize summary statistics using group-level aggregations.

### 5. Stationarity, Trend, and Seasonality Check
- Analyze:
  - Trend components
  - Seasonality patterns
  - Residuals
- Perform statistical stationarity tests (ADF test, KPSS).

**Dataset**: Female Births Dataset
### 6. Autocorrelation and Partial Autocorrelation
- Generate ACF and PACF plots to identify potential AR and MA components in the time series.

**Dataset**: Female Births Dataset
### 7. Differencing and Polynomial Trend Modeling
- Implement differencing techniques to remove trend/seasonality.
- Fit polynomial regression to adjust seasonal patterns and detrend the data.

**Dataset**: Daily Minimum Temperatures

### 8. ARMA Forecasting
- Implement ARMA model to perform time series forecasting.

**Dataset**: Monthly Sunspots

### 9. ARIMA Forecasting
- Build and evaluate ARIMA model (integrated model with differencing) for univariate forecasting.

**Dataset**: Monthly Sunspots

### 10. Seasonal ARIMA (SARIMA) Forecasting
- Apply Seasonal ARIMA for capturing both non-seasonal and seasonal components.

**Dataset**: Monthly Sunspots

### 11. Multivariate ARIMA (VAR/ARIMAX)
- Implement Multivariate ARIMA techniques using external variables for enhanced forecasting accuracy.

**Dataset**: UCI Ozone Level Detection

### 12. State Space Modeling
- Implement and visualize state space models for time series decomposition and forecasting.

**Dataset**: WPI (Wholesale Price Index)

---

## Tools & Libraries Used

- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Visualization  
- `statsmodels` – Time series models (ARIMA, SARIMA, State Space)  
---

