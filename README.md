# Diabetes-prediction-using-SVM-
##  Overview

This project aims to predict whether a person has diabetes based on medical features using a Machine Learning model. It is built using the Pima Indians Diabetes dataset and demonstrates a complete ML workflow from data preprocessing to prediction.

---

##  Dataset

* Dataset used: **Pima Indians Diabetes Dataset**

* Features include:

  * Pregnancies
  * Glucose Level
  * Blood Pressure
  * Skin Thickness
  * Insulin
  * BMI
  * Diabetes Pedigree Function
  * Age

* Target variable:

  * `Outcome` (0 → No Diabetes, 1 → Diabetes)

---

##  Tech Stack

* Python 
* NumPy
* Pandas
* Scikit-learn

---

##  Approach

### 1. Data Collection & Analysis

* Loaded dataset using Pandas
* Performed basic exploration (`.head()`, `.describe()`)
* Checked class distribution

### 2. Data Preprocessing

* Separated features and labels
* Applied **StandardScaler** for feature scaling

### 3. Train-Test Split

* Split data into training and testing sets (80/20)
* Used stratified sampling for balanced classes

### 4. Model Training

* Used **Support Vector Machine (SVM)** with linear kernel
* Trained model on training dataset

### 5. Evaluation

* Evaluated using **accuracy score**
* Compared performance on training and testing data

---

##  Results

* Training Accuracy: ~ 78.664%
* Testing Accuracy: ~ 72.272%

---

##  Prediction System

* Built a predictive system that takes input features
* Outputs whether the person is diabetic or not

---

##  Learnings

* Importance of feature scaling in ML models
* Working with real-world datasets
* Understanding SVM for classification
* Building an end-to-end ML pipeline

---

##  Future Improvements

* Try different models (Logistic Regression, Random Forest)
* Hyperparameter tuning
* Add visualization (confusion matrix, ROC curve)
* Deploy using Streamlit or Flask

---

##  Acknowledgement

Utkarsh
