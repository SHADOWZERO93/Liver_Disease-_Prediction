# 🩺 Liver Disease Prediction using Machine Learning

This project predicts the likelihood of liver disease using clinical and demographic data. It applies machine learning techniques with proper data preprocessing, class balancing, model evaluation, and an interactive user interface for predictions.

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
- Interactive prediction UI with confidence visualization  

---

## 📊 Dataset

- **Source:** UCI Machine Learning Repository  
- **Dataset:** Indian Liver Patient Dataset (ILPD)

### Attributes:
- Age  
- Gender  
- Total Bilirubin (TB)  
- Direct Bilirubin (DB)  
- Alkaline Phosphotase  
- Alanine Aminotransferase (SGPT)  
- Aspartate Aminotransferase (SGOT)  
- Total Proteins (TP)  
- Albumin (ALB)  
- Albumin/Globulin Ratio  

**Target Variable:**  
- `1` → Liver Disease  
- `0` → Healthy  

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Libraries:**
  - Pandas, NumPy
  - Matplotlib
  - Scikit-learn
  - imbalanced-learn (SMOTE)
  - ipywidgets
- **Tools:** Jupyter Notebook / Google Colab, VS Code  

---

## 🔍 Methodology

1. Load and inspect dataset  
2. Encode categorical features (Gender)  
3. Handle missing values using mean imputation  
4. Scale features using StandardScaler  
5. Balance dataset using SMOTE  
6. Split data into training and testing sets  
7. Perform randomized K search for optimal neighbors  
8. Train final KNN model  
9. Evaluate model performance  
10. Predict outcomes using interactive UI  

---

## 🤖 Model Used

- **K-Nearest Neighbors (KNN)**
- Randomized search for best `K`
- Probability-based prediction confidence

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  
- Classification Report  

---

## 🖥️ Interactive Prediction Interface

The project includes an interactive UI where users can:
- Input patient health parameters  
- Get disease prediction (Healthy / Liver Disease)  
- View prediction confidence  
- Compare values with normal medical ranges  
- Visualize probability distribution  

---
## 🚀 How to Run the Project
⚠️ Note: This project uses ipywidgets for interactivity.
GitHub does not support rendering interactive widgets.
Please run the notebook locally or on Google Colab to use the UI.

