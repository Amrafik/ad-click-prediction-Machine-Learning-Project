
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

```
├── advertising.csv              # Dataset (hosted on GitHub)
├── Advertising_ML_Project.ipynb # Complete Colab-compatible notebook
├── README.md                    # Project overview
```

---

## 📎 Run in Google Colab

[![Open In Colab]([[https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Amrafik/ad-click-prediction-Machine-Learning-Project/blob/main/Advertising_ML_Project.ipynb](https://colab.research.google.com/drive/1IwYbsT3HmI_h-XsRYisAePWjkSn1iLYM#scrollTo=LmZ8gvo7wEV8)](https://colab.research.google.com/drive/1k8Tk2Tw3EbBH-d7lENals_5ftLjP-h8X))

---

## 🛠 Built With

- [Python](https://www.python.org/)
- [scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Kaggle Datasets](https://www.kaggle.com/datasets)

---

## 📌 Author

**Amr Rafik**  
📍 [GitHub](https://github.com/Amrafik) | [Kaggle](https://www.kaggle.com/amrrafik)  
✉️ Passionate about machine learning, data storytelling, and applied AI.

---

## ✅ Project Status

✔️ Completed – ready to run in Colab  
📊 Useful as a template for binary classification problems  
