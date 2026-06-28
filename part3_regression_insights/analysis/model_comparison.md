# Model Comparison

## Overview

Three regression models were developed to analyze the factors associated with monthly sales.

- Model 1: Simple Linear Regression (Marketing Spend)
- Model 2: Simple Linear Regression (Footfall)
- Model 3: Multiple Linear Regression

---

# Model Comparison Table

| Model | Dependent Variable | Independent Variable(s) | R² | Significant Variables | Business Usefulness | Limitations |
|------|--------------------|-------------------------|------|----------------------|--------------------|-------------|
| Simple Regression 1 | Monthly Sales | Marketing Spend | 0.1679 | Marketing Spend | Shows the relationship between marketing investment and sales. | Low explanatory power because only one predictor is used. |
| Simple Regression 2 | Monthly Sales | Footfall | 0.7383 | Footfall | Strong predictor of monthly sales and useful for estimating sales based on customer traffic. | Does not consider other business factors affecting sales. |
| Multiple Regression | Monthly Sales | Marketing Spend, Footfall, Inventory Availability, Customer Rating, Region_East | 0.8132 | Marketing Spend, Footfall, Inventory Availability, Region_East | Best overall model because it explains most of the variation in monthly sales and supports business decision-making. | Regression shows association rather than causation and does not include external factors such as competition or seasonality. |

---

# Comparison of Models

## Model 1 – Marketing Spend

This model uses only Marketing Spend to predict monthly sales. The R² value of **0.1679** indicates that approximately **16.8%** of the variation in monthly sales is explained by marketing spend alone. Although the relationship is positive, the model has limited predictive ability.

---

## Model 2 – Footfall

This model uses Footfall as the only predictor. It achieved an R² value of **0.7383**, meaning that approximately **73.8%** of the variation in monthly sales is explained by customer footfall. This makes it much stronger than the Marketing Spend model.

---

## Model 3 – Multiple Regression

The Multiple Regression model combines Marketing Spend, Footfall, Inventory Availability, Customer Rating, and Region_East. It achieved the highest R² value of **0.8132**, indicating that about **81.3%** of the variation in monthly sales is explained by the selected predictors.

This model provides the best prediction accuracy and gives management a more complete understanding of the factors associated with sales.

---

# Final Model Selected

The **Multiple Regression Model** was selected because:

- It has the highest R² value (0.8132).
- It has the highest Adjusted R² (0.8102).
- It provides better prediction accuracy than the simple regression models.
- It considers multiple business factors simultaneously.
- It is more useful for management decision-making.

---

# Conclusion

Among all three models, the **Multiple Regression Model** performed the best. While Footfall was the strongest single predictor of monthly sales, combining multiple predictors significantly improved the model's explanatory power. Therefore, the Multiple Regression model is recommended for business forecasting and strategic decision-making.