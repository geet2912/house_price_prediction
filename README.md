# house_price_prediction
Comparing Lasso Regression and Ridge Regression models for predicting house prices.

## Notebook breakdown:
1. Understanding the Data
- Data Cleaning, Formatting
- Ordinal to Numerical data encoding
- Missing value imputation using documentation/existing information

2. Exploratory Data Analysis:
- Univariate and Bi-variate analysis on target variable (Sale Price of House)

3. Data Preparation for model building:
- Log transformation of target variable.
- Feature Engineering to generate new features
- Train-Test Split.
- Statistical imputation (on training dataset)
- Hot Encoding of nominal variables
- Robust Scaling of numerical features using median and quantile values.
- Feature Selection

4. Model Building:
- Ridge Regression & Lasso Regression model with GridSearchCV to find optimal value of alpha.
- Identify top 25 features based on beta coefficient values.
- Evaluate both the model on training and test dataset.
