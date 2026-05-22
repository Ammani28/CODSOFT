# CODSOFT Internship Tasks 🚀

This repository contains all the data science and software engineering tasks assigned during my internship at CODSOFT.


## 🛳️ Task 1: Titanic Survival Prediction

### 📋 Project Overview
Built a predictive model that determines whether a passenger on the Titanic survived or not based on individual characteristics like Age, Gender, Ticket Class, Fare, and Family Size.

### 🛠️ Technical Implementation
* **Data Cleaning:** Implemented conditional median imputation for missing `Age` values relative to `Pclass`, handled missing values for `Embarked`, and removed high-cardinality/incomplete columns (`Cabin`, `Name`, `Ticket`).
* **Feature Engineering:** Developed a novel feature `FamilySize` combining siblings, spouses, parents, and children indicators to capture social grouping patterns.
* **Categorical Encoding:** Leveraged One-Hot Encoding (`pd.get_dummies`) for structural conversion of text fields to numeric identifiers.
* **Model Pipeline:** Trained a Robust Random Forest Classifier with an 80/20 train-test split pattern.

### 📊 Model Performance Metrics
* **Validation Accuracy:** 81.01%
* **Precision (Survived Class 1):** 82%
* **Recall (Survived Class 1):** 69%

### 📁 Directory Reference
* `Task_1_Titanic_Survival/Titanic_Prediction.ipynb`: Complete implementation notebook containing code execution, Feature Importance Plots, and Confusion Matrix analytics.
