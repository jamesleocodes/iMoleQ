# Diabetic Retinopathy (DR) Classifiers
This repository hosts the execution of a machine-learning methodology used for categorizing metabolomic data obtained from tears. It differentiates between patients with diabetes mellitus who have diabetic retinopathy (DR) and those without DR.

## Introduction
Diabetic retinopathy is a common complication of diabetes that affects the blood vessels in the retina. Early detection and classification of DR are crucial for timely intervention and treatment. Metabolomic data from tear samples have shown promise in providing valuable insights for DR diagnosis.

## Dataset
The dataset used in this project consists of metabolomic profiles obtained from tear samples of individuals diagnosed with DR and healthy controls. The dataset includes various metabolites and their corresponding concentrations.

## Implementation
The machine learning approach implemented in this project aims to classify tear metabolomic data into HC and DR groups. The following steps are involved:

1. Data Preprocessing: The raw metabolomic data is processed to remove noise, handle missing values, and normalize the data.

2. Feature Selection: Relevant features are selected from the dataset to reduce dimensionality and improve classification performance. Various feature selection techniques can be used, such as statistical tests, correlation analysis, or feature importance ranking.

3. Model Training: Machine learning models, such as logistic regression, support vector machines, or random forests, are trained on the preprocessed and selected features. The models learn from the data to classify tear samples into No DR or DR groups.

4. Model Evaluation: The trained models are evaluated on a separate test set to assess their performance. Metrics such as accuracy, precision, recall, and F1-score are calculated to measure the effectiveness of the classifiers.
