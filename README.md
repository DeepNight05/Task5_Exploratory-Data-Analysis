# Titanic Survival Prediction with Machine Learning

This project is a machine learning pipeline to predict survival on the Titanic using Python. It's part of the classic **Titanic: Machine Learning from Disaster** competition by [Kaggle](https://www.kaggle.com/competitions/titanic).

---

## Dataset

The dataset can be downloaded from the official Kaggle competition page:

🔗 [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

It contains the following files:
- `train.csv` – The training dataset
- `test.csv` – The test dataset
- `gender_submission.csv` – A sample submission file

---

## Problem Statement

Given a dataset of passengers, your task is to build a model that predicts whether a passenger survived the Titanic shipwreck or not.

---

## Features Used

- `Pclass` (Ticket class)
- `Sex`
- `Age`
- `SibSp` (Number of siblings/spouses aboard)
- `Parch` (Number of parents/children aboard)
- `Fare`
- `Embarked`

---

## Workflow

1. **Data Loading**
2. **Data Cleaning** – Handling missing values and outliers
3. **Exploratory Data Analysis (EDA)** – Visualizing patterns
4. **Feature Engineering** – Encoding categorical features
5. **Model Training**
   - Logistic Regression
   - Decision Tree
   - Random Forest
6. **Evaluation** – Accuracy, precision, recall
7. **Prediction on Test Set**
8. **Submission File Generation**

---

## Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## Model Performance

| Model              | Accuracy Score |
|-------------------|----------------|
| Logistic Regression | ~80%           |
| Decision Tree       | ~78%           |
| Random Forest       | ~82%           |

> *Scores may vary slightly depending on preprocessing and feature tuning.*

---

