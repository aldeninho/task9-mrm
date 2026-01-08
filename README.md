# Titanic Survival Prediction (From Scratch)

This project implements **Logistic Regression and Linear Support Vector Machine (SVM) from scratch** using **Python and NumPy** to predict passenger survival on the Titanic dataset.

## 🔍 Project Overview
- Built core ML algorithms **without using sklearn**, focusing on mathematical foundations and optimization
- Designed an end-to-end machine learning pipeline including preprocessing, dimensionality reduction, and evaluation
- Compared model performance **with and without PCA** using robust evaluation metrics

## ⚙️ Implementation Details
- **Data Preprocessing**: Missing value imputation, categorical encoding, feature standardization, and manual train–test split  
- **Models**:
  - Logistic Regression using **batch gradient descent** and sigmoid activation
  - Linear SVM using **hinge loss with L2 regularization**
- **Dimensionality Reduction**: PCA implemented from first principles using covariance matrix and eigen decomposition
- **Evaluation**: Accuracy, ROC curves, and **manual AUC computation (trapezoidal rule)**

## 📊 Results
- Logistic Regression achieved **~0.80 accuracy** and **up to 0.88 AUC**
- PCA slightly reduced accuracy while preserving most variance
- ROC curves used to compare trade-offs between models and configurations

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: NumPy, Pandas, Matplotlib  
- **Concepts**: Gradient Descent, Hinge Loss, PCA, ROC–AUC, Feature Scaling

## 📁 Dataset
- Titanic dataset (Kaggle)

## 🚀 Key Learning Outcomes
- Strong understanding of ML algorithms at a **mathematical and implementation level**
- Hands-on experience with optimization, linear algebra, and evaluation techniques
- Ability to build and analyze ML systems **from first principles**

---

⭐ If you find this project useful, feel free to star the repository!

