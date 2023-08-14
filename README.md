# House-Price-Prediction-by-PySpark

This project focuses on predicting house prices using the House Price Prediction dataset, which comprises 506 observations and 14 features. The dataset attributes are outlined below:

1. CRIM: Per capita crime rate by town.
2. ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
3. INDUS: Proportion of non-retail business acres per town.
4. CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
5. NOX: Nitric oxides concentration (parts per 10 million).
6. RM: Average number of rooms per dwelling.
7. AGE: Proportion of owner-occupied units built before 1940.
8. DIS: Weighted distances to five Boston employment centers.
9. RAD: Index of accessibility to radial highways.
10. TAX: Property tax rate (full-value property-tax rate per $10,000).
11. PTRATIO: Pupil-teacher ratio by town.
12. B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town.
13. LSTAT: Percentage of lower status of the population.
14. MEDV: Median value of owner-occupied homes in $1000s.

# Project Implementation

In this project, I employed Principal Component Analysis (PCA) and Linear Regression models to predict house prices. The PCA technique helped in reducing the dimensionality of the dataset while retaining essential information. Linear Regression, a widely used machine learning algorithm, was then applied to build a predictive model.

# Steps Taken

1. Data Preprocessing: Handled missing values, normalized features if necessary, and split the dataset into features (X) and target (y).

2. Principal Component Analysis (PCA): Performed PCA to reduce the feature dimensionality and capture the most significant variance in the data.

3. Linear Regression Model: Implemented a Linear Regression model using PySpark's machine learning library.

4. Model Evaluation: Evaluated the model's performance using appropriate metrics such as Mean Squared Error (MSE), R-squared, and possibly cross-validation.

5. Result Interpretation: Analyzed the model results, identifying important features and understanding the impact of principal components on predictions.

