# 📘 Binary Logistic Regression – Phishing URL Detection

This repository demonstrates Binary Logistic Regression using a real-time Phishing URL Detection system.

The model predicts whether a website URL is:

- Legitimate Website
- Phishing Website

---

# 🔍 What is Binary Logistic Regression?

Binary Logistic Regression is a supervised machine learning algorithm used when there are only two output classes.

### Examples

- Phishing / Legitimate
- Spam / Not Spam
- Pass / Fail
- Yes / No

---

# 📂 Project Workflow

## 🔹 Dataset

The project uses a phishing URL dataset containing real website links and phishing indicators.

### Output Labels

- legitimate → Safe Website
- phishing → Fake Website

---

# ⚙️ Feature Engineering

The model extracts important URL features such as:

- URL Length
- HTTPS Usage
- Dot Count
- Slash Count
- Hyphen Count
- Numbers in URL
- Suspicious Keywords
- Suspicious Domain Extensions

### Suspicious Keywords

```text
login
verify
secure
bank
account
update
payment
paypal
crypto
signin
```

---

# 📌 Binary Logistic Regression Formula

```text
P(Y=1) = 1 / (1 + e^-z)
```

```text
z = b0 + b1X
```

### Meaning

- P(Y=1) → Probability of phishing
- X → Input Features
- b0 → Intercept
- b1 → Coefficient

---

# 💻 Real-Time URL Prediction

The user can enter any website URL.

### Example

```text
Enter URL: https://secure-bank-login.xyz
```

### Output

```text
⚠️ Phishing Website
```

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

# 🎯 Key Takeaway

Binary Logistic Regression helps classify URLs into phishing or legitimate categories by learning patterns from website links and predicting probabilities between 0 and 1.

---

# ⭐ If you like this project, give it a star!
