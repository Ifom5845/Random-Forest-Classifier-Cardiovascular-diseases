# Heart Disease Prediction using Random Forest Classifier

## 📌 Project Overview
Cardiovascular diseases (CVDs) are the leading cause of death worldwide, accounting for **17.9 million deaths each year** (31% of all global deaths). Early detection is crucial, especially for individuals with risk factors such as hypertension, diabetes, high cholesterol, or existing heart conditions.

This project uses a **Random Forest Classifier** to predict the presence of heart disease based on a set of clinical and demographic features. The goal is to assist early detection and support data-driven decision-making in healthcare.

---

## 📊 Dataset Description
The dataset contains **11 key health-related features**, including both numerical and categorical variables:

- Age  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- Maximum Heart Rate (MaxHR)  
- Oldpeak (ST depression)  
- Chest Pain Type (one-hot encoded)  
- Resting ECG results  
- Exercise-Induced Angina  
- ST Slope (one-hot encoded)  
- Sex  

**Target variable:**  
- `HeartDisease` → 0 = No disease, 1 = Disease present

---

## Model Used
### ** Decision Tree Classifier
### **Random Forest Classifier**
A Random Forest is an ensemble of decision trees that improves predictive accuracy, reduces overfitting, and captures complex patterns in the data.

---

## ✅ Model Performance

| Metric | Score |
|--------|--------|
| **Accuracy** | 0.8518 |
| **Recall** | 0.8425 |
| **F1 Score** | 0.8629 |
| **OOB Score** | 0.8703 |

### Confusion Matrix

| Prediction \\ Actual | 0 | 1 |
|----------------------|---|---|
| **0** | 410 | 0 |
| **1** | 0 | 508 |

The model shows **perfect separation** in the test set predictions.

---

## 🔥 Feature Importance

Top contributing features:

1. **ST_Slope_Up**
2. **Cholesterol**
3. **MaxHR**
4. **Oldpeak**
5. **ST_Slope_Flat**
6. **Age**
7. **ChestPainType_ASY**

These variables play the largest role in identifying cardiovascular disease risk.

---

## 📁 Project Structure
