# Anomaly Detection and Classification for Blood Donation Dataset

This project aims to detect anomalies and classify blood donation data to predict various medical conditions such as blood donation status, hepatitis, cirrhosis, and other related health issues. The dataset includes medical records of blood donors, and the task is to classify them into different health categories and identify any potential anomalies or outliers in the data. Several machine learning techniques, including anomaly detection and classification, are employed to achieve this goal.

The project utilizes several algorithms and frameworks such as **Isolation Forest** for anomaly detection, **Decision Tree**, **XGBoost**, and a **Combined Model** for classification, and **SHAP** (SHapley Additive exPlanations) for model interpretability. Hyperparameter tuning is done for **XGBoost** using **GridSearchCV** to improve the accuracy of the models.

## Features

- **Anomaly Detection**: Uses the **Isolation Forest** algorithm to identify and isolate anomalies or outliers in the dataset.
- **Classification Models**: Implements multiple classification algorithms including **Decision Tree**, **XGBoost**, and a **Combined Model** that combines multiple models for improved prediction accuracy.
- **Hyperparameter Tuning**: **XGBoost** model undergoes **GridSearchCV** for finding the optimal parameters, which enhances the model's performance.
- **Model Evaluation**: Performance metrics used to evaluate the models include:
  - **Confusion Matrix**
  - **Classification Report** (Precision, Recall, F1 Score)
  - **ROC Curve**
  - **AUC (Area Under Curve) Score**
  - **Accuracy, Precision, Recall**
- **Model Explainability**: Utilizes **SHAP** to generate detailed visualizations of feature importance and to explain model predictions for better interpretability.

## Installation

To set up the environment and run the project locally, follow the steps below:

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/your-username/blood-donation-anomaly-detection.git
