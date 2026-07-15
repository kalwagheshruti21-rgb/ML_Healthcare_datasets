# Healthcare Predictive Modeling: Diabetes & Heart Disease Analysis

An end-to-end Machine Learning project applying supervised learning algorithms to predict and analyze chronic health conditions. This repository demonstrates how regression and classification models can assist in clinical decision-making, early diagnosis, and risk assessment.

---

## 📌 Project Overview
This project leverages key clinical metrics to build three distinct machine learning models targeting two major healthcare challenges: **Diabetes** and **Heart Disease**.

1. **Linear Regression:** Predicts continuous clinical progression markers (e.g., quantitative diabetes progression or heart disease risk scores).
2. **Logistic Regression:** A binary classification model used to predict the likelihood of disease presence (e.g., heart disease risk).
3. **Decision Tree Classifier:** An interpretable, rule-based classification model to stratify patient risk and map clinical decision pathways.

---

## 📊 Dataset Descriptions

### 1. Diabetes Dataset
* **Source:** UCI Machine Learning Repository / Kaggle (Pima Indians Diabetes Dataset)
* **Target Variables:** * *Regression:* Quantitative measure of disease progression one year after baseline.
  * *Classification:* `Outcome` (1 = Diabetic, 0 = Non-diabetic).
* **Key Features:** Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age.

### 2. Heart Disease Dataset
* **Source:** UCI Heart Disease Dataset (Cleveland)
* **Target Variable:** `Target` (1 = Heart Disease present, 0 = Absent).
* **Key Features:** Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Cholesterol (chol), Maximum Heart Rate (thalach), Exercise-Induced Angina (exang).

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Visualization:** Matplotlib, Seaborn

---

## 📈 Methodology & Performance

### 1. Linear Regression (Diabetes Progression)
* **Objective:** Predict quantitative diabetes progression using clinical baselines.
* **Key Metrics:**
  * $R^2$ Score: `[Insert your R² Score, e.g., 0.52]`
  * Mean Squared Error (MSE): `[Insert your MSE]`

### 2. Logistic Regression (Heart Disease Diagnosis)
* **Objective:** Classify whether a patient has heart disease based on cardiovascular metrics.
* **Key Metrics:**
  * Accuracy: `[Insert your accuracy, e.g., 85%]`
  * ROC-AUC: `[Insert your ROC-AUC, e.g., 0.89]`
  * Precision / Recall: `[Insert metrics]`

### 3. Decision Tree Classifier (Diabetes/Heart Disease Risk Stratification)
* **Objective:** Build an interpretable flowchart to identify high-risk patients.
* **Key Metrics:**
  * Accuracy: `[Insert accuracy, e.g., 79%]`
  * Tree Depth: `[Insert max depth, e.g., 4]` (optimized to prevent overfitting)

> **Key Clinical Insight:** Feature importance analysis revealed that **Glucose** was the strongest predictor for diabetes classification, while **Chest Pain Type (cp)** and **Max Heart Rate (thalach)** were highly influential in predicting heart disease.

---

## 🚀 How to Run this Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
   cd YOUR_REPO_NAME
   
## Install dependencies:
pip install -r requirements.txt

## Run the notebooks:
Navigate to the notebooks/ directory and open the files in Jupyter Notebook or VS Code to see the step-by-step training, evaluation, and visualizations.
