# House Price Prediction

Predicting house sale prices with regression models in Python.

## Dataset
Kaggle House Prices dataset: 1,460 houses with 81 features, such as living area, basement size, overall quality, number of bathrooms and year built.

## What I did
1. **Exploratory Data Analysis (EDA):** checked missing values, distributions and the correlation between features and price.
2. **Feature selection:** kept the features with a meaningful correlation to price and removed features that were too similar to each other.
3. **Feature engineering:** created new features from existing data, for example the age of a building from its build year.
4. **Modelling:** trained and compared several regression models.

## Models compared
Linear Regression, Ridge, Lasso, Elastic Net, K-Nearest Neighbors, Extra Tree, Gradient Boosting and XGBoost.

## Results
| Model | R² | RMSE | MAE |
|---|---|---|---|
| Gradient Boosting | 0.855 | 21,014 | 14,905 |
| Ridge | 0.851 | 21,277 | 15,724 |

Gradient Boosting gave the best result, explaining about 85% of the variation in house prices.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost, Jupyter Notebook
