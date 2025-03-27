# Loan Approval Analysis

## 📌 Project Overview
This project focuses on analyzing loan approval data to identify key factors that influence loan approvals. The dataset contains information about applicants' financial status, assets, creditworthiness, and other critical parameters. The analysis aims to provide insights into loan approval trends and develop predictive models to assist lenders in decision-making.

## 📂 Dataset Information
The dataset consists of multiple financial and demographic features of loan applicants. Below are the key columns:

| Column Name                 | Description |
|-----------------------------|-------------|
| `loan_id`                   | Unique identifier for each loan application |
| `no_of_dependents`          | Number of dependents of the applicant |
| `education`                 | Educational background of the applicant |
| `self_employed`             | Indicates whether the applicant is self-employed (Yes/No) |
| `income_annum`              | Annual income of the applicant (in currency units) |
| `loan_amount`               | Loan amount requested by the applicant |
| `loan_term`                 | Duration of the loan in months/years |
| `cibil_score`               | Credit score of the applicant (ranging from 300 to 900) |
| `residential_assets_value`  | Value of the applicant’s residential assets |
| `commercial_assets_value`   | Value of the applicant’s commercial assets |
| `luxury_assets_value`       | Value of the applicant’s luxury assets |
| `bank_asset_value`          | Total bank balance and asset value |

## 🎯 Objectives
- Perform **Exploratory Data Analysis (EDA)** to understand trends in loan approval.
- Identify key factors that impact **loan approval decisions**.
- Use **statistical tests** (e.g., T-tests) to compare financial characteristics of approved vs. rejected loans.
- Develop **predictive models** to classify loan approval outcomes based on applicant attributes.

## 🛠️ Tools & Technologies
- **Programming Language:** Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn)
- **Visualization Tools:** Matplotlib, Seaborn
- **Machine Learning Models:** Logistic Regression, Decision Trees, Random Forest
- **Statistical Analysis:** T-tests, Correlation Analysis

## 📊 Key Insights
- Higher **CIBIL scores** and **higher income levels** are strongly correlated with loan approvals.
- Self-employed individuals may face more **loan rejections** due to inconsistent income sources.
- **Luxury and commercial assets** can play a role in determining loan approval probability.
- Statistically significant differences exist between **approved and rejected loans** in terms of financial factors.

## 🚀 Getting Started
### 1️⃣ Clone the Repository:
```sh
 git clone https://github.com/DataDruid-ops/loan-approval-analysis.git
```

### 2️⃣ Install Required Libraries:
```sh
 pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

### 3️⃣ Run the Analysis:
Execute the Python script to perform data analysis:
```sh
 python loan_analysis.py
```

## 📌 Future Enhancements
- Improve the **predictive model** with advanced ML algorithms (e.g., XGBoost, Neural Networks).
- Deploy an **interactive dashboard** for real-time loan approval insights.
- Integrate external financial APIs to **enrich dataset features**.

## 📞 Contact
For questions or contributions, reach out via:
- **GitHub Issues**
- **Email:** datadruid83@gmail.com


