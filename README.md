<h1 align="center">🚑 AI-Based ICU Patient Risk Prediction System</h1>

<p align="center"><b>Machine Learning for Healthcare Risk Analysis</b></p>
# 🚑 AI-Based ICU Patient Risk Prediction System

## 📌 Overview

This project focuses on predicting patient risk levels (Low, Medium, High) using clinical healthcare data.
The system leverages Machine Learning techniques to assist in early risk identification and support clinical decision-making.

---

## 🎯 Objective

* Predict patient health risk levels based on medical attributes
* Convert binary disease prediction into meaningful multi-level risk categories
* Provide interpretable insights for healthcare applications

---

## 📊 Dataset

* UCI Heart Disease Dataset
* Features include:

  * Age
  * Blood Pressure
  * Cholesterol
  * Heart Rate
  * Other clinical parameters

---

## ⚙️ Approach

### 1. Data Preprocessing

* Loaded dataset and checked for missing values

### 2. Feature Engineering

* Created a new **risk level column**:

  * Low Risk
  * Medium Risk
  * High Risk

### 3. Model Building

* Used **Random Forest Classifier**
* Trained model on processed dataset

### 4. Evaluation

* Achieved ~98% accuracy
* Performed **5-fold cross-validation (~99%)**

### 5. Model Interpretation

* Analyzed **feature importance**
* Identified key clinical factors influencing predictions

---

## 📈 Results

* High prediction accuracy and consistency
* Reliable multi-level risk classification
* Interpretable insights for healthcare applications

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib

---

## 🚀 Future Improvements

* Deploy using Streamlit dashboard
* Integrate real-time patient monitoring
* Use advanced models like XGBoost

---

## 📌 Conclusion

This project demonstrates how machine learning can be applied in healthcare to assist in early risk prediction and decision support.

---

## 📁 Project Files

* `notebook.ipynb` → Full project implementation
* `model.pkl` → Trained model (optional)
