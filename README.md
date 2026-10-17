# Task 6 – Explainable Machine Learning for Digital Payment Fraud Detection

## Project Overview
This project focuses on detecting fraudulent transactions using Machine Learning. It compares Logistic Regression and Random Forest models and identifies important features associated with fraud detection.

## Objective
- Detect fraudulent transactions using Machine Learning.
- Compare model performance using evaluation metrics.
- Identify important features using Random Forest feature importance.
- Understand the challenges of imbalanced datasets.

## Dataset
**Dataset:** Credit Card Fraud Detection  
**Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- Total transactions: 284,807
- Fraudulent transactions: 492
- Genuine transactions: 284,315
- Total columns: 31

*Note: This dataset contains historical European credit-card transactions. It is not specifically a UPI dataset.*

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models
1. Logistic Regression
2. Random Forest Classifier

## Results
- Logistic Regression Recall: 0.92
- Random Forest Precision: 0.96
- Random Forest Recall: 0.74
- Random Forest F1-Score: 0.84
- Random Forest PR-AUC: 0.8542

Random Forest achieved a better balance between precision and recall in this experiment, while Logistic Regression detected more fraud cases but generated more false alarms.

## Project Files
- `task6_Explainable_Fraud_Detection.ipynb` – Jupyter Notebook containing the analysis and model evaluation.
- `RabTech_Task6_Fraud_Detection_Research_Paper.pdf` – Research report and findings.

## Conclusion
This project demonstrates how Machine Learning can help detect fraudulent transactions. Further validation and testing on representative real-world payment data are required before practical deployment.

## Internship
**Organization:** Rab Tech Academy  
**Task:** Task 6 – Data Science Research Capstone & Whitepaper
