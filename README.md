# Uber-Lyft-Cab-prices
Price Prediction &amp; Analysis

# Uber and Lyft Cab Prices: Price Prediction & Analysis

## 📌 Project Overview
This project analyzes ride-hailing data from Uber and Lyft to identify the key factors influencing cab prices (such as distance, surge multipliers, and weather conditions). The ultimate goal is to build a predictive machine learning model to estimate ride prices accurately.

## 📊 Data Source
* **Datasets Used:** Uber/Lyft ride records and historical weather data (merged via timestamps and locations).
* **Key Features:** Distance, surge multiplier, weather summary, temperature, wind, and time of day.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Linear Regression)

## 📈 Key Insights (Work in Progress)
* **Distance vs. Price:** (Example: Distance has the strongest linear correlation with price, as expected.)
* **Surge Multipliers:** (Example: Lyft's surge pricing structure impacts final costs significantly more during peak hours compared to Uber.)
* **Weather Impact:** (Example: Surprisingly, light rain has a negligible impact on baseline prices compared to high demand.)

## 🤖 Model Performance
We established a baseline using a **Linear Regression** model:
* **R² Score:** `0.53` (The model explains 53% of the price variance)
* **RMSE (Root Mean Squared Error):** `$6.37` (On average, predictions deviate by $6.37)

  
## 🚀 How to Run the Project

Follow these steps to set up and run this data analytics project on your local machine:

### 1. Clone the Repository
Open Git Bash (or your terminal) and run the following command to clone the project:
```bash
git clone [https://github.com/zikra-data-analytics/Uber-Lyft-Cab-Prices.git](https://github.com/zikra-data-analytics/Uber-Lyft-Cab-Prices.git)
