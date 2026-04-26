# 💼 Salary Prediction using Machine Learning

This project predicts salary based on years of experience using Linear Regression.

## 🚀 Features

* 📊 Linear Regression Model
* 📈 Accuracy (R², MAE, MSE)
* 📉 Visualization Graph
* 💻 Built in Google Colab

## 🛠 Tech Stack

* Python
* Pandas
* Scikit-learn
* Matplotlib

## ▶️ How to Run

1. Open `model.ipynb` in Google Colab
2. Run all cells
3. View predictions and graph

## 📌 Output

* Predict salary based on experience
* Graph showing relationship


## ⚙️ How it Works

1. 📥 Data Collection

The dataset contains two columns:

* **Years of Experience (X)**
* **Salary (Y)**

---

2.  Linear Regression Concept

The model learns a linear relationship using:

$$
Y = mX + c
$$

Where:

* **Y** → Predicted Salary
* **X** → Years of Experience
* **m** → Slope (salary increase per year)
* **c** → Intercept (base salary when experience is 0)

---

3.  How Model Learns (Training)

The model finds optimal values of **m** and **c** by minimizing error:

$$
MSE = \frac{1}{n} \sum (Y_{actual} - Y_{predicted})^2
$$

👉 Goal: Minimize difference between actual and predicted salary

---

4. 📊 Prediction

After training, the model uses:

$$
\hat{Y} = mX + c
$$

to predict salary for new inputs

---

5. 📈 Evaluation

* **R² Score** → Measures how well the model fits the data
* **MAE** → Average prediction error
* **MSE** → Penalizes large errors

---

6.  📉 Visualization

The regression line represents the **best-fit line** showing the relationship between experience and salary.

---

⭐ If you like this project, give it a star!
