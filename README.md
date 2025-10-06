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

**Final Notebook Link:** [*** ***]

---

## 🗣️ Presentation and Teamwork

### Presentation Requirements
* [cite_start]**Duration:** 10 minutes[cite: 7].
* [cite_start]**Content:** The presentation must cover the evaluated models, the methodologies implemented, the challenges faced, and the solutions adopted[cite: 8].
* [cite_start]**Crucial Note:** The **performance results of the final model should NOT be revealed** in the presentation[cite: 9].

### Team Contribution
The **last slide** of the presentation must clearly describe the tasks carried out by every team member. [cite_start]**It is not allowed to assign one task to more than one member**[cite: 64, 65].

| Team Member | Tasks Carried Out |
| :--- | :--- |
| **Member 1** | [Insert specific task] |
| **Member 2** | [Insert specific task] |
| **Member 3** | [Insert specific task] |
| **Member 4** | [Insert specific task] |

### Evaluation Breakdown
[cite_start]The project evaluation is split as follows[cite: 53]:

| Component | Weight | Details |
| :--- | :--- | :--- |
| **Presentation** | 80% | [cite_start]Evaluated on overall proposal quality, active participation, individual contributions, and ability to answer questions[cite: 53, 55, 56]. |
| **Model Validation** | 20% | [cite_start]Evaluation using the reserved dataset, simulating a realistic scenario with previously unseen data[cite: 53, 57, 11]. |
