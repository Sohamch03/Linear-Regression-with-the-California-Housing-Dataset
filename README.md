# Linear-Regression-with-the-California-Housing-Dataset
# 🏠 California Housing Price Prediction using Linear Regression

This project demonstrates a simple linear regression model using the [California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html). The goal is to predict **Median House Value** based on **Median Income** of households.

---

## 📌 Objective

To explore the relationship between income levels and housing prices in California using a machine learning model, and visualize the results.

---

## 🔧 Tools & Libraries Used

- Python
- pandas
- matplotlib
- seaborn
- scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

We start by visualizing the relationship between `MedInc` (Median Income) and `MedHouseVal` (Median House Value):

![Scatter Plot](images/medinc_vs_houseval.png)

---

## 🧠 Model: Linear Regression

We trained a **Linear Regression** model using:
- Feature: `MedInc`
- Target: `MedHouseVal`

### 📉 Model Performance:

- **Mean Squared Error (MSE)**: *e.g., 0.52*
- **R² Score**: *e.g., 0.47*

---

## 🔍 Prediction Example:

For a new household with a **Median Income of $60,000**:
