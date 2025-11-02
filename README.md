# Diabetes Analysis
This project predicts the likelihood of diabetes in patients based on health and lifestyle data using machine learning models in Python.  
It includes data preprocessing, exploratory data analysis, handling missing values, feature engineering, and model training.

---

## Dataset

The dataset used is the [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset) from Kaggle.  

## "Note: The dataset (diabetes_prediction_dataset.csv) is not included in this repository due to its size."


**Features include:**
- `diabetes` (target variable: 0 = No, 1 = Yes)
- `blood_glucose_level`
- `HbA1c_level`
- `bmi`
- `smoking_history`
- `heart_disease`
- `hypertension`
- `age`
- `gender`



**Data Preprocessing**

Handle missing values (BMI missing values predicted using Random Forest Regressor)

Remove duplicate rows

Encode categorical features (gender, smoking_history)

Handle imbalanced classes using SMOTE

Normalize or categorize features (bmi, blood_glucose_level, HbA1c_level)

**Exploratory Data Analysis (EDA)**

Visualized BMI distribution by diabetes status

Count plots for gender, smoking history, hypertension, heart disease

Age distribution plots among diabetic patients

Combined conditions (hypertension & heart disease) for better insights

**Machine Learning Models**

LinearSVC

Random Forest Classifier

SGDClassifier

# Steps:

Encode categorical variables

Split data into training and testing sets

Apply SMOTE for class imbalance

Train models and evaluate accuracy on test data


**Results**

Models achieve high accuracy after handling imbalanced data

Predictions can be used to classify patients as diabetic or non-diabetic


## Device used:

** Dell inspiron 14 5625u 16gb ram **
