# 💰 Loan Approval Prediction using Machine Learning (SVM)

## 📌 Problem Statement
Banks receive thousands of loan applications every day.  
Approving or rejecting a loan manually can be time-consuming and error-prone ⚠️.  

This project uses **Machine Learning (Support Vector Machine - SVM)** to automatically predict whether a loan should be **Approved ✅** or **Not Approved ❌** based on applicant details such as income, credit history, education, and property area.  

---

## 🚀 Project Workflow

1. **Import Dependencies** → Pandas, NumPy, Scikit-learn, Seaborn  
2. **Data Collection** → Loan dataset (`loantrain.csv`)  
3. **Data Preprocessing**  
   - Handle missing values  
   - Label encoding of categorical values (Married, Gender, Education, etc.)  
   - Convert features into numerical format  
4. **Exploratory Data Analysis (EDA)** → Using Seaborn (`countplot`)  
5. **Train-Test Split** → Split into 90% train, 10% test  
6. **Model Training** → Support Vector Machine (Linear Kernel)  
7. **Model Evaluation** → Accuracy on training & test data  
8. **Prediction System** → User can input details and get loan approval result  

---

## 📊 Dataset Information
- Dataset: `loantrain.csv`  
- Features:  
  - Gender  
  - Married  
  - Dependents  
  - Education  
  - Self_Employed  
  - Applicant Income  
  - Coapplicant Income  
  - Loan Amount  
  - Loan Amount Term  
  - Credit History  
  - Property Area  
- Target:  
  - `0` → Loan Not Approved ❌  
  - `1` → Loan Approved ✅  

________

## Thank You
