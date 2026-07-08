# 🌸 Iris Classification Benchmark System

## 📌 Project Overview
This project compares the most popular classification algorithms in machine learning (Logistic Regression, KNN, SVM, Naive Bayes, Tree-based Models) using a structured pipeline on the legendary Iris dataset. Our focus is not just on finding accuracy, but on establishing that delicate balance between computational cost, overfitting risk, and model interpretability.

## 🚀 Benchmark Results

| Model | Accuracy | ROC/AUC | Computational Cost | Interpretability |
| :--- | :--- | :--- | :--- | :--- |
| **Logistic Regression** | 100.0% | 1.000 | Very Low | Very High |
| **Naive Bayes** | 100.0% | 1.000 | Very Low | High |
| **Random Forest** | 100.0% | 1.000 | High | Low (Black-box) |
| **Linear SVM** | 96.6% | 0.998 | Low | Medium |

> *Note: Results were obtained after applying `test_size=0.2` and `StandardScaler`.*

## 🎯 Technical Conclusion (Why Logistic Regression?)
Although most models achieved 100% accuracy, the real winner of this project is **Logistic Regression**. Using heavy-duty models like Random Forest or RBF Kernel on this dataset—which consists of only 150 samples and is largely linearly separable—is a waste of hardware resources (Occam's Razor principle). By transparently presenting the probabilities and coefficients behind the predictions (interpretability) to botanical researchers, Logistic Regression provides the most lightweight, fastest, and most reliable industrial solution.

