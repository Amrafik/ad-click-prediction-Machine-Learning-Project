# 🎯 Advertising Click Prediction – Machine Learning Project

This project builds a machine learning pipeline to predict whether a user will click on an online advertisement, using demographic and behavioral features such as age, income, daily internet usage, and time-based information.

It demonstrates a complete applied ML workflow including:
- 🔍 Exploratory Data Analysis (EDA)
- 🧹 Feature engineering
- 🤖 Model training & comparison
- 📊 Evaluation metrics
- 🔁 Cross-validation
- 📉 PCA & Clustering (unsupervised learning)

---

## 🧠 Problem Statement

> Predict whether a user will click on an advertisement using features such as age, daily internet usage, time spent on site, and timestamp breakdown (hour, day, month).

Target Variable:
- `Clicked on Ad` → 1 (Clicked) / 0 (Did not click)

---

## 📊 Dataset

- Name: `advertising.csv`
- [📎 View on GitHub](https://github.com/Amrafik/ad-click-prediction-Machine-Learning-Project/blob/main/advertising.csv)
- Includes features such as:
  - `Daily Time Spent on Site`
  - `Age`
  - `Area Income`
  - `Daily Internet Usage`
  - `Timestamp`, `City`, `Country`, `Ad Topic Line`

---

## 🚀 Models Used

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Naive Bayes**
- All models evaluated on:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix
  - Cross-Validation

---

## 📉 Unsupervised Learning

- **PCA** (Principal Component Analysis) for dimensionality reduction
- **K-Means Clustering** and **Hierarchical Clustering**
- Visualized decision boundaries using 2D PCA projections

---

## 📁 Project Structure

