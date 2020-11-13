# USA-House-Price-Prediction-MLR
Python Data Science Project, Used Car Price Prediction using MLR algo with 93.16% accuracy, RMSE: 91219, MAE: 73380, Mallow's_CP: 0.001, D_Watson: 1.99, No Multicollinearity, Homoscedastic Residual/Error Distribution

## Problem Statement
A real state agents want help to predict the house price for regions in the USA. He gave you the dataset to work on and you decided to use the Linear Regression Model. Create a model that will help him to estimate of what the house would sell for.

The dataset contains 6 feature columns, 1 label/target column ('Price') and 5000 rows with CSV extension. The data contains the following columns :

- Avg. Area Income’ – Avg. The income of the householder of the city house is located.

- ‘Avg. Area House Age’ – Avg. Age of Houses in the same city.

- ‘Avg. Area Number of Rooms’ – Avg. Number of Rooms for Houses in the same city.

- ‘Avg. Area Number of Bedrooms’ – Avg. Number of Bedrooms for Houses in the same city.

- ‘Area Population’ – Population of the city.

- ‘Price’ – Price that the house sold at.

- ‘Address’ – Address of the houses.

- ‘House-Category’ – Category of the houses as per price.

## Project Overview
In this Project I have unleashed the useful Data Science insights using this House Price dataset and performed the feature selection precisely to build multiple linear regression model by combining the power of best statistical rules & principles to maximise accuracy at its best. The best thing is my model is not having Multicollinearity & Heteroscedasticity problem.

## This Project is divided into 25 major steps which are as follows:
1. [Check out the Data](#data-check)
2. [Importing Libraries & setting up environment](#imp-lib)
3. [Loading dataset](#data-load)
4. [Data Cleaning & Preprocessing](#prep-clean)
5. [Shapiro for Normality test of All Numeric Columns](#shapiro-norm)
6. [Pearson & Spearman rank Correlation Test for Measures of Association](#spear-corr)
7. [Outlier Treatment/Check](#out-check)
8. [Skewness Check](#skew-check)
9. [Exploratory Data Analysis ( EDA )](#data-expo)
10. [New Feature Creation](#new-feature)
11. [Assigning Label & Features](#Labe-Feature)
12. [Features Encoding Technique](#Features-Encoding)
13. [Scaling of Numeric Features](#scale-feature)
14. [Train & Test Split](#data-split)
15. [Features P-Value & VIF Check](#p-vif)
16. [Final Implimentation of the MLR Model](#final-model)
17. [Model Evaluation](#mod-eval)
18. [Predictions from our Model](#actual-predicted)
19. [Residual Distribution of Predicted House Price](#re-dit)
20. [Amount of Error in House Price Prediction](#amt-er)
21. [Durbin Watson Auto-Correlation Test](#dur-wat)
22. [Regression Evaluation Metrics](#mod-eval)
23. [Plotting the Regression Line](#reg-plot)
24. [Heteroscedasticity Tests](#het-test)
25. [Auto-Correlation plot](#auto-plot)

## Selected Features for the Model
**1. Avg. Area Income:**

**2. Avg. Area House Age:**

**3. Avg. Area Number of Rooms:**

**4. Area Population:**

**5. HouseCategory:** (Luxuary & Standard)
