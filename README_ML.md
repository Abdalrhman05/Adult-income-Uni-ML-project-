# Adult Income Prediction

A university team project where we built and compared multiple machine learning models to predict whether a person earns more than $50K a year based on demographic data.

---

## About the Project

We used the [Adult Census Income dataset](https://archive.ics.uci.edu/dataset/2/adult) from the UCI Machine Learning Repository — around 48,000 records with features like age, education, occupation, and hours worked per week. The goal was to test different classifiers and see which one performs best on this type of problem.

---

## What We Did

- Cleaned the data: handled missing values (stored as '?'), removed duplicates, and encoded categorical features
- Applied SMOTE to deal with the class imbalance between income groups
- Ran EDA to explore patterns across age, gender, education, and capital gain
- Trained and compared 7 different models

---

## Models & Results

| Model | Accuracy | F1-Score |
|---|---|---|
| **Voting Classifier** ✅ | 85.56% | 0.72 |
| XGBoost | 85.43% | 0.73 |
| Random Forest | 84.65% | 0.69 |
| SVM | 79.59% | 0.68 |
| Gaussian NB | 78.80% | 0.43 |
| KNN | 78.44% | 0.64 |
| Logistic Regression | 76.75% | 0.63 |

The Voting Classifier (Random Forest + XGBoost) came out on top. Ensemble methods clearly worked better than individual models here.

---

## How to Run

```bash
pip install pandas numpy scikit-learn imbalanced-learn xgboost lightgbm catboost matplotlib seaborn
jupyter notebook Machine_Learning_Project.ipynb
```

---

## Team

- Abdalrhman Jehad
- Hazem Alalfi
- Zaid Khrisat

📅 January 2026 — University ML Project
