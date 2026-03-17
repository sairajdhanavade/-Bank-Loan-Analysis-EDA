# Bank Loan Data Analysis: Financial & Visual Insights

## 📌 Project Overview
This project is an Exploratory Data Analysis (EDA) focused on a financial loan dataset. By transforming raw data into structured insights, this project helps stakeholders monitor lending trends, assess regional performance, and understand borrower demographics.

The analysis is strictly aligned with **Business Requirement Documents (BRDs)** to ensure data-driven decision-making.

## 📊 Key Performance Indicators (KPIs)
The following core metrics are tracked to monitor the health of the loan portfolio:
*   **Total Loan Applications:** Overall and Month-to-Date (MTD) counts.
*   **Total Funded Amount:** Sum of original loan amounts and MTD disbursements.
*   **Total Amount Received:** Total payments from borrowers and MTD cash flow.
*   **Average Interest Rate:** Portfolio-wide average cost of capital.
*   **Average DTI (Debt-to-Income):** Assessing borrower financial stability.

## 📉 Visualizations & Business Insights
As per the BRD specifications, the following charts were developed to uncover deep-tier insights:
1.  **Monthly Trends (Line/Area Chart):** Identifying seasonality in loan issuance.
2.  **Regional Analysis (Bar Chart):** Visualizing loan distribution by State (`address_state`).
3.  **Loan Term Analysis (Donut Chart):** Understanding the split between 36-month and 60-month terms.
4.  **Employment Length Analysis (Bar Chart):** Correlating job stability with loan demand.
5.  **Loan Purpose Breakdown (Bar Chart):** Analyzing the primary reasons (e.g., debt consolidation, home improvement) for borrowing.
6.  **Home Ownership Analysis (Tree/Heat Map):** Hierarchical view of how home ownership (Rent, Mortgage, Own) impacts lending.

## 🛠️ Technology Stack
*   **Python 3.x**
*   **Data Manipulation:** Pandas, NumPy
*   **Data Visualization:** Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook

## 📂 Dataset Structure
The dataset `financial_loan.xlsx` includes 24 columns covering:
- **Loan IDs & Dates:** `id`, `issue_date`, `last_payment_date`
- **Borrower Info:** `annual_income`, `emp_length`, `home_ownership`, `dti`
- **Loan Characteristics:** `loan_amount`, `int_rate`, `term`, `purpose`


