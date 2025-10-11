# 🩺 Breast Cancer Risk Prediction using Machine Learning

## 📘 Overview  
This project focuses on **predicting breast cancer risk and patient outcomes** using the **METABRIC dataset** (Molecular Taxonomy of Breast Cancer International Consortium). By leveraging machine learning techniques, this study aims to enhance early detection and improve clinical decision-making for breast cancer patients.

## 🎯 Objectives  
- Explore clinical and genetic factors influencing breast cancer survival.  
- Develop predictive models to classify patient vital status.  
- Compare model performance using different machine learning algorithms.  
- Generate interpretable, data-driven insights for better diagnosis and prognosis.

---

## 🧠 Dataset  
**Dataset Name:** METABRIC (Molecular Taxonomy of Breast Cancer International Consortium)  
**File:** `Breast Cancer METABRIC.csv`  
**Features:** 34  
**Target Variable:** `Patient vital status` (Living / Died of Disease / Died of Other Causes)

### Key Attributes
- Age of Diagnosis  
- Tumor Size  
- Mutation Count  
- Chemotherapy  
- Genetic Markers  
- Hormone Receptor Status  
- Neoplasm Histologic Grade  
- Overall Survival (Months)

---

## ⚙️ Workflow  

### 1. Data Preprocessing
- Handled missing values (mean/median/mode imputation)
- Removed duplicates  
- Converted data types  
- Encoded categorical variables (One-Hot Encoding)  
- Applied feature scaling (StandardScaler / MinMaxScaler)  

### 2. Exploratory Data Analysis (EDA)
- Distribution of patient vital status  
- Univariate & Bivariate analysis  
- Correlation heatmaps  
- Treatment distribution across cancer types  

### 3. Model Development
Implemented and compared:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

### 4. Model Evaluation
Metrics used:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

---

## 📊 Model Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|-----------|
| **Logistic Regression** | **97.00%** | 97.07% | 96.90% | **Best** |
| **SVM** | 96.90% | 97.17% | 96.90% | High |
| **Random Forest** | 96.90% | 96.80% | 96.90% | High |
| **Decision Tree** | 96.90% | 97.17% | 96.50% | High |
| **KNN** | 80.56% | 80.31% | 80.56% | Moderate |

🏆 **Best Model:** Logistic Regression (97% accuracy)

---

## 💡 Key Insights  
- Age, tumor size, and mutation count are strong predictors of cancer risk.  
- Chemotherapy and hormone therapy significantly influence survival outcomes.  
- Logistic Regression performed best with simple yet effective generalization.  

---

## ⚠️ Limitations  
- Dataset size may limit generalizability.  
- Lifestyle and environmental risk factors were not included.  
- External validation on independent datasets is needed.  

---

## 🚀 Future Enhancements  
- Integrate genomic and lifestyle data for better prediction.  
- Explore Deep Learning (ANN, CNN) for nonlinear relationships.  
- Deploy as a web-based predictive tool (Streamlit/Flask).  
- Implement explainability with SHAP or LIME for medical interpretability.  

---

## 🧩 Tools & Technologies  
- **Language:** Python 3.x  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Environment:** Jupyter Notebook  
- **Visualization:** PowerPoint, Matplotlib  
- **Dataset:** METABRIC  

---

## 👨‍💻 Author  
**R. Nitin**  
📧 Email: rnitin0604@gmail.com  
🔗 LinkedIn: [https://www.linkedin.com/nitin0604](https://www.linkedin.com/in/nitin0604/)

---

## 🩹 License  
This project is licensed under the **MIT License** — feel free to use and modify it for educational or research purposes.





