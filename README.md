# 🫀 Heart Disease Prediction Using Machine Learning

This project aims to predict the presence of heart disease in patients based on clinical data. By using various machine learning models and proper data preprocessing techniques, this solution can assist hospitals in early diagnosis and prioritization of at-risk patients.

---

## 📌 Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess medical data (remove outliers, handle skewness)
- Apply feature engineering and encoding
- Train multiple ML models and compare their performance
- Recommend the best model for deployment in hospital systems
- Provide clinical suggestions based on model insights

---

## 🗃️ Dataset

- Total Records: `180`
- Columns: `14`
- Target Variable: `heart_disease_present`
- Key Features: `thal`, `chest_pain_type`, `oldpeak_eq_st_depression`, `exercise_induced_angina`, `age`, etc.

---

## 🧹 Data Preprocessing

- Handled outliers using IQR method
- Skewed features were identified and assessed
- One-Hot Encoding used for categorical variables
- StandardScaler / MinMaxScaler applied to numerical features
- Checked multicollinearity using correlation matrix

---

## 🤖 Models Used

| Model                | Accuracy | F1-Score (Class 1) |
|---------------------|----------|--------------------|
| SVM                 | 0.82     | 0.79               |
| Gradient Boosting   | 0.82     | 0.79               |
| Random Forest       | 0.80     | 0.77               |
| Logistic Regression | 0.76     | 0.74               |
| Decision Tree       | 0.64     | 0.58               |

✅ **Best Models:** SVM and Gradient Boosting (balanced performance)

---

## 📊 Visualizations

- Heatmaps
- Boxplots before/after outlier removal
- Confusion matrices
- Classification metrics
- Model comparison bar chart

---

## 🏥 Suggestions to Hospital

- Screen patients with abnormal `thal`, high `oldpeak`, or `exercise_induced_angina`
- Use predictive insights to prioritize critical patients
- Encourage routine stress testing and cholesterol monitoring

---



