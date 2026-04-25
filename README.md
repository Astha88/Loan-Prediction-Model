# 📊 Loan Prediction Model

## 📌 Project Overview

This project predicts whether a loan application will be **approved or rejected** using a Machine Learning model.

It follows a complete **data analysis + machine learning pipeline**, including data preprocessing, visualization, model training, and prediction.

---

## 📊 Dataset Information

The dataset contains applicant details such as:

* Gender
* Married
* Dependents
* Education
* Self Employed
* Applicant Income
* Loan Amount
* Property Area
* Loan Status (Target Variable)

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing

* Handled missing values using `.dropna()`
* Converted categorical data into numerical format
* Example:

  * Loan_Status → (Y = 1, N = 0)
  * Gender → (Male = 1, Female = 0)

---

### 2️⃣ Data Visualization

* Used Seaborn for analysis:

  * Education vs Loan Status
  * Marital Status vs Loan Status

---

### 3️⃣ Feature & Target Split

* Features (X): Input variables
* Target (Y): Loan Status

---

### 4️⃣ Train-Test Split

* Training Data: 90%
* Testing Data: 10%

---

### 5️⃣ Model Training

* Algorithm Used: **Support Vector Machine (SVM)**
* Kernel: Linear

---

### 6️⃣ Model Evaluation

* Training Accuracy: XX%
* Testing Accuracy: XX%

---

### 7️⃣ Prediction System

The model can predict loan approval based on new input data.

---

## 🤖 Why SVM?

* Works well for classification problems
* Effective on small datasets
* Provides good accuracy

---

## 📂 Project Structure

Loan-Prediction-Model/
│── LoanPredictionModel.ipynb
│── dataset.csv
│── README.md

---

## 🔍 Sample Prediction

Input:

* Gender: Male
* Married: Yes
* Income: 5000

Output:

* Loan Approved ✅

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Try Random Forest & XGBoost
* Deploy using Streamlit

---

## 👩‍💻 Author

Astha Pal
