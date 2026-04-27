# time-series-demand-forcasting
Sales demand forecasting using time-series feature engineering and machine learning.

# Time Series Demand Forecasting

##  Project Overview

This project predicts sales demand using time-series data using machine learning.

##  Techniques Used

* Lag Features (lag_1, lag_7, lag_30)
* Rolling Mean (7-day average)
* Random Forest Regression

##  Results

* Final MAE: 6.59 (~12-13% error)

##  Key Insights

* Weekly trends are very important (lag_7)
* Rolling mean captures stable demand pattern
* Model captures trend well but misses sudden spikes

##  Business Use Case

This model can help businesses plan inventory based on demand trends.

## 🛠 Tools Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
