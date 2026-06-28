Model Equations
1. Simple Regression Model 1
Dependent Variable

Monthly Sales

Independent Variable

Marketing Spend

Regression Equation

Monthly Sales = 560613.60 + (2.135377 × Marketing Spend)

Business Interpretation
 Intercept (560613.60): If marketing spend is zero, the estimated monthly sales are 560,613.60.
 Marketing Spend Coefficient (2.135377): A one-unit increase in marketing spend is associated with an average increase of about 2.14 units in monthly sales.
 
2. Simple Regression Model 2
Dependent Variable

Monthly Sales

Independent Variable

Footfall

Regression Equation

Monthly Sales = 446190.52 + (35.75162 × Footfall)

Business Interpretation
Intercept (446190.52): If footfall is zero, the estimated monthly sales are 446,190.52.
Footfall Coefficient (35.75162): Each additional customer entering the store is associated with an increase of approximately 35.75 units in monthly sales.

3. Multiple Regression Model
Dependent Variable

Monthly Sales

Independent Variables
Marketing Spend
Footfall
Inventory Availability (%)
Customer Rating
Region_East (Dummy Variable)
Regression Equation

Monthly Sales =

108811.43

(1.199885 × Marketing Spend)
(34.081407 × Footfall)
(2804.96585 × Inventory Availability)
(9719.59312 × Customer Rating)

− (15737.7842 × Region_East)

Coefficient Interpretation
Marketing Spend

The coefficient is positive. Higher marketing spend is associated with higher monthly sales.

Footfall

The coefficient is positive. Stores with more customer visits generally achieve higher monthly sales.

Inventory Availability

The coefficient is positive. Better product availability is associated with increased sales.

Customer Rating

The coefficient is positive. Higher customer ratings are associated with higher sales. If the p-value is above 0.05 in your regression output, this variable should be interpreted with caution because it may not be statistically significant.

Region_East (Dummy Variable)
The coefficient is negative (-15737.7842). Compared with the reference region, stores located in the East region are estimated to have monthly sales that are approximately 15,738 units lower, holding all other variables constant.

Dummy Variable Explanation

The categorical variable Region was converted into dummy variables for regression analysis.

Dummy Variable Used
Region_East
| Region | Region_East |
| ------ | ----------- |
| East   | 1           |
| North  | 0           |
| South  | 0           |
| West   | 0           |
Reference Category

The reference category is Non-East Regions (North, South, and West). This means the coefficient of Region_East compares East stores with the combined reference group.

Note: If your workbook actually includes separate dummy variables (for example Region_North and Region_South) with West as the omitted category, then change this section accordingly so it matches your Excel model exactly.

Final Model Selected

Multiple Regression Model

Reason for Selection

The Multiple Regression model was selected because:

It has the highest R² (0.8132), meaning it explains approximately 81.3% of the variation in monthly sales.
It has the highest Adjusted R² (0.8102), indicating a strong fit even after considering multiple predictors.
It has the lowest Standard Error (45275.47), providing more accurate predictions.
The Significance F (1.025E-111) is much lower than 0.05, showing that the overall model is statistically significant.
It combines multiple business factors, making it more useful for management decisions than the simple regression models.