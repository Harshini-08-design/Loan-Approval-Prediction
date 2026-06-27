# Loan Prediction Project

This project demonstrates data preprocessing, feature encoding, and loan approval prediction using the Loan Prediction dataset in Python.

---

## Tasks Completed

- Loaded and explored the Loan Prediction dataset
- Checked dataset information using `info()`
- Handled missing values using mode imputation for categorical columns
- Verified that the dataset contained no missing values
- Dropped the `Loan_ID` column
- Explored categorical features and their unique values
- Applied Label Encoding/Mapping to categorical columns:
  - Gender
  - Married
  - Education
  - Self_Employed
  - Loan_Status
  - Property_Area
- Converted the `Dependents` column into numeric values
- Separated features (`X`) and target (`y`)
- Split the dataset into Training and Testing sets
- Trained a Random Forest Classifier model
- Predicted loan approval on the test dataset
- Evaluated the model using Accuracy Score
- Generated a Confusion Matrix
- Displayed a Classification Report (Precision, Recall, F1-Score)

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Machine Learning Algorithm

- Random Forest Classifier

---

## Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

---

## Files Included

- loan.csv
- LOAN PREDICTION.ipynb (Assessment-4.ipynb)

---

## Project Outcome

This project demonstrates a complete machine learning classification workflow for loan approval prediction. It includes data preprocessing, handling missing values, feature encoding, model training using Random Forest, prediction, and performance evaluation using multiple classification metrics.
