# Bank-Loan-Approval-Analysis-Prediction
This project is an interactive Loan Analytics Dashboard built using Streamlit, Pandas, and Scikit-learn. It performs:

📊 Exploratory loan data analysis

📈 Real-time filtering & insights

🤖 Loan approval prediction using Logistic Regression

The system simulates how banks evaluate loan applications using credit history and loan-to-income ratio logic, and provides instant approval predictions through a clean web interface.




🚀 Key Features
📊 1. Interactive Loan Analytics Dashboard

Dynamic filters:

Gender

Marital Status

Self Employment

Property Area

Credit History

KPI Metrics:

Total Applicants

Average Loan Amount

Approval Rate %

🤖 2. Loan Approval Prediction Engine

Logistic Regression Model

Custom feature engineering:

TotalIncome = ApplicantIncome + CoapplicantIncome

LoanToIncomeRatio = LoanAmount / TotalIncome

Real-time approval prediction

Clean success / rejection UI output

🧠 3. Business Logic Used

Loan approval is primarily influenced by:

✅ Credit History (Strongest Factor)

✅ Loan-to-Income Ratio (< 0.35 improves approval chances)

This mimics simplified real-world banking risk rules.

🛠 Tech Stack

Python

Streamlit

Pandas

Scikit-learn (Logistic Regression)

Custom Feature Engineering
