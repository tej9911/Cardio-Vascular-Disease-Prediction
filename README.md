# Cardio-Vascular-Disease-Prediction
# 🫀 Cardiovascular Disease Prediction using Machine Learning

## 📌 Project Overview
Cardiovascular diseases (CVDs) are among the leading causes of mortality worldwide. Early detection and risk assessment play a crucial role in prevention and effective treatment.

This project implements a **machine learning–based predictive system** that analyzes clinical and lifestyle attributes to determine the likelihood of cardiovascular disease. Multiple supervised learning models are trained, evaluated, and compared using robust statistical and visual techniques.

---

## 🎯 Objectives
- Predict the presence of cardiovascular disease using clinical and behavioral data  
- Identify the most influential risk factors contributing to heart disease  
- Compare multiple machine learning models using standard evaluation metrics  
- Provide interpretable visual insights for healthcare decision support  

---

## 📊 Dataset Description
The dataset consists of structured health records with the following attributes:
- Age  
- Body Mass Index (BMI)  
- Systolic Blood Pressure  
- Cholesterol  
- Glucose  
- Smoking status  
- Exercise frequency  
- Stress level  
- Diabetes  
- Family history of cardiovascular disease  

**Target Variable:**
- `cvd_disease` → Binary classification  
  - `0` → No Disease  
  - `1` → Disease  

---

## 🔄 Data Preprocessing
The following preprocessing techniques were applied:
- Handling missing values using statistical imputation  
- Outlier detection and correction  
- Feature scaling and normalization  
- Encoding categorical variables into numerical format  
- Correlation analysis to remove redundant features  
- Stratified train–test split (80:20) to preserve class balance  

---

## 🧠 Machine Learning Models Used
The project implements and evaluates the following models:

- **Logistic Regression**
- **Random Forest Classifier**
- **CatBoost Classifier**

These models were chosen due to their effectiveness in handling:
- Non-linear feature relationships  
- Feature interactions  
- Healthcare datasets with mixed data types  

---

## 📈 Evaluation Metrics
Each model is evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC–AUC score  
- Confusion Matrix  

---

## 🖼️ Visualizations
The project includes the following visual analyses:
- Missing value pattern visualization  
- Feature correlation heatmap  
- Pair plot visualization  
- Confusion matrix and ROC curve (side-by-side for each model)  
- Model performance comparison charts  

These visualizations enhance model interpretability and explainability.

---

## 🏆 Results Summary
- Tree-based models outperformed linear models  
- Random Forest and CatBoost achieved strong balance between accuracy and recall  
- Key predictive features included:
  - Age  
  - Systolic Blood Pressure  
  - Cholesterol  
  - BMI  
  - Diabetes  
  - Family History  
- The final models demonstrated reliable performance suitable for early cardiovascular risk screening  

---

## 🛠️ Tools & Technologies Used
- **Programming Language:** Python  
- **Libraries & Frameworks:**
  - NumPy  
  - Pandas  
  - Matplotlib  
  - Seaborn  
  - Scikit-learn  
  - XGBoost  
  - CatBoost  
  - Statsmodels  
- **Development Environment:** Jupyter Notebook / Google Colab  

---

## 🚀 How to Run the Project
```bash
# Clone the repository
git clone https://github.com/your-username/cvd-prediction-ml.git

# Navigate to the project directory
cd cvd-prediction-ml

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
