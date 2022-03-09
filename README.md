# Lending Club Case Study
> The business problem is for a consumer finance company which specialises in giving out various types of loans to urban customers. When the company receives a loan application, it has to make a decision for loan approval based on the applicant’s profile.

We have been provided the historical data for loan applications that were approved by the company after analysing the associated business risks and whether the borrowers defaulted or not.

Our aim is to identify, using EDA, the strong variables which indicate whether a borrower is likely to default. This will be used for taking actions such as denying the loan, reducing the amount of loan, lending at competitive interest rates or at a higher interest rate (for risky applicants), etc. and hence reduce credit loss for the company.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- This project is meant to understand, using EDA, the strong variables which indicate whether a borrower is likely to default on a loan. This will be used for taking actions such as denying the loan, reducing the amount of loan, lending at competitive interest rates or at a higher interest rate (for risky applicants), etc. and hence reduce credit loss for the company.
- This project is a graded assignment under the EDA module of Upgrad and IIITB's Executive PG Program in ML & AI
- The business problem is for a consumer finance company which specialises in giving out various types of loans to urban customers. When the company receives a loan application, it has to make a decision for loan approval based on the applicant’s profile.
- We have been provided the historical data for loan applications that were approved by the company after analysing the associated business risks and whether the borrowers defaulted or not.


## Conclusions
- Loan applications for small businesses, renewable energy and educational purposes have a risk of defaulting. They should be given out cautiously after verification and also at higher interest rates.
- Annual income is a major factor that should be considered before approving/declining a loan application. Applicants having below 40K annual income are prone to high default rates. Loan should be disbursed to them for shorter terms and higher interest rates.
- If a loan applicant has even one public derogatory record or public record of bankruptcy, then bank should be extremely cautious of disbursing loan to such an applicant. There are significantly higher chances of default in such cases.
- Debt to income ratio is also an important variable and should be as low as possible. It should be checked along with other variables such as already open credit lines. If there is an additional debt burden on the borrower with no increase in income, there is a high risk of default
- If the loan amount is extremely high (15,000+), the lender and investors should exercise caution and do enhanced due diligence on the customer as there is significantly higher risk of default than in case of lower amounts
- If the LC assigned grades and sub-grades are lower, then it is a red flag with high risk of default and such loans should be avoided or given out at higher interest rates


## Technologies Used
- Python 3.8.8 (default, Apr 13 2021, 15:08:03) [MSC v.1916 64 bit (AMD64)]
- Jupyter notebook server - version 6.3.0
- IPython 7.22.0
- pandas - version 1.2.4
- numpy - version 1.19.5
- matplotlib - version 3.3.4
- seaborn - version 0.11.1
- plotly - version 5.5.0




## Contact
Created by [@poolakit](https://github.com/poolakit) and [@juhiramzai](https://github.com/juhiramzai) - feel free to contact us!


