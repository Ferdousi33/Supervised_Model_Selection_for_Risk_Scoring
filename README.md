# Supervised_Model_Selection_for_Risk_Scoring

## Overview
This project applies supervised machine learning techniques to predict risk-scores from clinical features. It compares multiple models, points out contributing features, calculates risk score and provides visualization for performance and interpretability of the model.

## Methods

**Models used :** Logistic Regression, K-Neighbors, Decision Tree and Random Forest. Logistic Regression shows the best classification performance.[Models](images/model_table.png)

**Evaluation metrics :** Accuracy, Precision, Recall, F1-score and Confusion Matrix.

**Feature Engineering :** An interecting term (age*cholesterol) and three age groups were created to help the model learn patterns better and improve prediction performance.

**Feature Importance :** Although Logistics Regression has higher accuracy, Random Forest was used to compute [feature importance](images/importance_table.png) as it handles nonlinear relationships better among features. ST depression, major vessels, thalassemia type, maximum heart rate, and chest pain are the most important factors affecting risl scores. 

**Risk Score :** [Risk scores](images/risk_score__table.png) were categorized into low, medium and high scores. A [summary table](images/risk_summary_table.png) is also provided.

## Outputs and plots

**[Confusion Matrix](images/confusion_matrices.png) :** Shows the number of patients correctly or incorrectly classified by the model
**[Feature Importance](images/feature_importance.png) :** Underscores the top features contributing most to heart disease prediction 
**Risk Score Table :** Summarizes predicted risk scores that is categorized into low, medium and high risk levels

Visual outputs are in the images folder and dataset used for the project is in dataset folder.




