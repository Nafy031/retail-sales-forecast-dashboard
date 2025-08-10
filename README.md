# 🛍 Retail Sales Forecast Dashboard

## 📌 Project Overview
This project analyzes historical retail sales data and uses **time series forecasting** to predict sales for each product category over the next 6 months.  
The results are presented in an **interactive Power BI dashboard** with slicers, KPI cards, and confidence intervals.

---

## 🎯 Objectives
- Clean and prepare raw sales data for analysis.
- Aggregate sales **monthly** and **by category**.
- Build forecasting models for each category using **Prophet**.
- Combine historical and forecasted data into a BI-friendly format.
- Create an interactive Power BI dashboard to explore trends and predictions.

---

## 🛠 Tools & Technologies
- **Python** → pandas, Prophet, matplotlib
- **Power BI** → data modeling, DAX measures, visuals
- **GitHub** → version control and portfolio hosting

---

## 📂 Project Structure
├── 01_clean_and_aggregate.ipynb # Step 1: Data cleaning & aggregation
├── 02_forecast_by_category.ipynb # Step 2: Forecasting by category
├── superstore_clean.csv # Cleaned dataset
├── monthly_sales_by_category.csv # Monthly category aggregates
├── forecast_by_category.csv # Forecast output from Prophet
├── bi_category_actuals_forecast.csv # Combined actual + forecast for Power BI
├── Sales_Forecast_Dashboard.pbix # Power BI dashboard file
└── README.md # Project documentation


---

## 📊 Data Preparation (Python)
1. Imported raw dataset using pandas.
2. Converted date columns to proper datetime format.
3. Aggregated sales monthly by category.
4. Saved clean datasets for forecasting and BI.

---

## 📈 Forecasting (Python + Prophet)
- Forecasted 6 months of future sales for **each category**.
- Generated predictions with:
  - **yhat** → expected value
  - **yhat_lower** / **yhat_upper** → confidence intervals
- Plotted forecasts with matplotlib to visually confirm trends.

---

## 📑 Power BI Dashboard
**Key features:**
- **Line Chart:** Actual vs Forecast sales, with category selection.
- **Confidence Bands:** Visual range for forecast uncertainty.
- **KPI Cards:** Total actual sales (last 12M), forecast (next 6M), YoY%.
- **Bar Chart:** Actual sales by category.
- **Slicers:** Interactive filters for category and date.

---

## 📷 Dashboard Preview


---

## 📌 Insights
- Categories show seasonal patterns that improve forecast accuracy.
- Forecasts indicate expected growth in **[insert category name]**.
- Power BI slicers and KPIs allow quick comparison between categories.

---

## 🚀 How to Use
1. Clone this repository:
```bash
git clone https://github.com/Nafy031/retail-sales-forecast-dashboard.git
```
Open and run the Python notebooks in order:
01_clean_and_aggregate.ipynb
02_forecast_by_category.ipynb
Open Sales_Forecast_Dashboard.pbix in Power BI Desktop.

📚 Skills Demonstrated
Data Cleaning & Transformation (pandas, datetime handling)
Time Series Forecasting (Prophet)
Data Visualization (matplotlib, Power BI)
DAX Calculations (measures, time intelligence)
Dashboard Design (KPIs, slicers, interactive filtering)
