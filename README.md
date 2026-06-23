# 📊 Data Science & Analytics Internship — DevelopersHub Corporation

**Due Date:** 26th June, 2026
**Tasks Completed:** 5 out of 5

---

## 📁 Repository Structure

```
DevelopersHub_DS_Analytics_Internship/
│
├── Task1_Iris_EDA/
│   ├── task1_iris_eda.ipynb
│   └── iris.csv
│
├── Task2_Credit_Risk/
│   ├── task2_credit_risk.ipynb
│   └── loan_prediction.csv
│
├── Task3_Customer_Churn/
│   ├── task3_customer_churn.ipynb
│   └── churn_modelling.csv
│
├── Task4_Insurance_Claim/
│   ├── task4_insurance_claim.ipynb
│   └── insurance.csv
│
├── Task5_Loan_Acceptance/
│   ├── task5_loan_acceptance.ipynb
│   └── bank_marketing.csv
│
└── requirements.txt
```

---

## ✅ Task 1: Exploring and Visualizing the Iris Dataset
**Objective:** Read, summarize, and visualize the Iris dataset.
**Approach:** Loaded with pandas, inspected shape/columns/head, built scatter plots, histograms, and box plots.
**Result:** Dataset is clean (no missing values/duplicates); petal measurements best separate species.

## ✅ Task 2: Credit Risk Prediction
**Objective:** Predict loan default risk from applicant data.
**Approach:** Handled missing values (mode/median imputation), encoded categoricals, trained Logistic Regression.
**Result:** Credit history is the strongest predictor of loan approval; model evaluated via accuracy + confusion matrix.

## ✅ Task 3: Customer Churn Prediction (Bank Customers)
**Objective:** Identify bank customers likely to churn.
**Approach:** Encoded Geography/Gender, trained Random Forest Classifier, analyzed feature importance.
**Result:** Age, Balance, and NumOfProducts are the top churn drivers.

## ✅ Task 4: Predicting Insurance Claim Amounts
**Objective:** Estimate medical insurance charges from personal data.
**Approach:** Encoded categoricals, trained Linear Regression, visualized BMI/age/smoking impact on charges.
**Result:** Smoking status is by far the strongest driver of charges; evaluated via MAE/RMSE/R².

## ✅ Task 5: Personal Loan Acceptance Prediction
**Objective:** Predict which bank marketing customers accept a loan/deposit offer.
**Approach:** Encoded categoricals, trained Decision Tree, extracted business insights from feature importance.
**Result:** Call duration and previous campaign outcome are the strongest acceptance predictors.

---

## 🛠️ How to Run

```bash
git clone https://github.com/YOUR_USERNAME/DevelopersHub_DS_Analytics_Internship.git
cd DevelopersHub_DS_Analytics_Internship
pip install -r requirements.txt
jupyter notebook
```

Each task folder is self-contained — open the notebook inside, ensure the CSV in the same folder, then `Run All`.

---

## 👨‍💻 Author
**Ahmed** — Data Science & Analytics Intern @ DevelopersHub Corporation

## 🏷️ Tags
`Python` `pandas` `scikit-learn` `EDA` `Classification` `Regression` `Internship` `DevelopersHub`
