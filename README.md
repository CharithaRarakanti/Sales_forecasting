# Sales_forecasting
A comprehensive HR Analytics Dashboard using Power BI to analyze employee attrition, demographics, and job roles for data-driven decision-making.
# Project Objective
* Goal: The goal of this project was to apply various quantitative methods, (i.e. Times Series Models and Causal Models) to forecast the sales of the products available in the dataset.

* Perform time series analysis to understand the data and trends
* Use multiple forecasting models on train dataset
* Finally select the best model to run the test data
# Models covered in the notebook include:

* Seasonal Naive Model
* Holt-Winters Model (Triple Exponential Smoothing)
* ARIMA Model and Seasonal ARIMA Models
* Linear Regression Model
# Features

* Sales by Category and Sub-Category: Visualize sales data broken down by major product categories and sub-categories.

* Sales by Ship Mode: Analyze sales performance based on different shipping methods.

* Monthly Sales and Profit: Track monthly sales and profit trends year-over-year.

* Sales and Profit by State: Geographic analysis of sales and profit across various states.

* Sales by Segment and Payment Mode: Understand sales distribution across different customer segments and payment methods.

* Sales Forecasting: Predict future sales with a 15-day sales forecast.

# Visualizations
The dashboard includes the following visualizations:

* Sales by Category: Bar chart showing sales by major product categories.

* Sales by Sub-Category: Detailed view of sales by sub-categories within each main category.

* Sales by Ship Mode: Pie chart displaying sales distribution by shipping methods.

* Monthly Sales and Profit: Line charts illustrating monthly sales and profit trends.

* Sales and Profit by State: Map visualization of sales and profit across different states.

* Sales by Segment: Pie chart showing sales by customer segment.

* Sales by Payment Mode: Bar chart illustrating sales distribution by payment methods.

* Sales Forecasting: Line chart predicting sales for the next 15 days.

# Skills Used

* Power BI: Data import, transformation, and visualization.

* Data Analysis: Statistical analysis of sales data.

* Data Visualization: Designing interactive and user-friendly dashboards.

* Predictive Analytics: Implementing sales forecasting techniques.

* Communication Skills: Presenting data insights effectively.

# Conclusion

We considered different time-series models as well as a regression model for time series forecasting. From our results we saw that the linear regression model outperformed the other time-series models. Therefore, for this dataset we could use a regression model, rather than a time-series model to forecast sales. One of the main assumptions of regression models is that the patterns in the historical data will be repeated in the future, and since our data was highly seasonal and had a linear trend, it made sense why the linear regression model out-performed the other models.
