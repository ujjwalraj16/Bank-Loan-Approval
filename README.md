📊 Loan Approval Prediction

📌 Overview
This project predicts whether a loan application will be approved or rejected based on applicant details such as income, credit history, loan amount, and more.
It uses Logistic Regression and Random Forest models to compare performance.

📂 Dataset

File: loan_approval_dataset.csv

Rows: 4,270

Columns: 13 (including target loan_status)

Target:

Y → Loan Approved
N → Loan Rejected

⚙️ Technologies Used
🐍 Python

📊 Pandas, NumPy

🤖 scikit-learn (ML Models)

📈 Matplotlib, Seaborn (Visualization)

🔍 Data Preprocessing

Removed irrelevant columns (loan_id)

Handled missing values

Label encoding for categorical variables

Feature scaling using StandardScaler

🤖 Models Implemented

Logistic Regression

Random Forest Classifier (Default & Tuned Hyperparameters)

| Model                      | Accuracy   |
| -------------------------- | ---------- |
| Logistic Regression        | **79.15%** |
| Random Forest (Default)    | **98.36%** |
| Random Forest (Best Tuned) | **97.69%** |

📊 ROC Curve Example
Both models were evaluated using ROC-AUC to measure classification performance beyond accuracy.

📌 Conclusion

Random Forest significantly outperforms Logistic Regression for this dataset.

Logistic Regression still provides a simpler, interpretable model.

Future improvements could include SMOTE for imbalance and feature engineering.
