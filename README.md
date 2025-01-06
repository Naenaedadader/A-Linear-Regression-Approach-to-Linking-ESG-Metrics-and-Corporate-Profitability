# A-Linear-Regression-Approach-to-Linking-ESG-Metrics-and-Corporate-Profitability
A Linear Regression Approach to Linking ESG Metrics and Corporate Profitability


**Purpose**

Analyze how companies' environmental efforts (e.g., resource utilization, emission reduction, etc.) impact their financial performance (e.g., ROA or EPS).
Use additional datasets if necessary for a more in-depth analysis.

------------
**Methodology**

**1.Apply Linear Regression Models:**
Use basic linear regression only, excluding higher-order polynomial terms (e.g., quadratic terms) or interaction terms.
Ensure each selected variable has clear economic or business logic to support its inclusion and interpretation.
**2.Variable Selection Limit:**
A maximum of 20 independent variables can be used, including environmental indicators and control variables.

------------
**Evaluation Metrics**

**1.Model Explanatory Power:** Use R² to assess how well the model explains the variance in the data; higher R² is better.
**2.Prediction Error:** Use SSE (Sum of Squared Errors) to evaluate model accuracy; lower SSE is better.

--------------
**Prediction Testing**

Randomly split the data into training and testing sets (e.g., 80% training, 20% testing). Use the testing set to evaluate the model's forecasting ability and ensure it avoids overfitting.

--------------
**DATA** combine_esgscore_10y

--------------

**CONCLUSION**

This study analyzed the relationship between companies' environmental efforts and financial performance using data from 1499 firms over 10 years (2014–2023). The findings show that resource use efficiency consistently has a positive impact on profitability, while environmental innovation and emissions scores exhibit more complex relationships, potentially involving short-term costs and long-term benefits that warrant further exploration. Among the two regression models, the inclusion of a constant term in Model 2 resulted in a lower SSE, making it the preferred model. Additionally, control variables such as EBITDA and price close positively influence profitability, while total assets show a negative association, possibly due to diminishing returns and higher costs in larger firms. However, the study’s explanatory power is limited by the selection of only six environmental factors, suggesting that future research should incorporate a broader range of variables to provide deeper insights.
