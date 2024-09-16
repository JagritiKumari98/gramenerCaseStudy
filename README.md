Loan Default Prediction - Exploratory Data Analysis (EDA)
Project Overview
This project focuses on understanding the key factors that influence loan defaults using data from a lending company. The objective is to identify the main variables that indicate the likelihood of a customer defaulting on a loan. These insights can help in improving the loan approval and rejection decision-making process, potentially reducing the company's default rate.

Business Objective
The goal is to use the available data to predict whether a customer is likely to default on their loan, based on factors like income, employment length, loan amount, interest rate, and other characteristics. This will assist in deciding loan approvals or rejections.

Dataset Description
The dataset contains three types of variables:

Customer Demographics – Information about the customer, such as their income, employment status, and home ownership.
Loan Information – Details about the loan, including loan amount, interest rate, and purpose of the loan.
Customer Behavior – If the loan is granted, this includes the customer’s payment history and loan status (fully paid, charged-off, or current).
Key Variables:
Annual Income – Higher income generally increases the chances of loan approval.
Home Ownership – Owning a home adds collateral, increasing approval chances.
Employment Length – Customers with longer employment tenure tend to be more financially stable.
Debt-to-Income (DTI) – A lower DTI ratio indicates better loan repayment capability.
Excluded Variables:
Columns with high levels of missing data or irrelevant information have been excluded from the analysis. This includes columns such as customer behavior details and specific internal company data.
Data Preprocessing
Handled mixed data types and converted variables to their appropriate formats.
Removed columns and rows with missing or irrelevant data, including loans with a status of "Current."
Common functions were developed to streamline visualization and analysis tasks such as plotting and binning.
Analysis
Univariate and Bivariate Analysis
Loan Grade – Loans with higher risk grades (A to G) have higher default rates.
Loan Purpose – Small business and renewable energy loans have higher default rates.
Loan Term – Loans with longer terms (60 months) tend to default more than shorter-term loans (36 months).
Income and Installments – Customers with lower income and higher installments default more frequently.
Interest Rate – Loans with higher interest rates are more likely to default.
Conclusion
The analysis helps in identifying several key factors that increase the likelihood of loan default, such as high interest rates, longer loan terms, low income, and high DTI ratios. These insights can be valuable for the lending company in improving its risk management strategy.

Project Structure
Data Preprocessing: Handling missing data, data cleaning, and formatting.
Univariate Analysis: Analysis of individual variables.
Bivariate Analysis: Relationships between key variables and loan default status.
Visualization: Graphical representations of findings using bar plots, histograms, and box plots.
Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
Jupyter Notebook
How to Run
Clone the repository.
Install the required libraries using pip install -r requirements.txt.
Run the Jupyter Notebook for data analysis and visualization.
Review the results in the output cells of the notebook.
