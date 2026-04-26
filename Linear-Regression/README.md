# 📘 Linear Regression

This repository demonstrates the concept of **Linear Regression** in Machine Learning, including both **Simple Linear Regression** and **Multiple Linear Regression**.

---

## 🔍 What is Linear Regression?

Linear Regression is a supervised machine learning algorithm used to model the relationship between input variables and a continuous output.

---

## 📂 Project Structure

### 🔹 Simple Linear Regression

* Uses **one input feature**
* Example: *Experience → Salary*

📌 **Formula**

> **Y = mX + c**

* **Y** → Predicted Salary
* **X** → Years of Experience
* **m** → Slope (increase per year)
* **c** → Intercept (base value)

---

### 🔹 Multiple Linear Regression

* Uses **multiple input features**
* Example: *Experience + Education → Salary*

📌 **Formula**

> **Y = m₁X₁ + m₂X₂ + m₃X₃ + ... + c**

* **X₁, X₂, X₃** → Input features
* **m₁, m₂, m₃** → Weights
* **c** → Intercept

---

---

## ⚙️ How it Works

### 📊 Model Learning

The model finds the best-fit line by minimizing error:

$$
MSE = \frac{1}{n} \sum (Y_{actual} - Y_{predicted})^2
$$

---

### 📈 Prediction

After training, the model predicts output using the learned equation.

---

## 🛠 Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## ▶️ How to Use

1. Open the respective folder (Simple or Multiple)
2. Run the notebook
3. Observe predictions and graphs

---

## 🚀 Future Enhancements

* Polynomial Regression
* Model Evaluation Improvements
* UI Integration (Gradio)

---

## 🎯 Key Takeaway

> Linear Regression helps understand and predict relationships between variables using a straight-line approach.

---

⭐ If you like this project, give it a star!
