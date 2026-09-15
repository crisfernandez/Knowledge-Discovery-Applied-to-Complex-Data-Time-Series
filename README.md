# Capital Bikeshare Time Series Analysis & Forecasting

An end-to-end Knowledge Discovery and Time Series analysis project on the Capital Bikeshare system (Washington, D.C., 2011–2012). This project investigates bike rental demand dynamics under the influence of weather conditions, seasonal patterns, calendar events, and holiday effects.

---

## Repository Structure

* **`data/`**
  * `day.csv`: Aggregated daily bike rental records.
  * `hour.csv`: Hourly bike rental records.
* **`notebooks/`**
  * `Bike_Sharing_Analysis.ipynb`: Data preprocessing, outlier handling, missing value visualization, EDA, and time series profiling.
* **`docs/`**
  * `Bikeshare_Report.pdf`: Comprehensive project report detailing methodology, interpretations, and results.

---

## Key Project Highlights

* **Data Preprocessing & Cleaning:** Missing value imputation, missingness pattern visualization, temporal sequence alignment, and outlier detection/treatment.
* **Exploratory Data Analysis (EDA):** Correlation analysis between rental counts and external drivers (temperature, apparent temperature, humidity, wind speed, weather situation).
* **Time Series Profiling:** Seasonality decomposition (trend, seasonal cycles, residuals), stationarity analysis, and temporal autocorrelation structure across both hourly and daily frequencies.
* **Behavioral Analysis:** Comparative study between casual and registered users across peak hours, business days, weekends, and holidays.

---

## 📊 Dataset Overview

The dataset is sourced from the Capital Bikeshare system (Washington D.C., 2011–2012):
* **`hour.csv`**: ~17,379 records capturing hourly rental activity with environmental metrics.
* **`day.csv`**: ~731 aggregated daily observations.

**Main Features:**
* **Temporal:** `dteday`, `season`, `yr`, `mnth`, `hr`, `holiday`, `weekday`, `workingday`.
* **Weather & Environment:** `weathersit`, `temp`, `atemp`, `hum`, `windspeed`.
* **Targets:** `casual`, `registered`, and total rental count `cnt`.
