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
<ul>
  <li>Total Applicants</li>
  <li>Average Loan Amount</li>
  <li>Approval Rate %</li>
</ul>


<h3>🤖 2. Loan Approval Prediction Engine</h3>
<ul>
  <li>Logistic Regression Model</li>
  <li>Custom feature engineering:
      TotalIncome = ApplicantIncome + CoapplicantIncome
      LoanToIncomeRatio = LoanAmount / TotalIncome
  </li>
  <li>Real-time approval prediction</li>
  <li>Clean success / rejection UI output</li>
  
</ul>


<h3>🧠 3. Business Logic Used</h3>

Loan approval is primarily influenced by:
<ul>
  <li>✅ Credit History (Strongest Factor)</li>
  <li>✅ Loan-to-Income Ratio (< 0.35 improves approval chances)
</li>
</ul>

This mimics simplified real-world banking risk rules.

<h3>🛠 Tech Stack</h3>
<ul>
  <li>Python</li>
  <li>Streamlit</li>
  <li>Pandas</li>
  <li>Scikit-learn (Logistic Regression)</li>
  <li>Custom Feature Engineering</li>
</ul>








