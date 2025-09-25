# 🍀 Breast Cancer Detection with XGBoost & LightGBM

Built machine learning classifiers to detect breast cancer (**Benign vs Malignant**) using medical diagnostic features. 🚀 Applied EDA, preprocessing, and advanced boosting algorithms to improve accuracy and reliability.


## 📌 Project Overview
This project implements **XGBoost** and **LightGBM** classifiers to predict whether a tumor is malignant or benign based on diagnostic features.  
It strengthened my understanding of:

- Ensemble Boosting Models (XGBoost, LightGBM)  
- Feature Scaling & Preprocessing  
- Evaluation with Classification Reports  


## 🎯 Objective
To classify tumors as **Malignant (M)** or **Benign (B)** using boosting-based ML models.  


## 📂 Dataset Overview
**Features Used (sample):**
- Radius Mean, Texture Mean, Perimeter, Area, Smoothness  
- Compactness, Concavity, Symmetry, Fractal Dimension  
- Many other diagnostic measurements  

**Target:** Diagnosis (Malignant = 1, Benign = 0)  

## 🔍 Workflow Summary

1️⃣ **Exploratory Data Analysis (EDA)**  
- Visualized feature distributions with histograms, violin plots, KDE plots  
- Checked correlations & feature importance  

2️⃣ **Preprocessing & Splitting**  
- Removed irrelevant column (`Unnamed: 32`)  
- Encoded target values (M → 1, B → 0)  
- Train/Test split (80% / 20%)  

3️⃣ **Model Training**  
- Implemented **XGBoost** and **LightGBM** classifiers  
- Trained models on input features and generated predictions  

4️⃣ **Evaluation & Insights**  
- Compared performance of XGBoost vs LightGBM  
- Used **classification reports** (precision, recall, F1-score)  
- Models achieved strong accuracy in distinguishing malignant vs benign tumors  

## 🛠 Tools & Technologies Used
- Python (Jupyter Notebook)  
- pandas, numpy  
- Visualization: matplotlib, seaborn  
- ML Models: XGBoost, LightGBM (scikit-learn integration)  

## ✅ Conclusion
This project enhanced my skills in **boosting algorithms** and **medical data classification**.  
XGBoost and LightGBM proved to be highly effective in building a reliable diagnostic system for breast cancer detection.  

---
