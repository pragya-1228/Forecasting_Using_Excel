# Excel Forecasting Project: Sales & Time Series Analysis

## 🎯 Overview

This repository contains the Excel file and detailed instructions demonstrating how to perform **time series forecasting** for business data, focusing on methods that account for seasonality and confidence levels. This is a must-know skill for financial and data analysts.

The project uses a hotel sales data example to illustrate the different forecasting techniques available in Microsoft Excel.

***

## 📊 Key Topics & Excel Functions

This project showcases the application of the following core Excel forecasting tools:

1.  **Linear Trend Forecasting:**
    * `=FORECAST.LINEAR(x, known\_y's, known\_x's)`: Used to project future values based on a straight-line trend.
2.  **Seasonal Forecasting (ETS):**
    * `=FORECAST.ETS(target\_date, values, timeline, [seasonality], [data\_completion], [aggregation])`: Utilizes the **Exponential Triple Smoothing (ETS)** algorithm to create forecasts that accurately account for **seasonality** (cyclical patterns in the data).
3.  **Seasonality Identification:**
    * `=FORECAST.SEASONALITY(values, timeline)`: Automatically determines the length of the seasonal pattern in the data (e.g., 4 quarters or 12 months).
4.  **Confidence Intervals:**
    * `=FORECAST.CONFINT(target\_date, values, timeline, [confidence\_level], [seasonality], [data\_completion], [aggregation])`: Calculates the **confidence range** (upper and lower bounds) around the ETS forecast, indicating the probability (default is 95%) that the actual value will fall within that range.
5.  **Forecast Sheet Tool:**
    * A quick, visual tool (found in the **Data tab**) that automates the creation of a forecast and a chart, including the upper and lower confidence bounds.

***

## 🚀 How to Use the Files

1.  **Download:** Clone the repository or download the `Forecasting_Project.xlsx` file.
2.  **Explore Formulas:** Navigate through the different worksheets (e.g., "Linear Forecast," "Seasonal Forecast") to inspect the formulas used in the forecast columns.
3.  **Generate a New Forecast:**
    * Select the historical `Date` and `Sales` columns.
    * Go to the **Data** tab on the Excel ribbon.
    * Click the **Forecast Sheet** button to instantly generate a new, customizable forecast sheet and chart.

***

## 🛠 Prerequisites

* **Microsoft Excel:** You must have a version of Microsoft Excel (2016 or later) to use the `FORECAST.ETS` and related functions.
* **Basic Excel Skills:** Familiarity with basic functions and data manipulation in Excel.

***

