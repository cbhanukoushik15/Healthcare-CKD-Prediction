# Chronic Kidney Disease Prediction Project

## Project Overview

This project focuses on analyzing Electronic Health Records (EHR) data to predict Chronic Kidney Disease (CKD) using machine learning techniques.

---

## Week 1: Data Preprocessing

### Tasks Completed:

* Loaded CKD dataset
* Inspected dataset structure using info() and describe()
* Handled missing values using median (numerical) and mode (categorical)
* Cleaned invalid values such as '?' and removed extra spaces
* Encoded categorical variables using LabelEncoder
* Renamed column names for better readability
* Saved cleaned dataset for further analysis

---

## Data Ethics and Privacy

* The dataset used is anonymized and publicly available
* No personal or identifiable patient information is included
* No Protected Health Information (PHI) is used
* The analysis follows ethical data handling standards

---

## Clinical Rationale

* Median was used for numerical features because medical datasets often contain outliers
* Mode was used for categorical variables to preserve the most common clinical condition
* This ensures realistic and unbiased data representation

---

## Project Structure

* data/ → contains cleaned dataset
* notebooks/ → contains preprocessing notebook

---

## Outcome

A clean and structured dataset ready for exploratory data analysis and predictive modeling.

