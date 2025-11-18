# 🏡 House Price Prediction using Linear Regression

A simple and clean machine learning project using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Scikit-Learn** to predict house prices based on house size.

This project demonstrates:
- Loading & cleaning data
- Visualizing data
- Training a linear regression model
- Plotting actual vs predicted values

---

## 🚀 Live Notebook (nbviewer)
🔗 View beautifully on nbviewer:  
**(Add link here after we generate it)**

---

## 🧩 Tech Stack & Libraries Used

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![NumPy](https://img.shields.io/badge/NumPy-Math%20Library-blueviolet)
![scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML%20Model-yellow)


---

## 📊 Dataset
The dataset contains two columns:

| Column       | Description                 |
|--------------|-----------------------------|
| HouseSize    | Size in square feet         |
| HousePrice   | Price of the property       |

Format: `.csv`

---

## 📈 Scatter Plot
![Scatter Plot]([scatter_plot.png](https://github.com/Priyanka-Talari/house-price-prediction-linear-regression/blob/main/analysis.PNG?raw=true))

---

## 📉 Regression Line Plot
![Regression Line](regression_line.png)

---

## 🧠 Machine Learning Model

We used **Linear Regression** from Scikit-Learn.

```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(x_train, y_train)
