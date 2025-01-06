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


**DATA** combine_esgscore_10y
