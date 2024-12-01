# Efficient Automated Disease Diagnosis

This repository contains the documentation and resources for the **Efficient Automated Disease Diagnosis** project, completed as a major project during the academic year 2021-22 at the Department of Electronics and Telecommunication Engineering, MPSTME, Shirpur Campus.

## Project Overview
The project focuses on building a system that predicts diseases based on user-provided information and medical datasets. It aims to assist in the early diagnosis of diseases like:

- Breast Cancer
- Heart Disease
- Liver Disease
- Kidney Disease
- Diabetes

### Key Objectives
1. Predict diseases accurately based on user input.
2. Provide actionable advice for users to seek medical help if necessary.
3. Contribute to early-stage disease detection to improve healthcare outcomes.

## Dataset Details
The project uses publicly available datasets for disease prediction:

### 1. Breast Cancer Dataset
- **Attributes**: 32
- **Instances**: 569
- **Target**: Diagnosis (Malignant/Benign)

### 2. Liver Disease Dataset
- **Attributes**: 11
- **Instances**: 583

### 3. Heart Disease Dataset
- **Attributes**: 14
- **Instances**: 303
- **Target**: Presence of Heart Disease (Yes/No)

### 4. Chronic Kidney Disease Dataset
- **Attributes**: 26
- **Instances**: 400
- **Target**: Classification (Yes/No)

### 5. Pima Indians Diabetes Dataset
- **Attributes**: 9
- **Instances**: 768

## Methodology
The project leverages the **Random Forest Classifier**, a supervised machine learning algorithm, for disease prediction.

### Features of Random Forest:
- Handles missing/null values effectively.
- Provides high stability and accuracy (70-95% in our implementation).
- Mitigates overfitting through majority voting.

#### Hyperparameters:
- `n_estimators`: Number of trees in the forest.
- `max_features`: Maximum features considered for splitting.
- `min_samples_leaf`: Minimum samples required at a leaf node.

## Results
The project achieves disease prediction accuracy within the range of **70-95%**, demonstrating its potential as an early diagnostic tool in healthcare.

## Future Work
- Improve the user interface for better interaction.
- Add a user authentication system.
- Deploy the application on a cloud platform for real-time accessibility.
- Extend functionality to support COVID-19 data.

## Project Guide
- **Prof. Pankaj Gulhane**

## Team Members
- **Apurv Panbude** (C220)
- **Prashant Pandey** (C221)
- **Yash Agarwal** (C245)

## Documentation
The complete project report is available as a PDF file: [Efficient Automated Disease Diagnosis Report](./project_report.pdf)

## References
1. Naresh Kumar et al., "Efficient Automated Disease Diagnosis Using Machine Learning Models" (2021).
2. Jian Ping LI et al., "Heart Disease Identification Method Using Machine Learning Classification in E-Healthcare" (2020).
3. Md. Kamrul Hasan et al., "Diabetes Prediction Using Ensembling of Different Machine Learning Classifiers" (2020).
4. Jiomgming Qin et al., "A Machine Learning Methodology for Diagnosing Chronic Kidney Diseases" (2019).
5. Senthilkumar Mohan et al., "Effective Heart Disease Prediction Using Hybrid Machine Learning Techniques" (2019).
