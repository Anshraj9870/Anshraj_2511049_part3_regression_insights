# Residual Analysis

## Objective

The purpose of residual analysis is to evaluate how well the final multiple regression model predicts monthly sales. Residuals help identify stores where the model over-predicts or under-predicts sales.

---

# Residual Calculation

The predicted monthly sales were calculated using the final multiple regression equation.

### Formula

Residual = Actual Sales − Predicted Sales

* Positive Residual → Actual sales are higher than predicted (the model under-predicted).
* Negative Residual → Actual sales are lower than predicted (the model over-predicted).

---

# Top 5 Largest Positive Residuals

The records with the highest positive residuals indicate stores that performed better than expected.
| Rank |    Actual Sales      |    Predicted Sales   |       Residual        |
| ---- | -------------------: | -------------------: | --------------------: |
    1           713611.16	     2001763887	             -2001050276
    2           625514.04	     1754654493	             -1754028979
    3           787715.51	     2209624121              -2208836406
    4           799046.94	     2241408485	             -2240609438
    5           813316.71	     2281434625	             -2280621309

### Interpretation

These stores achieved higher sales than predicted by the regression model. Possible reasons include:

* Successful local promotions
* Better customer service
* Seasonal demand
* Strong store management
* Other business factors not included in the model

---

# Top 5 Largest Negative Residuals

The records with the largest negative residuals indicate stores where actual sales were lower than predicted.

| Rank |         Actual Sales |      Predicted Sales |              Residual |
| ---- | -------------------: | -------------------: | --------------------: |
| 1    |      685379.08       |      2210667962      |     -2209982583       |
| 2    |       595467.6       |      1300291667      |     -1299696199       |
| 3    |       641865.03      |      1661198251      |     -1660556386       |
| 4    |       627171.9       |      2063187922      |     -2062560750       |
| 5    |       415721.82	  |      1435815020	     |     -1435399299       |


### Interpretation

These stores generated lower sales than predicted. Possible reasons include:

* Stock shortages
* Operational issues
* Lower customer demand
* Local competition
* External factors not included in the regression model

---

# Overall Residual Analysis

The residual values include both positive and negative values, indicating that the model sometimes under-predicts and sometimes over-predicts monthly sales.

Most residuals are reasonably close to zero, suggesting that the multiple regression model provides a good overall fit for the data.

No obvious systematic pattern was observed, indicating that the model performs consistently across most observations.

---

# Business Interpretation

* Positive residuals indicate stores performing better than expected.
* Negative residuals indicate stores performing below expectations.
* Management should investigate stores with very large residuals to identify operational strengths or weaknesses.
* The residual analysis suggests that the model explains most sales variation, but some factors affecting sales are not captured in the regression model.

---

# Conclusion

The Multiple Regression model provides a reliable prediction of monthly sales. However, regression cannot capture every business factor. Residual analysis highlights stores that require further investigation and supports better business decision-making.
