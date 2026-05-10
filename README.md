# CSVMLProject
# Employee Attrition Prediction using Machine Learning

## 📌 Overview
This project focuses on predicting employee attrition using Machine Learning techniques on the IBM HR Analytics dataset. The goal is to identify employees who are likely to leave the company so that organizations can take preventive actions to improve retention.

The project includes:
- Data preprocessing and feature engineering  
- Handling class imbalance using SMOTE  
- Training multiple machine learning models  
- Stacking ensemble model  
- Model evaluation and comparison  
- Statistical significance testing and bootstrap validation  

---

## 📂 Dataset
The dataset used is the **IBM HR Analytics Employee Attrition & Performance Dataset**.

### Target Variable:
- **Attrition**
  - Yes → Employee left
  - No → Employee stayed

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Imbalanced-learn (SMOTE)  
- Matplotlib  
- Seaborn  

---

## 🔄 Workflow

### 1. Data Preprocessing
- Cleaned dataset and removed duplicates  
- Encoded categorical variables  
- Scaled numerical features  
- Feature selection applied  

### 2. Handling Imbalanced Data
- SMOTE used to balance class distribution  

### 3. Model Training
Models used:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- Stacking Ensemble Model  

### 4. Model Evaluation
Metrics used:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC Score  
- Confusion Matrix  

### 5. Statistical Analysis
- Paired T-Test  
- Bootstrap Confidence Interval  

---

## 📊 Results

| Metric | Score |
|--------|-------|
| Accuracy | 98.05% |
| ROC-AUC | 99.77% |

### Bootstrap Confidence Interval (95%)
- Accuracy: 0.9662 – 0.9944  
- ROC-AUC: 0.9940 – 0.9997  

### Statistical Test
- T-statistic: 3.5570  
- P-value: 0.000426  

✔️ Results show statistically significant model performance.

---

## 🧠 Key Highlights
- High-performance stacking ensemble model  
- Effective handling of imbalanced dataset  
- Strong statistical validation of results  
- Robust preprocessing pipeline  

---

## 📁 Project Structure
