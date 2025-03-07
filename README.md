# Demand Forecasting and Inventory Optimization 
# Overview
Demand Forecasting is the process of predicting future customer demand for a product or service using historical data and external factors such as seasonality, promotions, and trends. Inventory Optimization ensures that the right amount of stock is available at the right time while minimizing costs.
This project leverages SARIMA (Seasonal AutoRegressive Integrated Moving Average) for demand forecasting and economic order quantity (EOQ), safety stock, and reorder point calculations for inventory optimization.
# Project Workflow
1. Data Collection & Preprocessing:
Load historical sales and inventory data,
Handle missing values and format date columns
2. Demand Forecasting using SARIMA:
Identify seasonality patterns in demand,
Use ACF (Autocorrelation Function) & PACF (Partial Autocorrelation Function) to determine ARIMA parameters
Train SARIMA model and forecast demand for the next 10 days
3. Inventory Optimization
Calculate Optimal Order Quantity (EOQ), Reorder Point, and Safety Stock;
Implement cost analysis (holding cost, stockout cost)
4. Results & Insights:
Forecasted demand with 90% accuracy,
Optimized inventory strategy to reduce overstocking and minimize stockouts
# Key Features
1. Demand Forecasting using SARIMA for accurate predictions
2. Automated Inventory Optimization with EOQ and reorder point calculations
3. Visualization of demand and inventory trends using Matplotlib & Plotly
4. Cost Analysis to minimize holding costs and stockout risks
# Technologies Used
Python
Pandas, NumPy (Data Processing)
Matplotlib, Plotly (Data Visualization)
Statsmodels (SARIMA), Time Series Forecasting (Predictive Analytics)
# Results
Optimal Order Quantity: 236,
Reorder Point: 235,
Safety Stock: 114,
Total Inventory Cost Reduction: 15%
