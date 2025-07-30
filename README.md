# Liver Patient Classification

This project was developed as part of a machine learning competition for a university course. The task was hosted on the Kaggle InClass platform, where teams aimed to build the most accurate classifier for detecting liver disease based on patients' clinical and demographic features.

The competition used macro-averaged F1-score as the main evaluation metric, with special emphasis on handling class imbalance to build robust and generalizable models. 

## Introduction

Liver disease is increasing globally due to factors like environmental toxins, ultra-processed food, alcohol, and other drugs. Early detection is key to improve diagnostic efficiency. 

This project aims to build a classification model that predicts whether a patient is healthy (label = 1) or has liver disease (label = 0) using ten clinical and demographic features. The solution applies machine learning techniques, including an initial exploratory data analysis, feature engineering, classification algorithms, and ensemble methods. 

## Dataset Description

The dataset was sourced form the UCI Machine Learning Repository, originally containing 583 records (416 liver patients, 167 healthy individuals). After preprocessing to remove missing values and encode categorical variables, the final dataset includes:
- **Training set**: 
    - `train_features_ILDS.csv`: 463 × 10 matrix (patients × features)
    - `train_labels_ILDS.csv`: 463 × 1 label vector
- **Test set**: 
    - `test_data_ILDS.csv`: 116 × 10 matrix (no labels provided)
- **Features**: 
    - Age: Age of the patient 
    - Female: Gender of the patient (1 if Female, 0 if Male) 
    - TB: Total Bilirubin 
    - DB: Direct Bilirubin 
    - Alkphos: Alkaline Phosphotase 
    - Sgpt: Alamine Aminotransferase 
    - Sgot: Aspartate Aminotransferase 
    - TP: Total Protiens 
    - ALB: Albumin 
    - A/R: Albumin and Globulin Ratio 

## Methodology and Contents

A detailed explanation of the methodology, including data exploration, preprocessing, feature transformation, model selection, hyperparameter tuning, and evaluation, can be found in the final project report. 

Specifically, it covers:
- **Feature Analysis**: Exploratory data analysis, outlier treatment, scaling and transformations among other preprocessing steps.
- **Classification Methods**: Description of all models used, including baseline classifiers and ensemble techniques like Random Forest, AdaBoost, Gradient Boosting, and model stacking.
- **Evaluation Metrics**: F1-score, precision, recall, accuracy, and their relevance to the task.
- **Experiments**: Overview of each preprocessing pipeline, cross-validation strategy, and hyperparameter optimization.
- **Results and Discussion**: Performance comparison of all models, both locally and on the Kaggle leaderboard.
- **Conclusions**: Summary of model effectiveness and suggestions for future work. 

For full details, refer to the `LiverPatientClassification_Report.pdf`, and to reproduce the workflow, check the full `LiverPatientClassification_Script.ipynb`.

## Authors

The project was developed as part of a Machine Learning I course assignment at the Universitat Politècnica de Catalunya (UPC) by:
- Nicolás Jiménez Muñoz
- Aina Vila Arbusà




