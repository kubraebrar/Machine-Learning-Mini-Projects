
# 🚀 Machine Learning Mini Projects Portfolio

Welcome to my Machine Learning portfolio! This repository contains a collection of predictive models built using Python and Scikit-Learn. Each project includes data understanding, exploratory analysis, and model evaluation.

## 📂 Projects Included

### 1. Employee Salary Prediction Engine (Polynomial Regression)
* **Goal:** Predict fair salary compensations based on hierarchical position levels.
* **Algorithm:** Linear vs. Polynomial Regression (Degree 4).
* **Key Learning:** Handling non-linear growth and exponential salary jumps in C-Level positions to prevent underfitting.

### 2. Startup Profit Predictor (Multiple Linear Regression)
* **Goal:** Estimate the annual profit of a startup based on its R&D, Administration, and Marketing expenditures.
* **Algorithm:** Multiple Linear Regression with Backward Elimination.
* **Key Learning:** Dummy variable trap avoidance, P-Value significance, and feature selection (proving R&D is the only significant profit driver).

### 3. Luxury House Price Prediction (Support Vector Regression)
* **Goal:** Predict the highly irregular pricing of luxury real estate based on square meters.
* **Algorithm:** Support Vector Regression (SVR) with RBF Kernel.
* **Key Learning:** The critical importance of Feature Scaling (StandardScaler) for distance-based algorithms and managing outliers with epsilon-margins.
  
### 4. Bank Customer Purchase Predictor (K-Nearest Neighbors)
* **Goal:** Predict whether a customer will purchase a targeted bank product based on their age and estimated salary to optimize marketing campaigns.
* **Algorithm:** K-Nearest Neighbors (KNN) Classification.
* **Key Learning:** The absolute necessity of Feature Scaling for distance-based algorithms, tuning the 'K' hyperparameter to balance the bias-variance tradeoff, and visualizing 2D decision boundaries to interpret model behavior.

### 5. Breast Cancer Diagnosis System: Project Summary
* **Project Objective and Nature of the Dataset:**
The objective is to classify tumors as malignant or benign based on clinical features derived from cell nuclei (radius, area, smoothness, concavity, etc.). Health data is inherently complex; cancer cells do not always have distinct and standardized dimensions. Variables such as concavity, in particular, play a critical role in determining the nature of a tumor. However, these variables are so intertwined that they cannot be distinguished from one another using standard, linear logic (non-linearly separable).
* **Algorithmic Approach: Why Kernel SVM?:** 
Linear SVM: Attempts to classify data using a simple, linear rule (e.g., “if the area is greater than 1,000, it is cancer”). However, because cells overlap in the feature space, these rigid and linear rules are bound to misclassify critical patients on the borderline.
Kernel SVM (RBF – Kernel Trick): It allows the model to examine complex data in a mathematically high-dimensional space without increasing computational cost. Thanks to the “Kernel Trick,” the model calculates local similarities between points and generates flexible decision rules tailored to the data’s structure. This enables high learning capacity in complex medical data without consuming hardware resources.

### 5. Email Spam Detection System (Naive Bayes)
* **Goal:** Classify incoming emails as 'spam' or 'normal' (ham) using Natural Language Processing (NLP) techniques to improve inbox filtering.
* **Algorithm:** Multinomial Naive Bayes with CountVectorizer.
* **Key Learning:** Transforming raw text data into numerical frequency matrices (Bag of Words), understanding why MultinomialNB is highly efficient for discrete count data, and the business critical importance of minimizing False Positives (Type 1 Errors) in spam detection.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib, Scikit-Learn, Statsmodels
* **Environment:** Jupyter Notebook

---
