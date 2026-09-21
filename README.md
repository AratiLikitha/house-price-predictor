# House Price Predictor

Predicts house sale price using Kaggle House Prices dataset with Linear Regression.

## Dataset
Kaggle - House Prices: Advanced Regression Techniques (2919 houses, 80 features)
Link: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
Note: Dataset not included in repo, download from Kaggle link above

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
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn (Linear Regression)
  
## How to Run
1. Download dataset from here: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
2. Place HousePricePrediction.csv / train.csv in same folder as notebook
3. Install requirements: `pip install pandas scikit-learn matplotlib seaborn`
4. Run `house_price_predictor.ipynb` in Jupyter Notebook or VS Code
   
## Author
Pati Likitha
