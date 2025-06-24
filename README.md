

## CodeAlpha_Car_Price_Prediction

# 🚗 Car Price Prediction using Machine Learning — CodeAlpha Internship

This project predicts the selling price of a used car based on features like brand goodwill, mileage, horsepower, and ownership history.

## 🔍 Key Features
- Extracted brand info from car names
- Outlier detection per numerical feature
- Regression modeling with both Linear & RandomForest
- EDA with heatmaps, pairplots, and boxplots
- Evaluation with RMSE and R²

## 💻 Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (Linear, Random Forest)
- Seaborn, Matplotlib

## 📈 Model Performance
- Linear R² Score: ~0.83
- Random Forest R² Score: ~0.96

## 🚫 Outlier Strategy
Custom function using IQR on each numeric feature (`Mileage`, `Horsepower`, `Present_Price`, etc.)

➡️ [GitHub Repo](https://github.com/Abre1234/CodeAlpha_Car_Price_Prediction/blob/main/Car_Price_Prediction.ipynb))



[Dataset car](https://github.com/Abre1234/CodeAlpha_Sales_Prediction/blob/main/Advertising.csv)
