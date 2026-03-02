# Milk Sales Forecasting using Prophet

## Project Overview
This project forecasts daily milk sales using Python and the Prophet library. It demonstrates time series analysis, preprocessing, model fitting, evaluation, and visualization of seasonal trends. The goal is to provide actionable insights for inventory planning and sales forecasting.

---

## Files in This Repository
- `milk_sales.csv.csv` – Dataset containing daily milk sales (`date`, `units_sold`).  
- `milk_sales_forecast.ipynb` – Colab notebook with full preprocessing, modeling, evaluation, and visualization.  
- `images/` (optional) – Folder for exported plots like forecast and component plots.  

---

## How to Run
1. Open `milk_sales_forecast.ipynb` in **Google Colab** or **Jupyter Notebook**.  
2. Install required packages:
```bash
pip install pandas matplotlib prophet
```

---

## Forecasting Insights
- The Prophet model effectively captures the overall increasing trend in daily milk sales.
- Clear weekly seasonality is observed, showing higher sales on specific days of the week.
- Yearly seasonality patterns are also visible, reflecting recurring peaks during certain months.
- RMSLE of ~0.4998 indicates reasonably accurate predictions on a logarithmic scale.
- Confidence intervals in the forecast provide a sense of prediction uncertainty, helping plan for variability in demand.
- Insights can be used for inventory planning, reducing overstocking or stockouts, and preparing for peak sales periods.
- Forecast accuracy could be improved by incorporating holidays, promotions, or relevant economic indicators as additional regressors.


---

## Model Workflow

Data Preprocessing: Aggregated daily sales and renamed columns to ds (date) and y (units sold).

Model Fitting: Prophet model trained on historical data.

Forecasting: Predictions generated for 365 future days.

Evaluation: RMSLE calculated to measure performance.

Visualization: Forecast and component plots show trends and seasonal patterns.

--- 

## Skills Demonstrated

Time series forecasting with Python and Prophet

Data preprocessing and cleaning

Model evaluation (RMSLE)

Visualization of trends and seasonality

Portfolio-ready documentation







