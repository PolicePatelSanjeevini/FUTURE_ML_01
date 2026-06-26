Sales Forecasting Using Superstore Dataset

Project Overview

This project aims to forecast future sales using historical sales data from the Superstore dataset. By analyzing past sales trends and patterns, the model predicts future demand and provides actionable business insights for inventory planning, budgeting, and decision-making.

Objective
Predict future sales using historical transaction data.
Identify sales trends and patterns.
Generate business-friendly visualizations.
Provide insights to support business planning.
Dataset

Dataset: Superstore Dataset Final

The dataset contains:

Order Date
Sales
Profit
Quantity
Category
Sub-Category
Region
Customer Information
Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
XGBoost
Google Colab
Project Workflow
1. Data Preprocessing
Loaded and cleaned the dataset.
Converted date columns into datetime format.
Aggregated sales at a daily level.
2. Feature Engineering

Created time-based features:

Year
Month
Day
Day of Week
Quarter
Week of Year

Created forecasting features:

Lag 1 Sales
Lag 7 Sales
Lag 30 Sales
Rolling Mean (7 Days)
Rolling Mean (30 Days)
3. Model Building

Used XGBoost Regressor to learn historical sales patterns and predict future sales.

4. Model Evaluation

Evaluated the model using:

MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
R² Score
5. Forecasting

Generated sales forecasts for the next 30 days based on historical trends.

Results

The model successfully captured historical sales patterns and generated future sales predictions.

Generated Outputs:

Historical Sales Trend Visualization
Actual vs Predicted Sales Comparison
Feature Importance Analysis
30-Day Future Sales Forecast
Business Insights and Recommendations
Business Insights
Sales forecasting helps businesses anticipate future demand.
Inventory levels can be optimized based on predicted sales.
Staffing and operational planning can be improved.
Forecasts support budgeting and strategic decision-making.
Future Improvements
Incorporate holiday and seasonal effects.
Use advanced time-series models such as Prophet or LSTM.
Develop an interactive Power BI dashboard.
Forecast sales by category and region.
Conclusion

This project demonstrates how machine learning can be used to forecast future sales and support data-driven business decisions. The generated forecasts can help store owners, startup founders, and business managers improve planning and operational efficiency.
