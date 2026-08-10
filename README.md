# Hospital Readmission Risk Analysis

## Overview

This project examines factors associated with early hospital readmission among patients with diabetes. Using approximately 70,000 hospital encounters, I analyzed patient demographics, clinical characteristics, admission information, and HbA1c results to identify factors associated with readmission and evaluate the ability of statistical models to predict patient risk.

## Objective

The primary objective was to determine whether HbA1c measurements were associated with early hospital readmission and identify additional patient and hospitalization characteristics that may contribute to readmission risk.

The analysis also evaluated whether the relationship between HbA1c and readmission varied across clinical subgroups.

## Dataset

The analysis uses hospital encounter data for patients with diabetes and includes approximately 70,000 observations.

Variables examined included:

- HbA1c results
- Age
- Gender
- Race
- Admission source
- Discharge disposition
- Primary diagnosis
- Admitting specialty
- Length of hospital stay

**Outcome:**

- Early hospital readmission

## Tools & Methods

- R
- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Logistic Regression
- Interaction Analysis
- Predictive Modeling
- ROC Curve Analysis
- AUC Evaluation
- Data Visualization
- Statistical Inference

## Analysis

Patient and hospitalization characteristics were evaluated using logistic regression to identify factors associated with early readmission.

The analysis first examined the overall relationship between HbA1c and readmission while controlling for demographic and clinical characteristics. Interaction terms were then evaluated to determine whether the relationship between HbA1c and readmission differed according to primary diagnosis or admitting specialty.

Model performance was assessed using receiver operating characteristic (ROC) analysis and area under the curve (AUC).

## Key Findings

- HbA1c alone was not a statistically significant predictor of early hospital readmission.
- Significant interactions were identified between HbA1c and primary diagnosis, indicating that its relationship with readmission may vary across diagnostic groups.
- Significant interactions were also observed between HbA1c and admitting specialty.
- Longer hospital stays were associated with increased odds of early readmission.
- The final model achieved an AUC of approximately **0.62**, indicating modest discriminatory ability.
- The findings suggest that readmission risk is multifactorial and that HbA1c may provide more useful information when considered alongside other clinical characteristics rather than as an isolated predictor.

## Model Performance

![ROC Curve](images/roc_curve.png)

The ROC curve illustrates the model's ability to distinguish between patients who experienced early readmission and those who did not. The model achieved an AUC of approximately 0.62, suggesting modest predictive performance and highlighting opportunities for additional variables or alternative modeling approaches to improve risk discrimination.

## Skills Demonstrated

- Healthcare Data Analytics
- Data Cleaning & Preparation
- Logistic Regression
- Interaction Modeling
- Predictive Analytics
- Model Evaluation
- Statistical Inference
- Data Visualization
- Interpretation of Clinical Data
- Communicating Analytical Findings
