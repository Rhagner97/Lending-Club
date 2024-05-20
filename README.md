# Lending-Club

In this case study we have to dertmine the criteria of lending loan main objective to identify the risky loan criteria.
 The process used here:-
  1. Data Cleaning
  2. Univeariate analysis
  3. Bivariate analysis
  4. Mutlitivatiate analysis heatmap
  5. Observation
Overview
The objective of this project is with the help of Loan data set identify factors/ variables responsible for credit loss i.e. probable causes of loan defaults. The project uses EDA techniques to analyse data and derive the conclusion as follows:

Data cleaning - remove outliers, null values, fix data types
Data Analysis - Univariate, Bivariate, Multivariate
Visualise results
Conclusion
Technologies Used
Python - v3.11.5
Python Libraries
pandas - v2.2.2
numpy - v1.26.4
plotly - v5.22.0
matplotlib - v3.9.0
seaborn - v0.13.2
Jupyter Notebook - v7.2.0
Conclusions
Univariate Analysis
Loan Amount: Most loans are small to moderate amounts with a few large loans.
Interest Rate: Interest rates vary, but there might be common rates around certain values.
Annual Income: Most borrowers have moderate incomes; a few have very high incomes.
Debt-to-Income Ratio: Most borrowers have a manageable Debt To Income ratio, but some might have higher values indicating more debt.
Term: A significant proportion of loans are of term 36months
Public record bankruptcies: A very small percentage of loan defaulters have filed bankruptcies.
Derogatory public records: A very small percentage of loan defaulters have derogatory public records.
Majority of the Charged off loans belong to customers with employment length around 10 and above years
Majority of the Charged off loans belong to customers who took loan for purpose of another debt consolidation
Majority of the Charged off loans belong to customers who live in a rented place and second to it who already have mortgage on their homes
Bivariate Analysis
Interest Rate: Higher interest rates correlate with a higher risk of loan default.
Length of Employment: Stable, long-term employment is associated with better loan repayment, though it's not a strong standalone predictor.
Annual Income Groups: Higher annual incomes (above 58k) are associated with a higher likelihood of fully repaying loans. Lower income groups (3k-31k) show a higher risk of default, suggesting that income level is an important factor in assessing loan repayment capability.
Verification Status: Verified income and employment significantly reduce the risk of loan default.
Higher Grades (A, B): Likely to have fewer charged-off loans due to lower risk.
Moderate Grades (C, D): Higher likelihood of charged-off loans compared to higher grades.
Lower Grades (E, F, G): Higher risk categories with more charged-off loans.
Higher Interest Rates: Charged Off loans are more concentrated at higher interest rates, suggesting that borrowers with higher interest rates are at a greater risk of default.
Loan Amounts: There is no clear differentiation in loan amounts between Fully Paid and Charged Off loans, indicating that loan amount alone may not be a strong predictor of default.
Combined Effect: While higher loan amounts are generally associated with higher interest rates, the risk of default appears to be more closely related to the interest rate rather than the loan amount.
Loan amount vs Public Record of Bankruptcies is inconclusive to derive a loan amount range that is relative to bankruptcies
Maximum number of loan defaulters(Charged Off loan_status) were in the following ranges:¶
Interest Rate - 11.26 - 16.32
Annual Income - 36.3k - 71.67k
Debt to Income Ratio - 9.18 - 19.40
Highest number loan defaulters(Charged Off loan_status) are as follows:
Requested loan during the month - December
Requested loan during the year - 2011
Highest number loan defaulters(Charged Off loan_status) are as follows:
Requested loan for Purpose - Debt Consolidation
Requested loan from State - CA - California
Highest number loan defaulters(Charged Off loan_status) are as follows:
9%-17% Interest rates

2-10 open credit lines

2-37 total credit lines currently in the borrower's credit file

31k - 85k Annual Income

5k - 10k Loan Amount

Multivariate Analysis

Higher interest rates, high DTI ratios, and high revolving utilization are key indicators of higher default risk.
Lower annual income may also contribute to higher default risk.
Interest Rate (int_rate): Higher rates are associated with higher default risk.
Annual Income (annual_inc): Lower incomes are linked to higher default rates.
Debt-to-Income Ratio (dti): Higher DTI ratios are indicative of higher default risk.
Revolving Utilization (revol_util): Higher utilization rates correlate with higher default risk.
Public Record Bankruptcies (pub_rec_bankruptcies): History of bankruptcies increases default likelihood.


Contributor

 1.Soumendu Dasgupta
 2.Sonal Jatav
