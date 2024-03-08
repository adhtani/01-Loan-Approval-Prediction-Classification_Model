# Loan Approval Prediction - Classification Model
   
**Introduction**  
  
Dream Housing Finance company is a growing company that provides Home loans in all over US Areas. They first check the eligibility of the customers before customers apply for the application. The company is interested in automating the pre-approval eligibility process by evaluating the customer's data provided by them on the application. This is important, as this provides the customer their likelihood of getting approved before they apply for the loan. The data is provided by the company to determine the eligibility of the customer so they can target these customers. There are many factors that can determine the eligibility of the customer, such as education level, Income, Credit History, etc.

**Business Objective:**
Predict which customer is pre-approved for home loan based on their background information.

**Data Science Problem:**

Predict the liklihood of customer getting approved or not approved.
  
**Data**  
   
Data Source: Loan Eligibility Data from [kaggle.com](https://www.kaggle.com/vikasukani/loan-eligible-dataset?select=loan-train.csv).  
Data variables in the file are: Key Name Description   
Gender - Male/ Female  
Married - Applicant married (Y/N)  
Dependents - Number of dependents Education - Applicant Education (Graduate/ Under Graduate)  
Self_Employed - Self-employed (Y/N)  
ApplicantIncome - Applicant income  
CoapplicantIncome - Coapplicant income  
LoanAmount - Loan amount in thousands  
Loan_Amount_Term - Term of a loan in months  
Credit_History - credit history meets guidelines  
Property_Area - Urban/ Semi-Urban/ Rural  
Loan_Status - Loan approved (Y/N) - Target Variable

**Modeling:**
Experimented with 3 different model - Decision Tree, Logistic Regression and Random Forest.

**Model Evaluation & Selection:**
Performed cross validation to choose Logistic Regression based on all the classification metrics (Accuracy, precision and recall), AUC curve = .86. Further, used grid search to choose best parameters and increased overall recall and precision score. Overall accuracy increased to 86%, precision = .85, recall = .99 and F1-score = .90.  
