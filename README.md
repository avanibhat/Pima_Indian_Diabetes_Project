# 🧬 Predicting Diabetes Risk from Health Data

> A machine learning project analyzing clinical features to predict diabetes, with a special focus on women’s health indicators such as pregnancies and BMI.

---

## 📚 Table of Contents

- [🧬 Predicting Diabetes Risk from Health Data](#-predicting-diabetes-risk-from-health-data)
  - [📚 Table of Contents](#-table-of-contents)
  - [🧠 Project Overview](#-project-overview)
  - [📊 Dataset](#-dataset)
  - [🔍 EDA and Health Insights](#-eda-and-health-insights)
  - [🤖 Modeling](#-modeling)
  - [👩‍⚕️ Women’s Health Focus](#️-womens-health-focus)
  - [✅ Results](#-results)
  - [📁 Project Structure](#-project-structure)
  - [⚙️ How to Run](#️-how-to-run)

---

## 🧠 Project Overview

This project uses health data to train machine learning models that predict the likelihood of diabetes. The dataset includes several biomarkers and demographic factors, offering insight into risk profiles—particularly for women.

---

## 📊 Dataset

**Source:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

- 768 patients
- 8 clinical features
- Target: `Outcome` (1 = diabetic, 0 = non-diabetic)

---

## 🔍 EDA and Health Insights

- Visualized outcome distribution
- Explored feature distributions by diabetes status
- Identified missing or invalid data points (e.g., zeros in BMI or glucose)

---

## 🤖 Modeling

- Used Logistic Regression and Random Forest classifiers
- Evaluated with metrics like F1-score and ROC-AUC
- Feature importance analysis was done for interpretability

---

## 👩‍⚕️ Women’s Health Focus

Special attention given to women-focused metrics:
- Number of pregnancies
- BMI comparison among diabetic vs. non-diabetic women

---

## ✅ Results

- Random Forest achieved higher accuracy and recall
- Glucose, BMI, and Age were top predictors
- BMI and pregnancy count showed strong patterns in diabetic cases

---

## 📁 Project Structure

Pima_Indian_Diabetes_Project/
│
├── diabetes_prediction.ipynb       # Jupyter notebook with all code and results
├── pima-diabetes/
│   └── diabetes.csv                # Dataset file
├── README.md                       # Project overview and instructions
├── requirements.txt                # Python libraries needed to run the notebook
├── .gitignore                      # Files and folders to exclude from Git


## ⚙️ How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt