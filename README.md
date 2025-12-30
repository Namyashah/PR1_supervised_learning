![Plots Screenshot](images/Screenshot%202025-12-30%20125304.png)
# 🏠 House Price Prediction Project

## 📌 Project Overview

This project builds and evaluates multiple regression models to predict
house prices (INR) using property features.
The focus is on model comparison, bias--variance analysis, regression
assumptions, and optimization using gradient descent.

------------------------------------------------------------------------

## 📊 Dataset Snapshot (First 5 Columns)

  Column Name        Description
  ------------------ -----------------------------
  `house_id`         Unique house identifier
  `area_sqft`        Built-up area of the house
  `bedrooms`         Number of bedrooms
  `bathrooms`        Number of bathrooms
  `location_score`   Location desirability score

Target Variable: `house_price_inr`

------------------------------------------------------------------------

## 🧠 Models Implemented

-   Simple Linear Regression
-   Multiple Linear Regression
-   Polynomial Regression
-   Batch Gradient Descent (SGDRegressor)
-   Stochastic Gradient Descent
-   Mini-batch Gradient Descent

------------------------------------------------------------------------

## 📈 Model Evaluation

-   Train--Test Split
-   R² Score
-   Cross-Validation
-   Learning Curves (Bias--Variance Analysis)

------------------------------------------------------------------------

## ✅ Assumptions Validation

-   Linearity (Actual vs Predicted plots)
-   Independence of errors (Residual plots)
-   Homoscedasticity (Residuals vs Predictions)
-   Normality of residuals

------------------------------------------------------------------------

## 🏁 Conclusion

Multiple Linear Regression provided the best bias--variance
balance,
while Polynomial Regression showed overfitting tendencies.
Gradient Descent--based models performed comparably when properly tuned.

------------------------------------------------------------------------

## 🛠 Tools & Libraries

`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`

------------------------------------------------------------------------

📌 This project demonstrates end-to-end regression modeling and
evaluation techniques suitable for real-world ML problems.
