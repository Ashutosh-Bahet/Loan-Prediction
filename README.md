# Loan Prediction Project

## Overview
This project focuses on predicting loan approvals using machine learning techniques. The dataset contains various features related to applicants' financial and personal information. The goal is to develop a robust predictive model to classify whether a loan will be approved or not.

## Features & Techniques Used
- **Chi-Square Test**: Used for feature selection to determine the significance of categorical features.
- **Principal Component Analysis (PCA)**: Applied for dimensionality reduction to enhance model performance.
- **Classification Models**:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Decision Trees
  - XGBoost (achieved highest accuracy of 89%)
- **Data Resampling**: Used SMOTE to handle imbalanced datasets.
- **Performance Metrics**: Evaluated models using accuracy, precision, recall, and F1-score.

## Dataset
The dataset contains the following key features:
- **Applicant Income**
- **Co-Applicant Income**
- **Loan Amount**
- **Loan Term**
- **Credit History**
- **Gender, Marital Status, and other demographic details**

## Installation
To run this project locally, install the necessary dependencies using:
```sh
pip install pandas numpy scikit-learn xgboost imbalanced-learn
```

## Running the Notebook
1. Open the `Loan_Prediction.ipynb` Jupyter Notebook.
2. Execute the cells step by step to preprocess data, train models, and evaluate performance.

## Results
- XGBoost outperformed other classifiers with 89% accuracy.
- PCA improved model efficiency without significant loss in accuracy.
- SMOTE effectively handled class imbalance, improving prediction reliability.

## Future Improvements
- Fine-tuning hyperparameters further to enhance performance.
- Exploring deep learning models for improved accuracy.
- Deploying the model as a web application for real-world usability.

## Contributors
- **Ashutosh Baheti** – Data Science & Model Development

## License
This project is licensed under the MIT License. Feel free to use and modify as needed.

---

For further details, refer to the Jupyter Notebook included in this repository.
