# Fintech-Banking_loan_approval-Analysis
# 🏦 Bank Loan Approval Analysis

A data analytics project focused on analyzing bank loan applications to uncover the key factors influencing loan approval decisions. This project demonstrates the complete analytics workflow, from data cleaning and exploratory data analysis (EDA) to business insights and dashboard creation.

---

## 📌 Project Objective

The goal of this project is to analyze customer loan application data and identify patterns affecting loan approval. The analysis helps understand applicant profiles, financial characteristics, and credit behavior that influence lending decisions.

---

## 📂 Dataset

The dataset contains information about loan applicants, including:

- Loan ID
- Number of Dependents
- Education
- Self Employed Status
- Annual Income
- Loan Amount
- Loan Term
- CIBIL Score
- Residential Asset Value
- Commercial Asset Value
- Luxury Asset Value
- Bank Asset Value
- Loan Status

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Power BI

---

# 📊 Data Cleaning

The following preprocessing steps were performed:

- Removed unnecessary spaces from column names
- Checked and handled missing values
- Removed duplicate records
- Verified data types
- Cleaned categorical values
- Removed unnecessary identifier columns (Loan ID)

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

### ✅ Loan Approval Rate
- Visualized approved vs rejected loan applications.

### ✅ Education vs Loan Status
- Compared approval rates based on applicant education.

### ✅ CIBIL Score Analysis
- Studied the relationship between CIBIL score and loan approval.

### ✅ Income vs Loan Amount
- Analyzed how annual income affects the loan amount requested.

### ✅ Self-Employed vs Loan Status
- Compared approval rates between salaried and self-employed applicants.

### ✅ Average Loan Amount by Education
- Identified education groups receiving higher average loan amounts.

---

# 📊 Key Business Insights

- Higher CIBIL scores significantly increase the chances of loan approval.
- Applicants with higher annual income generally receive larger loan amounts.
- Education level influences loan approval trends.
- Self-employed applicants show different approval patterns compared to salaried applicants.
- Loan approval decisions are influenced by multiple financial factors rather than a single variable.

---

# 📷 Dashboard

The Power BI dashboard includes:

- KPI Cards
  - Total Applications
  - Approved Loans
  - Rejected Loans
  - Average Loan Amount
  - Average CIBIL Score

- Pie Chart
  - Loan Approval Distribution

- Bar Charts
  - Education vs Loan Status
  - Self Employed vs Loan Status
  - Average Loan Amount by Education

- Scatter Plot
  - Income vs Loan Amount

- Box Plot
  - CIBIL Score vs Loan Status

---

# 📁 Project Structure

```
Bank-Loan-Approval-Analysis/
│
├── Dataset/
│   └── loan_approval_dataset.csv
│
├── Notebook/
│   └── Loan_Analysis.ipynb
│
├── Dashboard/
│   └── Bank_Loan_Dashboard.pbix
│
├── Images/
│   ├── dashboard.png
│   ├── loan_approval_rate.png
│   ├── education_vs_status.png
│   ├── cibil_boxplot.png
│   └── income_vs_loan.png
│
├── README.md
└── requirements.txt
```

---

# 🚀 Future Improvements

- Build a machine learning model for loan approval prediction.
- Deploy the project as an interactive dashboard.
- Add additional financial KPIs.
- Integrate SQL for data extraction.
- Enhance visualizations with Plotly.

---

# 📬 Connect With Me

If you found this project helpful, feel free to ⭐ this repository and connect with me on LinkedIn.
