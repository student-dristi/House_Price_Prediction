# House Price Predictor using Linear Regression 🏡📊

A simple machine learning project using Linear Regression to estimate housing prices based on features from the Boston Housing dataset.

---

## 📁 Dataset  
The dataset used is the classic **Boston Housing** dataset, which contains information collected by the U.S. Census Service concerning housing in the area of Boston, Massachusetts.

---

## 🔍 Features Used  
- `rm`: Average number of rooms per dwelling  
- `zn`: Proportion of residential land zoned for large lots  
- `lstat`: Percentage of lower status population  

---

## 🎯 Target  
- `medv`: Median value of owner-occupied homes in $1000s

---

## 🧠 Model  
We use **Linear Regression** from `sklearn.linear_model` to predict house prices.

---

## 🛠️ Steps  

1. Load and clean the dataset (handle missing values)  
2. Visualize correlations using a heatmap  
3. Select important features based on correlation  
4. Split the data into training and

## 📈 Result  
The model's performance (R² Score) was approximately **0.63**, showing a moderately strong linear relationship between selected features and housing prices.

---

## 📝 Future Improvements  
- Feature engineering for better predictive power  
- Try other regression models (Ridge, Lasso, Random Forest)  
- Hyperparameter tuning  
- Use pipelines and cross-validation  

---

## 📌 Note  
This project is a beginner-friendly exploration of machine learning regression and data preprocessing. Perfect for building foundational skills in data science! 🚀
