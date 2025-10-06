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

---

## 💻 Technical Details

### Development Platform
**Google Colab platform**.

### Evaluation Metrics
The final model will be evaluated using the **Area Under the ROC Curve (AUC-ROC)** and the **F-measure**.

**F-measure Threshold:** To calculate the most optimal F-measure, the team must select and provide the **probability threshold** that will be applied to the reserved data.

### Submission Requirement
The only material to be delivered is a PDF file uploaded to the virtual campus, containing the **link to the Jupyter notebook** where the final model was developed.

**Final Notebook Link:** [***https://github.com/jackieMboyaAchieng/Applied-Machine-Learning-Capstone-Project/blob/main/Copy_of_AML_Capstone.ipynb***]

---


| Team Member |
| :--- |
| **Cosmas O. Okungu**|
| **Straton Amodora** |
| **Jackline Mboya** |
| **Bernard Ogol** |
