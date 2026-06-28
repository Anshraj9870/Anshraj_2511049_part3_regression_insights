# Regression-Based Business Insights & Model Interpretation

## Project Overview

This project analyzes the factors affecting monthly sales across retail stores using linear regression techniques. The objective is to identify the key business drivers of sales and provide recommendations that support better decision-making.

---

## Business Problem

The retail company's leadership team wants to understand which business factors are most strongly associated with monthly sales. Based on the analysis, management can make informed decisions regarding marketing investment, inventory planning, staffing, and regional performance.

---

## Dataset Description

The dataset contains information about retail store performance, including sales, marketing, customer traffic, inventory availability, customer ratings, and regional information.

### Dependent Variable

* Monthly Sales

### Independent Variables

* Marketing Spend
* Footfall
* Inventory Availability (%)
* Customer Rating
* Region (Dummy Variable)

---

## Data Preparation

The dataset was prepared before analysis by:

* Reviewing missing values.
* Filling missing values where appropriate.
* Keeping the original dataset unchanged.
* Creating a cleaned dataset for regression analysis.
* Creating dummy variables for the categorical Region variable.

---

## Dummy Variable Approach

The categorical variable **Region** was converted into dummy variables for regression analysis.

Dummy variable used:

* Region_East

Reference category:

* Non-East Regions (North, South, and West)

The reference category was excluded from the regression model to avoid the dummy variable trap.

---

## Regression Approach

Three regression models were developed.

### Model 1

Simple Linear Regression

Dependent Variable:

* Monthly Sales

Independent Variable:

* Marketing Spend

---

### Model 2

Simple Linear Regression

Dependent Variable:

* Monthly Sales

Independent Variable:

* Footfall

---

### Model 3

Multiple Linear Regression

Dependent Variable:

* Monthly Sales

Independent Variables:

* Marketing Spend
* Footfall
* Inventory Availability
* Customer Rating
* Region_East

---

## Model Comparison Summary

| Model                               | R²     |
| ----------------------------------- | ------ |
| Simple Regression (Marketing Spend) | 0.1679 |
| Simple Regression (Footfall)        | 0.7383 |
| Multiple Regression                 | 0.8132 |

The Multiple Regression model achieved the highest explanatory power and was selected as the final model.

---

## Final Model Selected

The Multiple Regression model was selected because it provides:

* Highest R² (0.8132)
* Highest Adjusted R² (0.8102)
* Lowest Standard Error
* Statistically significant overall model
* Better prediction accuracy than the simple regression models

---

## Business Recommendation

The analysis indicates that the strongest factors associated with monthly sales are:

* Footfall
* Marketing Spend
* Inventory Availability

Management should focus on increasing customer traffic, investing in effective marketing activities, and maintaining sufficient inventory levels. Regional performance should also be monitored to identify operational improvements.

---

## Assumptions and Limitations

* Regression measures association and does not prove causation.
* External factors such as seasonality, competition, pricing, and economic conditions were not included in the model.
* Future predictions depend on historical patterns and may change under different business conditions.

---

## Project Files

The repository includes:

* Original Dataset
* Regression Workbook
* Data Cleaning
* Dummy Variables
* Simple Regression Models
* Multiple Regression Model
* Model Comparison
* Residual Analysis
* Regression Summary
* Model Equations
* Final Recommendation
* Screenshots

---

## Screenshots Included

* Simple Regression Output
* Multiple Regression Output
* Residual Analysis
* Model Comparison

---

## Tools Used

* Microsoft Excel
* Excel Data Analysis ToolPak
* Linear Regression Analysis
