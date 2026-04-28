# Credit-Card-Applications-Prediction
- By : ABeer Al-Zebda | Machine Learning Engineer**About Dataset**
  
## 💳 Credit Card Application Dataset
This dataset focuses on analyzing and predicting credit card approval decisions using real-world applicant data. It includes multiple customer attributes such as age, financial status, credit history, and employment details, which influence approval outcomes.

The dataset is ideal for building and evaluating machine learning models like Logistic Regression, Decision Trees, and Random Forests to classify whether an application will be approved or rejected.

**📊 Key Features**
- CustomerID: Unique identifier for each applicant
- A1 – A14: Customer attributes (demographics, financial status, credit behavior)
- A15: Target variable (Approval: Yes/No)

**🎯 Use Cases**
Credit risk analysis
Loan/credit approval prediction
Data preprocessing and feature engineering practice
Machine learning classification projects

**data link**
https://www.kaggle.com/datasets/nazishjaveed/credit-card-application

## Data Dictionary
- CustomerID
Unique ID of applicant
- A1
Binary feature (e.g., gender or status)
- A2
Applicant age
- A3
Debt amount or financial burden
- A4
Marital status / category
- A5
Number of dependents or similar factor
- A6
Education / employment level
- A7
Credit history score/category
- A8
Years of employment / experience
- A9
Binary feature (e.g., owns property/phone)
- A10
- A11
- A12
- A13
- A14
- Class (target)

## Steps 
- Import Libraries
- Load and Inspect data
- Clean Data
- Explore Data
  - Applicant age vs Credit history score/category'
   <img width="562" height="455" alt="565426644-2c90e1fe-51e8-4cf4-98e7-45628c894bfd" src="https://github.com/user-attachments/assets/7c0db34b-55e6-404b-a293-1208ff940768" />
  - Marital status / category vs Credit history score/category
   <img width="562" height="455" alt="تنزيل (1)" src="https://github.com/user-attachments/assets/362591cd-aee0-4a69-8e9e-e0161fa1664f" />

- Preprocess
- Build Catbosost model
- Evaluate
  <img width="615" height="283" alt="image" src="https://github.com/user-attachments/assets/3effb1da-5f54-4a55-8547-a1e81bb7d979" />

- Model Insight
  - Top 10 Most Important Features
   <img width="391" height="547" alt="تنزيل" src="https://github.com/user-attachments/assets/ef19e3ad-8ab9-40cb-ae42-4e73a1534eb1" />

- Rebuild model with top 10 importance features
- Evaluate with 10 top features
  <img width="672" height="290" alt="image" src="https://github.com/user-attachments/assets/787dcdeb-da94-4988-af6d-692b8cfa2992" />
---
# Result
**CatBoost gives  88% F1-score and accuracy with all features**
