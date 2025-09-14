🏡 House Price Prediction

This project focuses on predicting house prices using machine learning models.  
The goal was to compare simple and advanced models, evaluate their performance, and apply hyperparameter tuning for optimization.  

🔹 Workflow
- Performed EDA (checked dataset shape, null values, duplicates).  
- Split data into features and target.  
- Applied Linear Regression as a baseline.  
- Applied Random Forest for stronger performance.  
- Evaluated models using MSE, RMSE, and R².  
- Used RandomizedSearchCV to tune Random Forest parameters.  

🔹 Results
- Linear Regression → RMSE = 196,388, R² = 0.7394  
- Random Forest → RMSE = 69,664, R² = 0.9672  
- Random Forest (Tuned) → RMSE = 69,795, R² = 0.9671  

🔹 Key Insights
- Linear Regression gave a decent baseline but wasn’t very accurate.  
- Random Forest performed much better, capturing complex relationships in the data.  
- Hyperparameter tuning didn’t improve results much in this case, but it’s essential for more complex datasets.  

🔹 Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

✅ Conclusion
Random Forest turned out to be the best model for predicting house prices in this dataset, showing the power of ensemble methods in machine learning.
