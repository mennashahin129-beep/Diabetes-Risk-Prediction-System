# Diabetes-Risk-Prediction-System

This project presents a Machine Learning-based Diabetes Risk Prediction System designed to estimate the likelihood of diabetes using health and lifestyle-related features.

The dataset was preprocessed through:

Handling missing and duplicated values
Encoding categorical variables
Feature selection using correlation analysis
Outlier detection and treatment using the IQR method
Feature scaling using StandardScaler
Handling class imbalance using RandomOverSampler

Several Machine Learning models were trained and evaluated, including:

Logistic Regression
Linear SVC
Random Forest
Gradient Boosting
K-Nearest Neighbors (KNN)

Model performance was evaluated using:

Accuracy
Precision
Recall
F1-Score

The best-performing model was selected based on F1-score and Recall, since medical prediction systems require balanced and reliable classification performance rather than accuracy alone.

The final system was deployed using Gradio, allowing users to input medical and lifestyle information and receive:

Diabetes risk level
Prediction confidence
Lifestyle recommendations

This system is intended for educational and research purposes only and should not replace professional medical diagnosis.
