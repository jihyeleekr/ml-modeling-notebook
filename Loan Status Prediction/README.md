# Loan Status Prediction

A classification project that uses a historical loan application dataset to predict whether a loan will be approved or rejected based on applicant demographics and financial data.

---

##  Dataset

**Source:** `dataset.csv`  
**Target:** `Loan_Status` (Approved = 1 / Rejected = 0)  
**Features include:**  
- `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`
- `Credit_History`
- `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`
- `Property_Area` (Rural, Semiurban, Urban)

---

##  Model

**Classifier:** Support Vector Machine (SVM) using `sklearn.SVC()`

---

##  Techniques & Evaluation

✅ Data cleaning: Drop rows with missing values  
✅ Label encoding and feature conversion for categorical variables  
✅ Exploratory Data Analysis: Seaborn countplots for `Education` and `Married` vs `Loan_Status`  
✅ Train/test split (80/20) with stratified sampling  
✅ Model training with SVM Classifier  
✅ Evaluation:  
- **Train Accuracy:** ~[0.70]%  
- **Test Accuracy:** ~[0.6875]%

---

##  Visualizations

- Count plots: `Education` vs `Loan_Status`
- Count plots: `Married` vs `Loan_Status`

---

