# 🛍️ Retail Sales Forecasting

This project predicts weekly sales for Walmart stores using historical data and machine learning (Random Forest). It combines store details, promotional events, economic indicators, and date features.

## 📂 Dataset
- Sales data from 45 Walmart stores
- Economic and promotional features
- Holiday indicators

## 📊 ML Approach
- Data merged and cleaned using `pandas`
- EDA with `matplotlib` and `seaborn`
- Feature engineering from dates
- Model: `RandomForestRegressor`
- Evaluation: MAE and R² Score

## 📈 Results
- MAE: 1200.55
- R² Score: 0.89

## 🔍 Insights
- Sales are higher during holidays
- Type of store and markdowns impact sales the most
