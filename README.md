# Loan Approval Prediction using Machine Learning


A machine learning project that predicts whether a loan application is likely to be Approved or Rejected based on applicant financial, personal, and employment information.

📊 Important Features
Credit Score – major indicator of creditworthiness
Applicant Income – repayment capacity
Coapplicant Income – additional income support
DTI Ratio – debt-to-income level
Savings – financial stability
Loan Amount – requested loan amount.
Age
Employment Status
Education Level
Marital Status
Loan Purpose
Property Area
Employer Category
⚙️ Data Preprocessing
Handled missing numerical values using Mean Imputation
Handled missing categorical values using Most Frequent Imputation
Removed Applicant_ID
Applied Label Encoding and One-Hot Encoding
Used StandardScaler for feature scaling
Performed 80/20 Train-Test Split
🔧 Feature Engineering

Created new features to capture nonlinear relationships:

DTI_Ratio_sq = DTI_Ratio²
Credit_Score_sq = Credit_Score²
🤖 Machine Learning Models
Logistic Regression
K-Nearest Neighbors (KNN)
Gaussian Naive Bayes
📈 Evaluation Metrics

Models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
🎯 Final Prediction
Applicant Data
      ↓
Preprocessing
      ↓
Feature Engineering
      ↓
ML Model
      ↓
Loan Prediction
      ↓
┌──────────────────┐
│ Loan Approved    │
│       OR         │
│ Loan Rejected    │
└──────────────────┘

Yes → Applicant has a predicted chance of loan approval.
No → Applicant is predicted to have a lower chance of loan approval.