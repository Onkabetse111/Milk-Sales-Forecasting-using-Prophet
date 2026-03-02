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

```markdown
---

## Forecasting Insights
- The Prophet model captures the overall upward trend in daily milk sales.
- Weekly seasonality shows higher sales on specific days of the week.
- Yearly seasonality highlights recurring peaks during certain months.
- RMSE of ~0.41 indicates reasonably accurate predictions.
- Confidence intervals provide a sense of uncertainty, useful for inventory planning.
- Accuracy could be improved by adding holidays, promotions, or economic indicators.






