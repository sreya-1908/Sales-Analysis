# Sales-Analysis
Overview
This project involves the analysis of sales data to identify trends and key factors impacting sales performance. The data includes weekly sales records for different stores, along with additional factors such as:
- Store Identifiers
- Date Information
- Holiday Flags
- Temperature
- Fuel Prices
- Consumer Price Index (CPI)
- Unemployment Rates
  
The analysis helps in understanding how these factors affect sales, particularly in the retail industry.

# Features
- Data Cleaning & Preparation:
  - Handling missing data
  - Filtering relevant features for analysis

- Descriptive Statistics:
  - Analysis of central tendencies (mean, median, mode)
  - Identifying outliers in sales performance
  
- Visualization:
  - Graphical representation of sales trends over time
  - Visualization of the impact of external factors like holidays, temperature, fuel prices, etc.


- Predictive Modeling: 
  - Time series analysis to forecast future sales
  - Regression models to assess relationships between sales and other factors

# Usage
1. Launch the Jupyter Notebook:
   jupyter notebook sales.ipynb
2. Follow the steps in the notebook to load the data and run the analysis.
# Data
The dataset used in this analysis consists of the following columns:
- `Store`: Unique ID for each store.
- `Date`: The week of sales.
- `Weekly_Sales`: Total sales for the store.
- `Holiday_Flag`: Whether the week included a holiday (1) or not (0).
- `Temperature`: Average temperature for the week.
- `Fuel_Price`: Fuel prices in the area.
- `CPI`: Consumer Price Index.
- `Unemployment`: Unemployment rate in the area.
# Results
-Sales Trends: Insights into how weekly sales fluctuate across stores.
- Factor Impact: Understanding how holidays, temperature, and fuel prices impact sales performance.
- Forecasting: Time series forecasting models to predict future sales.

