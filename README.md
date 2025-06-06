# Breast-Cancer-Prediction Using Machine Learning
project predicts the diagnosis of breast cancer (Malignant or Benign) using key medical features such as radius, texture, perimeter, area, and more. The objective is to identify the best classification model to support early and accurate diagnosis.


---

## 📌 Project Overview

- ✅ Dataset: Breast Cancer Dataset (CSV file with 569 records and 30 features)
- 📊 Target Variable: `diagnosis` (M = Malignant, B = Benign)
- 🎯 Goal: Predict diagnosis using features like radius_mean, texture_mean, area_mean, etc.
- 📚 Evaluation Metric: Accuracy and Confusion Matrix

---

## 🔍 ML Models Used

| Model                    | Accuracy  |
|--------------------------|-----------|
| Decision Tree Classifier | 95.10%    |
| Random Forest Classifier | **97.90%** ✅ |
| Logistic Regression      | 94.40%    |

> 🔎 **Best Model:** Random Forest (Entropy, n=20)

---

## 📈 Visualizations

- Diagnosis count plot (Malignant vs. Benign)
- Feature correlation heatmap
- Confusion matrices for each model

---

## 🛠️ Technologies Used

- Python (NumPy, Pandas, Seaborn, Matplotlib)
- Scikit-learn (Classification, Preprocessing, Accuracy)
- Google Colab / Jupyter Notebook

---

