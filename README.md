# LendingCaseStudy
# Project Name
> Lending Club Case Study


## Table of Contents
[General Info]

[Approach taken]

[Conclusions]

[Technologies Used]

[Collaborators]


## General Information
Case Study - Objective: To develop a model that assists a consumer finance company in making informed loan approval decisions by identifying patterns in applicant profiles that indicate the likelihood of loan default.
Context: The company specialises in providing various types of loans. When a loan application is received, the company must decide whether to approve or reject the loan based on the applicant profile. This decision involves two primary risks:

Business Loss: If the company deny a loan to someone who is likely to repay it, we lose potential business. 
Financial Loss: If the company approve a loan for someone who is likely to default, we face a financial loss.

Business Objective :The aim is to decide whether to accept or deny loan applications based on specific criteria.

Dataset Details :
The dataset provided includes information on historical loan applicants and their default status. It contains details only on approved loans, not the rejected ones. There are three loan statuses: Fully Paid, Current, and Charged-Off

## Approach taken
Data Clean up process - step by step taken:

1)Importing the Data
2)Removing large null value columns
3)Removing Duplicate Data
4)Removing irrelevant columns
5)Removing/Fixing null values
6)Filter Data for requirement.
7)Removing outliers


## Conclusions / Analysis Outcome
1)Debt-to-Income (DTI) Ratio: Higher DTI ratios suggest increased financial stress and risk.
2)Credit Grades: Lower credit grades (E, F, G) indicate a higher likelihood of default.
3)Verification Status: Verified income and employment status tend to lower the risk of default.
4)Annual Income: Lower annual incomes are associated with a higher probability of default.
5)Public Recorded Bankruptcies: A history of bankruptcy significantly increases the risk of default.
Borrowers Not from Large Urban Cities: Clients outside major metropolitan areas like California, New York, Texas, and Florida may have 6)different risk profiles.
6)Annual Income Between $50,000 and $100,000: This income range is crucial for assessing default risk.
8)Public Recorded Bankruptcy: Borrowers with a history of bankruptcy have a higher risk of default.
9)Low Credit Grades (E, F, G): These grades signify high risk and are indicators of potential default.
10)Very High Debt-to-Income (DTI) Ratio: A high DTI ratio is a strong predictor of default risk.
11)Work Experience of Over 10 Years: Surprisingly, a significant number of defaults occur among borrowers with long work experience.

## Technologies Used
Pandas 
NumPy 
Seaborn 
MatplotLib 
Plotly 

## Contact
Created by Muthyala Surya Bhaskara Rayudu and Aishwarya - feel free to contact us!

## License
This project is open source and available without restrictions.
