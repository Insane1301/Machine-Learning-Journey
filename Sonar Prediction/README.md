# ⛏️ Sonar Rock vs Mine Prediction 🎯

This project is a **Machine Learning model** that predicts whether an object detected by sonar is a **Rock (R)** or a **Mine (M)**.  
It uses the **Sonar Dataset** from Kaggle and applies **Logistic Regression** for classification.

---

## 📝 Problem Statement  
The challenge is to classify sonar signals received from objects under water.  
- **R (Rock):** Harmless objects like stones.  
- **M (Mine):** Dangerous objects such as metal cylinders (potentially explosive).  

Using sonar returns (60 frequency-based features), the model learns to differentiate between rocks and mines.  

---

## 🚀 Steps Performed
✔️ Imported and processed the dataset using **Pandas & NumPy**  
✔️ Explored data with **shape, describe, and groupby** functions  
✔️ Split dataset into **train & test sets** (90/10 split, stratified)  
✔️ Built a **Logistic Regression model**  
✔️ Trained and evaluated accuracy on both train and test sets  
✔️ Created a **predictive system** to classify custom input data  

---

## 📊 Model Accuracy
- ✅ Training Accuracy: ~**80-85%**  
- ✅ Testing Accuracy: ~**75-80%**  

> Dataset is also given - `sonardata.csv` (You can refer to it)


