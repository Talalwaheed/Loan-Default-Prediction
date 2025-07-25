
**Objective:** To develop a machine learning model that accurately predicts loan default, helping financial institutions assess credit risk and make informed lending decisions.

**Dataset:** The project utilizes a loan dataset containing applicant information such as gender, marital status, education, income, loan amount, credit history, and property area, along with the Loan_Status indicating default or non-default.

**Libraries Used:** Pandas, Scikit-learn (LabelEncoder, train_test_split, GradientBoostingClassifier, SVC), and imblearn (SMOTE).

**Project Activities & Methodology:** I started by preprocessing the data, which involved dropping the Loan_ID, handling missing values (filling categorical with mode and numerical with median), and encoding categorical features using LabelEncoder. To address class imbalance, I applied SMOTE (Synthetic Minority Over-sampling Technique). The data was then split into training and testing sets. Finally, machine learning models such as Gradient Boosting Classifier and Support Vector Machine (SVM) were trained and evaluated using classification reports.

**Benefits:** This project provides a robust tool for credit risk assessment, enabling lenders to minimize financial losses by identifying high-risk applicants. It helps streamline the loan approval process and contributes to more stable financial operations.
