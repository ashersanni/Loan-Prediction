# Loan-Prediction Using ML

This project focuses on developing a **loan prediction model** to determine the likelihood of loan approval based on applicant characteristics. The model leverages multiple machine learning techniques to achieve accurate predictions and provide insights into the key factors influencing loan approval.

## **Objective**
To predict whether a loan application will be approved based on features such as:
- Income
- Employment status
- Marital status
- Other relevant demographic and financial factors

## **Dataset**
- **Source**: The dataset includes information about applicants and their loan approval status.
- **Features**:
  - Applicant income
  - Co-applicant income
  - Loan amount
  - Loan term
  - Credit history
  - Gender, marital status, education, and employment type
  - Property area
- **Target**: Loan approval status (Approved/Not Approved).

## **Project Workflow**
1. **Data Preprocessing**
   - Handled missing values using appropriate imputation methods.
   - Encoded categorical variables using one-hot encoding.
   - Scaled numerical features to normalize ranges.

2. **Model Implementation**
   - Evaluated three machine learning classifiers:
     1. **Logistic Regression**
     2. **Random Forest**
     3. **Support Vector Machine (SVM)**
   - Split data into training and testing sets to evaluate model performance.

3. **Hyperparameter Tuning**
   - Used grid search to optimize hyperparameters for each model.
   - Selected the best-performing model based on evaluation metrics.

4. **Model Evaluation**
   - Compared models using metrics such as accuracy, precision, recall and F1-score.
   - Identified the most accurate model for loan prediction.


## **Tools and Libraries Used**
- **Programming Language**: Python
- **Libraries**:
  - pandas, numpy (data manipulation)
  - matplotlib (visualization)
  - scikit-learn (modeling and evaluation)

## **Future Work**
- Deploy the model as a web application using **Streamlit** or **Flask**.
- Incorporate additional features, such as applicant credit scores, to improve accuracy.
- Explore ensemble techniques for further boosting model performance.
