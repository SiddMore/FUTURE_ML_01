# FUTURE_ML_01

# 📈 Superstore Sales Forecasting

> **Task ID:** Future Interns ML-01
> **Domain:** Machine Learning / Time Series Analysis

## 🧐 Overview
This project focuses on forecasting sales for a "Superstore" using historical data. By leveraging **Facebook Prophet**, the model analyzes trends and seasonality to predict future sales performance. This task demonstrates end-to-end data handling, from preprocessing raw CSVs to generating actionable forecast visualizations.

## 🛠️ Tech Stack
* **Language:** Python 🐍
* **Core Library:** [Prophet](https://facebook.github.io/prophet/) (for time series forecasting)
* **Data Manipulation:** Pandas, NumPy
* **Environment:** Kaggle Notebooks

## 📊 Workflow & Features
1.  **Data Ingestion:** Loaded the `SampleSuperstore.csv` dataset (handling specific encodings like `latin1`).
2.  **Preprocessing:**
    * Date parsing and sorting.
    * Aggregating sales data by date to prepare for time-series modeling.
3.  **Forecasting:**
    * Initializing the Prophet model.
    * Fitting the model on historical sales data.
    * Predicting future sales trends.

## 📸 Visualizations
Here are the results from the analysis:

### 1. Sales Trends & Data Analysis
*Visualizing the historical sales patterns.*
![Sales Analysis](Screenshot%202025-12-19%20173942.png)

### 2. Model Performance
*Insights into how the model fits the training data.*
![Model Fit](Screenshot%202025-12-19%20173955.png)

### 3. Future Forecast
*The final projection of sales for the upcoming period using Prophet.*
![Final Forecast](Screenshot%202025-12-19%20174002.png)

## 🚀 How to Run
1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install pandas prophet matplotlib
    ```
3.  Open `fut-ml-01.ipynb` in Jupyter or upload it to Kaggle.
4.  Run all cells to see the forecast!

---
*Completed as part of the Future Interns program.*
