# 🏠 Housing Price Prediction using Linear Regression

> A simple machine learning project predicting housing prices using linear regression. This project includes data preprocessing, feature engineering, model training, and visualization.

## 🔍 Project Overview

This project uses the **Housing Dataset** to predict house prices based on various features such as house size, number of bedrooms, location, etc. It implements a **Linear Regression** model using popular Python libraries like `scikit-learn`, `pandas`, and `matplotlib`.

---

## 📦 Features Used

- **Data Preprocessing**: Handling missing values, normalizing/standardizing data.
- **Feature Engineering**: Extracting useful features from raw data.
- **Machine Learning**: Training a Linear Regression model.
- **Evaluation Metrics**: Using R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).
- **Visualization**: Plotting actual vs predicted values using `matplotlib`.

---

## 🧰 Technologies Used

- **Python**
- **Pandas** – For data manipulation
- **Scikit-learn (sklearn)** – For regression modeling and evaluation
- **Matplotlib** – For visualizations
- **Jupyter Notebook / Python Script**

---
##  Model Training

- The dataset was split into training (80%) and test (20%) sets.
- The model used: `LinearRegression()`
- Evaluation results:
  
  - **R² Score**: `0.2861`
  - **MAE**: `1341.5115869796873`
---

1. Clone the repository:
   ```bash
   git clone https://github.com/ShettyGaurav/LinearRegression.git
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
##  Acknowledgements

- [Housing Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- [Linear Regression Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
