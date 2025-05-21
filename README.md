# 🏘️ Boston Housing Price Prediction with Linear Regression

In this project, I used the **Linear Regression** model to predict the prices of houses in the city of Boston. I applied data preprocessing, log transformations, and outlier analysis to improve the model's performance.

---

## 📊 Dataset Used

- **Boston Housing Dataset** (via scikit-learn)
- Features: Crime rate, number of rooms, proximity to the river, age, tax rate, etc.
- Target: MEDV (Median House Value – in $1000)

---

## 🧪 Steps Applied

- Identifying and cleaning the data
- Outlier analysis (CRIM, LSTAT)
- Correcting skewed distributions with **Log transformations**
- Model setup (LinearRegression – scikit-learn)
- Performance evaluation: R², MSE, RMSE

---
## 📈 Results

- **R² Score**: `0.723`
- **MSE**: `20.33`
- **RMSE**: `20.33`
- Model performance improved by **10%+** compared to the previous time thanks to log transformations.

---

## 🛠️ Technologies Used

- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn

---
