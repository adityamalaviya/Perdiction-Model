"# Perdiction-Model" 
# Machine Learning Internship Projects

## Overview

This repository contains four Machine Learning projects developed during my internship. These projects demonstrate the complete ML workflow including:

* Data Collection
* Data Preprocessings
* Feature Scaling
* Train-Test Splitting
* Model Training
* Model Evaluation
* Prediction on New Data

The projects cover both **Classification** and **Regression** problems using Scikit-Learn.

---

# Projects Included

## 1. Diabetes Prediction System

### Objective

Predict whether a patient is diabetic based on medical attributes.

### Dataset Features

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Algorithms Used

* Support Vector Machine (SVM)
* StandardScaler

### Evaluation Metric

* Accuracy Score : 0.6883116883116883

### Workflow

1. Load dataset
2. Data exploration and analysis
3. Feature scaling
4. Train-test split
5. Train SVM classifier
6. Evaluate model accuracy
7. Predict diabetes status for new patient data

---

## 2. Heart Disease Prediction System

### Objective

Predict whether a person has heart disease using medical information.

### Dataset Features

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* ECG Results
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression
* Number of Major Vessels
* Thalassemia

### Algorithms Used

* Support Vector Machine (SVM)
* StandardScaler

### Evaluation Metric

* Accuracy Score : 

### Workflow

1. Load dataset
2. Handle missing values
3. Encode categorical features
4. Feature scaling
5. Train-test split
6. Train SVM model
7. Evaluate accuracy
8. Predict heart disease for new patient data

---

## 3. House Price Prediction System

### Objective

Predict house prices based on housing features.

### Algorithms Used

* Random Forest Regressor
* StandardScaler

### Data Processing

* Outlier detection using IQR method
* Feature scaling

### Evaluation Metric

* R² Score : 0.9426430733151114

### Workflow

1. Load housing dataset
2. Remove outliers using IQR
3. Split features and target variable
4. Scale features
5. Train Random Forest model
6. Evaluate using R² Score
7. Predict house prices for new houses

---

## 4. Wine Quality Prediction System

### Objective

Predict wine quality using physicochemical properties.

### Dataset Features

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

### Algorithms Used

* Random Forest Regressor
* StandardScaler

### Data Processing

* Outlier removal using IQR method
* Feature scaling

### Evaluation Metric

* R² Score : 0.25860192464920584


### Workflow

1. Load wine quality dataset
2. Remove outliers
3. Feature scaling
4. Train-test split
5. Train Random Forest model
6. Evaluate performance
7. Predict wine quality

---

# Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Jupyter Notebook
* Google Colab

---

# Machine Learning Concepts Implemented

* Data Preprocessing
* Feature Engineering
* Feature Scaling
* Outlier Detection
* Classification
* Regression
* Support Vector Machine (SVM)
* Random Forest Regression
* Model Evaluation
* Accuracy Score
* R² Score

---

# Installation

```bash
git clone https://github.com/adityamalaviya/ml-internship-projects.git

cd ml-internship-projects

pip install pandas numpy scikit-learn matplotlib
```

---

# Run Project

```bash
python diabeticsinternship.py
python heart_disease.py
python house_price_internship.py
python wine_test.py
```

---

# Future Improvements

* Add GUI using Streamlit
* Hyperparameter Tuning
* Cross Validation
* Model Serialization using Pickle
* Deploy models using Flask/FastAPI
* Add performance visualizations

---

# Author

Aditya Malaviya

Diploma in Computer Engineering

Machine Learning Internship Projects
