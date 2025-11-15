# Used Car Price Prediction 🚗💰

This project uses machine learning to predict used car prices based on factors such as engine power, car age, year, mileage, and transmission type.

## 📊 Project Overview
- **Goal:** Build a predictive model to estimate used car prices.
- **Dataset:** used car prices from cars4U (approx. 7,000 records)
- **Tech stack:** Python, Pandas, Numpy, Matplotib, Seaborn, Scikit-learn, XGBoost, sklearn.preprocessing, skleaarn.metrics, GridSearchCV, XGBRegressor tuning

## ⚙️ Workflow
1. Data cleaning and feature engineering
2. Exploratory data analysis (EDA)
3. Model training and cross-validation
4. Comparison of Linear, Ridge, Lasso, Random forest and XGBoost regressors
5. Model evaluation using RMSE and R²

## 🧠 Key Results
- Linear Regression achieved ~0.91 R²
- XGBoost performed best with lowest RMSE (~0.19) and highest R² (~0.94)
- Engine Power, Year and Brand were top predictors

## 📈 Files in this Repository
- `used_car_price_prediction.ipynb` – Full notebook
- `used_cars.csv` – Dataset used for Model 


## 🗝️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook used_car_price_prediction.ipynb
