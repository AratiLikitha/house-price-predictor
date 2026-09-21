# House Price Predictor

Predicts house sale price using Kaggle House Prices dataset with Linear Regression.

## Dataset
HousePricePrediction.csv - 2919 rows, 13 columns
Features: MSSubClass, LotArea, OverallCond, YearBuilt, YearRemodAdd, etc.
Target: SalePrice

## Steps Performed
1.  Data Loading & EDA - head(), describe(), info()
2.  Data Cleaning - Filled missing SalePrice with mean, dropped remaining nulls
3.  Train-Test Split - 80% train, 20% test
4.  Model Building - Linear Regression
5.  Feature Scaling - StandardScaler to improve performance
6.  Model Evaluation - R2 Score, MAE, RMSE, MAPE

## Model Performance
- R2 Score: 0.974
- MAE: 98629.9
- RMSE: 41138.55

## Tech Stack
Python, Pandas, NumPy, Scikit-Learn, Matplotlib, Jupyter Notebook
