# 🩺 Liver Disease Prediction using Machine Learning

This project predicts the likelihood of liver disease using clinical and demographic data. It applies machine learning techniques with proper data preprocessing, class balancing, model evaluation, and an **interactive user interface** for predictions.

---

## 📌 Project Overview

Liver disease is a serious health condition that benefits from early detection. This project uses the **Indian Liver Patient Dataset (ILPD)** to build a **K-Nearest Neighbors (KNN)** classifier that predicts whether a patient may have liver disease based on medical parameters.

An interactive UI built with **ipywidgets** allows users to input patient data and receive predictions with confidence scores.

---

## 🎯 Features

- Automatic dataset download from UCI repository  
- Data preprocessing with imputation and scaling  
- Class imbalance handling using **SMOTE**  
- Randomized multi-round search for optimal K value  
- KNN-based classification  
- Model evaluation using classification report  
- **Interactive prediction UI with confidence visualization**  

---

## 📊 Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/ILPD+(Indian+Liver+Patient+Dataset))  
- **Attributes:** Age, Gender, TB, DB, Alkphos, SGPT, SGOT, TP, ALB, Albumin/Globulin Ratio  
- **Target:** `1` → Liver Disease, `0` → Healthy  

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn, imbalanced-learn (SMOTE), ipywidgets  
- **Tools:** Jupyter Notebook / Google Colab, VS Code  

---

## 🔍 How It Works

1. Load and inspect dataset  
2. Encode categorical features (Gender)  
3. Handle missing values with mean imputation  
4. Scale features using StandardScaler  
5. Balance dataset with SMOTE  
6. Split data into training/testing sets  
7. Perform randomized K search for optimal neighbors  
8. Train final KNN model  
9. Evaluate model performance  
10. Predict outcomes using interactive UI  

---

## ⚠️ Important Note

GitHub **cannot render interactive widgets** (`ipywidgets`) directly.  
To use the interactive sliders and buttons:

1. **Run the notebook locally** in Jupyter Notebook or VS Code  
2. **Or open it in Google Colab** (recommended)


