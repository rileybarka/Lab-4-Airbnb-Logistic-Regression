[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rileybarka/Lab-4-Airbnb-Logistic-Regression/blob/main/notebooks/Lab4.ipynb)

# Lab 4: Logistic Regression from Scratch and Benchmarking

In this lab, we extend the modeling phase by implementing logistic regression from the ground up using Python.  
The model class includes fitting via gradient descent and prediction methods. The implementation is benchmarked against scikit-learn’s LogisticRegression class to validate performance.

---

## Dataset Used

| Dataset | Description |
|---------|-------------|
| **Airbnb Listings NYC (Dec 2021)** | Modified NYC Airbnb listings dataset used for building labeled examples and training logistic regression classifiers. |

---

## Objectives

- Build a Python class to fit logistic regression using gradient descent  
- Implement log loss, gradient, and Hessian computations  
- Load and prepare Airbnb data, defining classification labels and features  
- Train the custom logistic regression model  
- Benchmark against scikit-learn’s logistic regression implementation  
- Analyze differences in performance and computational efficiency  

---

## Methodology

- Data loading and preprocessing: feature engineering, label definition  
- Implement logistic regression class with `fit()` and `predict()` methods  
- Use gradient descent with mathematical functions (log loss, gradient, Hessian)  
- Train both custom and scikit-learn models on the same dataset  
- Evaluate and compare accuracy, convergence speed, and other metrics  

---

## Setup Instructions

### Open in Google Colab  
Click the badge above.

### 🖥️ Run Locally  
```bash
git clone https://github.com/rileybarka/Lab-4-Airbnb-Logistic-Regression.git
cd Lab-4-Airbnb-Logistic-Regression/notebooks
jupyter notebook Lab4.ipynb
