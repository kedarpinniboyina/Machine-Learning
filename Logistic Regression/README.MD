# 📘 Logistic Regression

This repository demonstrates the concept of Logistic Regression in Machine Learning, including Binary, Multinomial, and Ordinal Logistic Regression.

---

# 🔍 What is Logistic Regression?

Logistic Regression is a supervised machine learning algorithm used for classification problems.

It predicts categorical outputs such as:

- Yes / No
- True / False
- Spam / Not Spam
- Pass / Fail

---

# 📂 Types of Logistic Regression

## 🔹 1. Binary Logistic Regression

Binary means only **two output classes**.

### Examples:
- Spam / Not Spam
- Pass / Fail
- Yes / No

### Formula

```text
P(Y=1) = 1 / (1 + e^-z)
```

```text
z = b0 + b1X
```

### Meaning

- P(Y=1) → Probability of output
- X → Input Feature
- b0 → Intercept
- b1 → Coefficient

### Working

If probability > 0.5 → Output = 1  
If probability < 0.5 → Output = 0

---

## 🔹 2. Multinomial Logistic Regression

Multinomial means **more than two output classes**.

### Examples:
- Cat / Dog / Cow
- Red / Blue / Green
- Car / Bike / Bus

### Formula

```text
P(Y=i) = e^zi / Σ e^zj
```

### Meaning

- Used when multiple categories are present
- Model predicts the probability for each class
- Highest probability becomes the final output

### Example

```text
Cat  → 0.20
Dog  → 0.70
Cow  → 0.10
```

Final Prediction → Dog

---

## 🔹 3. Ordinal Logistic Regression

Ordinal means output classes have an **order or ranking**.

### Examples:
- Low / Medium / High
- Poor / Average / Good
- 1 Star / 2 Star / 3 Star

### Important Point

Order is important here.

```text
Low < Medium < High
```

### Formula

```text
log(p / (1-p)) = b0 + b1X
```

### Working

The model predicts categories based on ranking or order.

---

# 🎯 Key Takeaway

- Binary → Two classes
- Multinomial → Multiple classes
- Ordinal → Ordered classes

Logistic Regression helps classify data into categories by predicting probabilities using mathematical formulas.

---

# ⭐ If you like this project, give it a star!
