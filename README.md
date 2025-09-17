# 📊 Stock Market Classification (ISLP Chapter 4 Labs)

This repository contains my practice notebooks from *An Introduction to Statistical Learning with Python (ISLP)*, Chapter 4 labs.  
The focus is on classification methods for predicting stock market movements.

---

## 📌 Topics Covered

1. Logistic Regression
   - Predicting Direction (Up/Down) using lagged returns
   - Interpreting coefficients
   - Probability outputs vs class predictions

2. Linear Discriminant Analysis (LDA)
   - Assumes groups are normally distributed with equal variance
   - Finds linear boundaries between classes

3. Quadratic Discriminant Analysis (QDA)
   - More flexible than LDA
   - Allows curved decision boundaries

4. Naive Bayes
   - Simple probabilistic classifier
   - Assumes predictor independence
   - Often works surprisingly well

---

## 📊 Dataset
We use the Smarket dataset, included in the ISLP library:
- Daily % returns for the S&P 500 (2001–2005)
- Predictors: Lag1, Lag2, ..., Lag5, Volume
- Response: Direction (Up/Down)

---

## 🚀 Methods
- Split data into training (2001–2004) and test (2005) sets
- Fit models on training set
- Evaluate on test set using confusion matrices and accuracy

---

## 🛠 Tools & Libraries
- Python (3.9+)
- pandas, numpy
- statsmodels
- scikit-learn
- matplotlib
- ISLP package

---

## 💻 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/Oxcheatcode/logistic-regression.git
   cd islp-logistic-classification
2. pip install -r requirements.txt
3.jupyter notebook


🌟 Key Learnings

Logistic regression outputs probabilities (great for classification)

LDA assumes linear separation; QDA allows non-linear boundaries

Naive Bayes is simple yet effective

Always evaluate with training vs test data to avoid overfitting

🔗 References

An Introduction to Statistical Learning with Python

[ISLP package](https://github.com/intro-stat-learning/ISLP)
