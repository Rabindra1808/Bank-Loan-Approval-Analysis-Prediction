# Bank-Loan-Approval-Analysis-Prediction
This project is an interactive Loan Analytics Dashboard built using Streamlit, Pandas, and Scikit-learn. It performs:
<ul>
  <li>📊 Exploratory loan data analysis</li>
  <li>📈 Real-time filtering & insights</li>
  <li>🤖 Loan approval prediction using Logistic Regression</li>
</ul>

The system simulates how banks evaluate loan applications using credit history and loan-to-income ratio logic, and provides instant approval predictions through a clean web interface.


<h2>🚀 Key Features</h3>
<h3>📊 1. Interactive Loan Analytics Dashboard</h3>
Dynamic filters:
<ul>
  <li>Gender</li>
  <li>Marital Status</li>
  <li>Self Employment</li>
  <li>Property Area</li>
  <li>Credit History</li>
</ul>


KPI Metrics:

Total Applicants

Average Loan Amount

Approval Rate %

<h3>🤖 2. Loan Approval Prediction Engine</h3>
<ul>
  <li>Logistic Regression Model</li>
  <li>Custom feature engineering:
    <li>TotalIncome = ApplicantIncome + CoapplicantIncome</li>
    <li>LoanToIncomeRatio = LoanAmount / TotalIncome</li>
  </li>
  <li></li>
  <li></li>
  
</ul>








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
