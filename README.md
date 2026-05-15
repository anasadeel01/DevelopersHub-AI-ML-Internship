# 🤖 AI/ML Engineering Internship – DevelopersHub Corporation

This repository contains my completed tasks for the **AI/ML Engineering Internship** at DevelopersHub Corporation.

---

## ✅ Completed Tasks

### Task 1: Exploring and Visualizing the Iris Dataset
- **Objective:** Load, inspect, and visualize the famous Iris dataset to understand data trends.
- **Dataset:** Iris Dataset (loaded via `seaborn` — no download required)
- **Models/Techniques:** Data inspection with pandas, scatter plots, histograms, box plots, pair plots
- **Key Findings:**
  - Petal length and width are the most useful features for distinguishing species
  - Setosa is clearly separable from the other two species
  - Sepal width contains some outliers

---

### Task 3: Heart Disease Prediction
- **Objective:** Predict whether a patient is at risk of heart disease using health data.
- **Dataset:** Heart Disease UCI Dataset (loaded via public URL)
- **Models Applied:** Logistic Regression, Decision Tree Classifier
- **Key Results:**
  - Logistic Regression achieved ~85% accuracy with AUC > 0.90
  - Top predictive features: chest pain type, max heart rate, thalassemia, ST depression
  - ROC curve and confusion matrix used for evaluation

---

### Task 6: House Price Prediction
- **Objective:** Predict median house prices using property and demographic features.
- **Dataset:** California Housing Dataset (built into `scikit-learn`)
- **Models Applied:** Linear Regression, Gradient Boosting Regressor
- **Key Results:**
  - Gradient Boosting outperformed Linear Regression significantly
  - Median Income (MedInc) was the most important predictor
  - Evaluation metrics: MAE, RMSE, R² score

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook / Google Colab

---

## 📁 Repository Structure

```
├── TASK 01 - Iris Visualization.ipynb
├── TASK 03 - Heart Disease Prediction.ipynb
├── TASK 06 - House Price Prediction.ipynb
└── README.md
```

---

## 🚀 How to Run

1. Open any `.ipynb` file in [Google Colab](https://colab.research.google.com) or Jupyter Notebook
2. Run all cells from top to bottom (Runtime → Run All in Colab)
3. No extra dataset downloads needed — all datasets load automatically!

---

*Internship by DevelopersHub Corporation*
