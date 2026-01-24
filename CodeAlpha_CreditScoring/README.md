# 📊 Credit Scoring Model  
**CodeAlpha Machine Learning Internship – Task 1**

---

## 📌 Project Overview
This project focuses on building a **Credit Scoring / Loan Approval Prediction** model using machine learning techniques.  
The objective is to predict whether a loan will be **approved or rejected** based on an applicant’s financial and demographic details.

This project was completed as part of the **CodeAlpha Machine Learning Internship Program**.

---

## 🎯 Objective
To predict an individual’s **creditworthiness (`Loan_Status`)** using historical financial data such as:
- Income
- Loan amount
- Credit history
- Personal & demographic details

---

## 🗂 Dataset
- **Source:** Loan Approval Prediction Dataset  
- **Rows:** 614  
- **Features:** 12 input features + 1 target column  
- **Target Variable:** `Loan_Status` (Approved / Not Approved)

### 🔑 Key Features Used
- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  

---

## 🛠️ Technologies & Libraries Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Exploration
- Loaded dataset using Pandas  
- Checked shape, columns, and missing values  

### 2️⃣ Data Preprocessing
- Removed unnecessary column (`Loan_ID`)  
- Handled missing values using **mode** and **median**  
- Encoded categorical variables using `LabelEncoder`  
- Applied feature scaling using `StandardScaler`  

### 3️⃣ Model Building
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

### 4️⃣ Model Evaluation
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC Score  

---

## 📈 Model Performance

| Model               | Accuracy | F1 Score | ROC-AUC |
|--------------------|----------|----------|---------|
| Logistic Regression | 78.86%   | 85.87%   | 0.70    |
| Decision Tree       | Varies   | Varies   | Varies  |
| Random Forest       | Best     | Best     | Best    |

🔹 **Logistic Regression** achieved high recall, ensuring most eligible applicants were correctly identified.  
🔹 **Random Forest** provided the best overall performance due to ensemble learning.

---

## 📌 Conclusion
This project successfully demonstrates how **machine learning models** can be applied to **credit scoring and loan approval prediction**.

- Random Forest performed best overall  
- Logistic Regression showed excellent recall  
- Suitable for real-world banking & finance applications  

---

## 📎 Repository Contents
