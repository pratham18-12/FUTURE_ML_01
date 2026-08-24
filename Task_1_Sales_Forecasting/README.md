# Sales & Demand Forecasting

## Project Overview

This project is a Machine Learning-based Sales and Demand Forecasting system developed as part of **Future Interns - Machine Learning Task 1 (2026)**.

The project uses historical Superstore sales data to analyze sales patterns and predict future sales for the next 30 days.

## Objective

The objective of this project is to build a forecasting system that helps businesses:

* Plan inventory
* Predict future demand
* Avoid overstocking
* Improve staffing decisions
* Support budgeting and cash flow planning

## Dataset

The project uses the **Sample Superstore Dataset**, which contains historical business sales information such as:

* Order Date
* Sales
* Quantity
* Discount
* Profit
* Category
* Region

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* VS Code

## Machine Learning Model

The project uses the **Random Forest Regressor** algorithm to predict sales based on time-related features.

### Features Used

* Year
* Month
* Day
* Day of Week
* Day Number

## Model Evaluation

The model performance is evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Visualizations

The project includes:

1. Daily Sales Trend
2. Actual vs Predicted Sales
3. 30-Day Sales Forecast

## Business Value

The forecasting system helps businesses make data-driven decisions by predicting future sales trends. Businesses can use these predictions for inventory management, financial planning, staffing, and demand forecasting.

## Project Structure

```text
Task_1_Sales_Forecasting
│
├── data
│   └── Sample - Superstore.csv
│
├── notebooks
│   └── sales_forecasting.ipynb
│
├── images
│   ├── daily_sales_trend.png
│   ├── actual_vs_predicted.png
│   └── 30_day_forecast.png
│
└── README.md
```

## Author

Pratham Singh

Future Interns - Machine Learning Internship (2026)
