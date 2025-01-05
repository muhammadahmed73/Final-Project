# Final-Project

**Overview**
This repository contains the implementation of a research project aimed at predicting money laundering risks in financial transactions using machine learning models. The project leverages real-world data and advanced techniques like Random Forest, Optimized Random Forest, and Attention-based LSTM models to analyze and predict suspicious transactions effectively.

**Key Features**

Feature Importance Analysis: Identification of key features contributing to money laundering risks, such as Amount (USD), Destination Country, and Shell Companies Involved.

**Machine Learning Models:**

Random Forest and Optimized Random Forest for robust feature selection and prediction.
Attention-based LSTM for advanced sequence modeling and feature interpretability.
Permutation Importance: Enhances model explainability by quantifying the impact of individual features on predictions.
Custom Dataset: The dataset includes financial transaction details with labeled risk scores, preprocessed for machine learning tasks.

**Research Objectives:**

1. Identify the key factors contributing to money laundering risks.
2. Predict suspicious transactions across different regions using machine learning models.
3. Develop an interpretable framework for identifying high-risk transactions not reported to authorities.

**Methodology**

Data Preprocessing: Includes handling categorical variables, normalization, and feature engineering.
Model Training: Multiple machine learning algorithms were trained and evaluated on the dataset.
Model Evaluation: Performance was assessed using metrics like accuracy, precision, recall, and feature importance scores.

**Results**

Achieved high accuracy with models like Optimized Random Forest and Attention-based LSTM.
Key features identified: Amount (USD) had the highest impact, followed by Destination Country and Shell Companies Involved.
Attention-based LSTM provided additional interpretability through attention mechanisms.


**Limitations**

Limited generalizability due to reliance on a single dataset.
Absence of real-time transaction analysis.
Complex models like LSTM require further work for improved interpretability.
Future Work
Integration of real-time financial transaction data.
Incorporation of diverse datasets from multiple sources for enhanced model generalization.
Development of more interpretable and efficient deep learning models.
