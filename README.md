# Applied-Machine-Learning-Capstone-Project

# The Project: Mortality Prediction in Patients with Acute Kidney Injury (AKI)

## 🎯 Overview

This repository contains the materials for the capstone project for **DSA 8401: Applied Machine Learning*.*

The objective of this project is to **train a machine learning model capable of predicting in-hospital mortality in the Intensive Care Unit (ICU) for patients with Acute Kidney Injury (AKI)**.

---

## 📋 Project Goal & Data

### Goal
The primary goal is to develop, evaluate, and fine-tune a machine learning classification model that accurately predicts the target variable, **In-hospital mortality (IHM)**.

### Target Variable
The target variable, **IHM**, is a binary variable where a value of **'1' indicates the death of the patient in the ICU**.

### Data Source
The data for this project is a retrospective cohort of patients with AKI and is derived from the **MIMIC-III database**.

### Features
The dataset includes the following variables, which summarize the patient's clinical trajectory during their ICU stay:

| Variable | Description |
| :--- | :--- |
| **Age** | Patient's age |
| **Sex** | Patient's sex |
| **Days in ICU** | Days in ICU |
| **BP** | Blood Pressure |
| **HR** | Heart Rate |
| **Temp** | Temperature |
| **WBC** | White Blood Count |
| **PaO2** | Partial pressure of Oxygen |
| **FiO2** | Fraction inhaled of Oxygen |
| **Pot** | Potassium |
| **Bic** | Bicarbonate |
| **Na** | Sodium |
| **BUN** | Blood Ureic Nitrogen |
| **Bilirubin** | Bilirubin |
| **GCS** | Glasgow Coma Scale |
| **IHM** | In-hospital mortality (Target) |


> 🔍 The original dataset was split into:
> - **Training set**: Provided via the virtual campus for model development.
> - **Test set**: Reserved by instructors for unbiased evaluation.

---

## ⚙️ Methodology

Our approach follows a structured ML pipeline:

1. **Data Preprocessing**
   - Handling missing values
   - Outlier detection using statistical and clinical thresholds
   - Feature scaling and encoding

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis and correlation studies
   - Class imbalance assessment (survival vs. mortality)
   - Visualization of key risk factors

3. **Feature Engineering**
   - Derived metrics such as **PaO₂/FiO₂ ratio** (a marker of respiratory function)
   - Normalization and binning of continuous variables

4. **Model Training & Selection**
   - Trained multiple algorithms:
     - Logistic Regression
     - Random Forest
     - XGBoost
     - Decision Tree
     - SVM
     - Neural Networks (Keras MLP)
     - Gradient Boosting
  
5. **Hyperparameter Tuning**
   - Optimized for AUC-ROC

6. **Threshold Optimization**
   - Selected optimal probability threshold to maximize **F-measure**
   - This threshold will be applied to the reserved test set during final evaluation

---

## 💻 Implementation Environment

All code was developed and executed on **Google Colab** for reproducibility and ease of sharing.

**Final Jupyter Notebook**:  [***https://github.com/jackieMboyaAchieng/Applied-Machine-Learning-Capstone-Project/blob/main/Copy_of_AML_Capstone.ipynb***]

---


## 👥 Team Contributions

Each team member completed one unique task (no shared responsibilities):

| Member        | Task Assigned                                  |
|---------------|------------------------------------------------|
| *Cosmas O. Kungu*    | Data cleaning and missing value imputation     |
| *Jackline Mboya*    | Exploratory data analysis and visualizations   |
| *Bernard Ogol*    | Model training, tuning, and cross-validation   |
| *Straton Amodora*    | Threshold optimization and final model export  |

> ✅ These contributions will also be summarized on the final slide of our presentation.