# 🏥 Chronic Kidney Disease (CKD) Prediction Project

## 📌 Overview

This project focuses on predicting Chronic Kidney Disease (CKD) using machine learning techniques. The workflow includes data preprocessing, exploratory data analysis (EDA), model building, evaluation, and dashboard visualization.

The goal is to assist in early detection of CKD using clinical and laboratory features.

---

## 📊 Dataset

The dataset contains patient medical records with features such as:

* Age
* Blood Pressure
* Serum Creatinine
* Hemoglobin
* Albumin
* Specific Gravity
* Blood Glucose
* And other clinical indicators

Target variable:

* **CKD (1)** → Patient has kidney disease
* **Non-CKD (0)** → Healthy patient

---

## ⚙️ Project Workflow

### 🔹 Week 1: Data Preprocessing

* Handled missing values
* Cleaned inconsistent data
* Converted categorical values to numeric
* Saved processed dataset

---

### 🔹 Week 2: Exploratory Data Analysis (EDA)

* Analyzed distribution of CKD vs Non-CKD patients
* Visualized key biomarkers:

  * Serum Creatinine
  * Hemoglobin
  * Blood Pressure
* Generated correlation heatmap
* Identified important features

---

### 🔹 Week 3: Machine Learning Models

* Split data into training and testing sets
* Built models:

  * Logistic Regression
  * Random Forest
* Applied hyperparameter tuning
* Evaluated performance

---

### 🔹 Week 4: Evaluation & Dashboard

* Evaluated using:

  * Confusion Matrix
  * Precision
  * Recall
  * ROC-AUC Score
* Built interactive dashboard using Power BI
* Visualized:

  * Patient distribution
  * Biomarker comparisons
  * Feature importance
  * Model performance

---

## 🤖 Model Performance

The Random Forest model achieved strong performance:

* High accuracy
* High recall (important for medical diagnosis)
* ROC-AUC score close to 1

### 📌 Important Note

The model achieved perfect classification on the test dataset, correctly identifying both CKD and Non-CKD patients. This may indicate a well-separated dataset or potential overfitting.

---

## 📊 Dashboard Features

The Power BI dashboard includes:

* Total patients, CKD, and Non-CKD counts
* CKD distribution visualization
* Biomarker comparisons (Creatinine, Hemoglobin, Blood Pressure)
* Age distribution
* Feature importance
* Confusion matrix
* Interactive filter (CKD status)

---

## ⚕️ Why Recall is Important

In medical diagnosis, **Recall** is critical because:

* Missing a CKD patient (false negative) can lead to serious health risks
* Early detection is essential for treatment

---

## ⚖️ Ethical Considerations

* Patient data must remain confidential
* Model predictions should assist doctors, not replace them
* Avoid bias in healthcare decisions
* Ensure fairness across all patient groups

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the notebook:

   ```
   notebooks/data_preprocessing.ipynb
   ```
4. Open Power BI dashboard file to view results

---

## 📁 Project Structure

```
Healthcare-CKD-Prediction/
│
├── Data/
│   ├── processed_data_ckd.csv
│   └── README.md
│
├── notebooks/
│   └── data_preprocessing.ipynb
│
├── dashboard/
│   └── CKD_dashboard.pbix
│
└── README.md
```

---

## 🎯 Conclusion

This project demonstrates how machine learning can be applied to healthcare data to support early detection of Chronic Kidney Disease. The combination of data analysis, predictive modeling, and visualization provides valuable clinical insights.

---

## 👨‍💻 Author

Developed as part of an internship project.
