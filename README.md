
# Loan Default Prediction Project

## Author
**Vincent Barchok Ngochoch**  
Full-time Data Science Student | Moringa School  


## Project Overview

This project presents an end-to-end machine learning pipeline to **predict loan default risk** using historical customer data. It is designed with business impact in mind and is targeted at financial institutions seeking data-driven solutions to minimize Non-Performing Loans (NPLs).


##  Business Objective

To develop a predictive model that helps banks:
- Identify likely loan defaulters before disbursement.
- Improve risk-based pricing models.
- Support proactive recovery and early intervention strategies.


## Problem Statements

1. Can we predict whether a customer will default on a loan using historical financial and demographic data?
2. What features most influence the likelihood of loan default?
3. Which model performs better between **Logistic Regression** and **Decision Tree**?


##  Dataset Description

The dataset contains **10,000 records** with customer financial indicators.  
Key features include:
- `Employed`: Employment status (binary)
- `Bank Balance`, `Loan Amount`, `Income`, `Savings Rate`
- `Defaulted?`: Target variable (1 = Defaulted, 0 = Not Defaulted)


## Workflow Summary

1. **Data Cleaning & Exploration**
2. **Feature Engineering**
3. **Train-Test Split**
4. **Modeling** (Logistic Regression & Decision Tree)
5. **Handling Class Imbalance using SMOTE**
6. **Model Evaluation using Accuracy, Precision, Recall, F1 Score, ROC AUC**
7. **Recommendations**


##  Results Summary

- Logistic Regression had high accuracy but very low recall.
- After applying **SMOTE**, recall improved significantly for Decision Trees.
- Decision Tree outperformed in identifying actual defaulters (higher recall and F1).


## Key Takeaways

- SMOTE effectively addressed class imbalance.
- Decision Tree provided better interpretability and actionable insights.
- The model supports proactive decision-making for credit risk teams.


##  File Structure

loan_default_prediction.ipynb   # Main Jupyter Notebook

resampled_train_data.csv        # (Optional) Exported SMOTE dataset

README.ipynb                    # This file


## Contacts
 
vbarchok@gmail.com  
[LinkedIn](https://www.linkedin.com/in/vincent-ngochoch-94095b64)
