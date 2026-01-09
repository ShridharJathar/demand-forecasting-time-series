# 📈 Demand Forecasting Using Time Series

**SARIMA | Prophet | Rolling Forecasts**

## 📌 Business Problem

Accurate demand forecasting is essential for inventory planning, procurement, and capacity management.
Poor forecasts can lead to **stock-outs**, **excess inventory**, and increased operational costs.

This project demonstrates an **end-to-end demand forecasting workflow** using time series techniques to support data-driven supply chain decisions.

---

## 📊 Dataset

* **Frequency:** Monthly
* **Target variable:** Sales / Demand
* **Time period:** 2018–2024
* **Data characteristics:**

  * Clear long-term trend
  * Strong annual seasonality
  * Realistic demand variability

> Note: The dataset is a simulated business dataset designed to replicate real-world demand patterns.

---

## 🔍 Project Approach

1. Exploratory Data Analysis (EDA)
2. Trend and seasonality decomposition
3. Stationarity testing and differencing
4. Model development and comparison:

   * SARIMA
   * Prophet
   * Rolling Forecasts
5. Model evaluation using business-friendly metrics
6. Business insights and recommendations

---

## 🧠 Models Used

### 🔹 SARIMA

* Captures trend, seasonality, and autocorrelation
* Strong statistical baseline for demand forecasting

### 🔹 Prophet

* Automatically models trend and seasonality
* Easy to interpret and explain to business stakeholders

### 🔹 Rolling Forecast

* Retrains the model at each step using the latest data
* Closely simulates real-world forecasting operations

---

## 📈 Evaluation Metrics

* **MAPE (Mean Absolute Percentage Error):**
  Measures average percentage error, easy for business interpretation
* **RMSE (Root Mean Squared Error):**
  Penalizes large forecasting errors

---

## 📊 Results Summary

| Model          | Key Insight                                 |
| -------------- | ------------------------------------------- |
| SARIMA         | Strong statistical performance              |
| Prophet        | Business-friendly and interpretable         |
| Rolling SARIMA | Best real-world simulation and adaptability |

---

## 💡 Business Impact

* Improved demand visibility
* Better inventory and procurement planning
* Reduced risk of over-stocking and stock-outs
* Supports data-driven supply chain decisions

---

## ⚠️ Limitations

* External drivers such as promotions, pricing, and holidays are not included
* Single-product forecasting only

---

## 🔮 Future Enhancements

* Add external variables (promotions, holidays, pricing)
* Extend to multi-product forecasting
* Automate retraining and monitoring
* Deploy forecasts through dashboards

---

## 🛠 Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Statsmodels
* Prophet
* Scikit-learn

---

## 📎 Author

Shridhar Jathar
Data Analytics | Supply Chain | Time Series Forecasting
