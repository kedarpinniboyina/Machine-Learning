# 🏠 House Price Prediction using Machine Learning

This project predicts house prices using multiple features such as area, bedrooms, bathrooms, and other property-related attributes using **Multiple Linear Regression**.

---

## 🚀 Features

* 📊 Multiple Linear Regression Model
* 📈 Accuracy Metrics (R², MAE, MSE)
* 📉 Visualization Graph (Actual vs Predicted)
* 💻 Built using Google Colab

---

## 🛠 Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## ▶️ How to Run

1. Open `model.ipynb` in Google Colab
2. Run all cells
3. View predictions, metrics, and graph

---

## 📌 Output

* Predict house price based on multiple features
* Graph showing actual vs predicted values

---

## ⚙️ How it Works

### 📥 Data Collection

The dataset contains multiple input features:

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Air Conditioning
* Preferred Area
* Furnishing Status

🎯 Target: **Price**

---

### 🧠 Multiple Linear Regression Concept

The model learns a relationship using:

> **Y = m₁X₁ + m₂X₂ + m₃X₃ + ... + c**

Where:

* **Y** → Predicted Price
* **X₁, X₂, X₃...** → Input features
* **m₁, m₂, m₃...** → Feature weights
* **c** → Intercept

---



### 🔍 Model Training

The model learns optimal weights by minimizing prediction error using the Mean Squared Error (MSE) function:

> **MSE = (1 / n) Σ (Y_actual − Y_predicted)²**

👉 **Goal:** Minimize the difference between actual and predicted house prices


---

### 📊 Prediction

After training, the model uses the learned equation to predict house prices for new inputs

---

### 📈 Evaluation

* **R² Score (~65%)** → Model performance
* **MAE** → Average prediction error
* **MSE** → Penalizes large errors

---

### 📉 Visualization

The scatter plot compares actual vs predicted values:

* Points near the line → good predictions
* Deviations → real-world complexity

---

## 🎯 Conclusion

This project demonstrates how multiple features influence house prices.
Due to real-world factors like location and market trends, the model achieves moderate accuracy.

---

⭐ If you like this project, give it a star!
