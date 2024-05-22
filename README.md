# Lending Club Case Study

## Problem Statement

We have a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

* If the applicant is **likely to repay the loan**, then not approving the loan results in a **loss of business** to the company
* If the applicant is **not likely to repay the loan**, i.e. he/she is likely to default, then approving the loan may lead to a **financial loss** for the company

Our goal here is to help this finance company to make good decisions to minimise the risk. This can be done by understanding and anlysing the historical data that this financial institution is willing to provide.

## Business Understanding
The finance compnay has provided historical data which provides various inputs related to loans they have offered including few behavioural attributes of loan applicants. 
Data can looked at [here](https://github.com/salman-kgp/LendingClubCaseStudy/tree/main/Data) and data disctionary which explains what each if the columns mean can be found [here](https://github.com/salman-kgp/LendingClubCaseStudy/tree/main/Data)

The data provided consists of loan attributes like loan amount , funded amount , interest rate , isueed data etc.
The data also provides certain glimpse into customers demographic and financial situation using attributes like address , debt to income ration, revol balance , publicly recorded bankruptcies , details related to delinquecy in past 2years etc.
For each of loan application , loan status is also provided whic denotes 
1. Loan was fully paid
2. Current status i.e payments are still on going
3. Charged off i.e the loan applicant has default and is a loss to the bank.

The prime objective of this assignment is the identify the pattenrs using Exporatory Data Analysis and help the bank to make profitable decisions.

## Technologies Used
- Python - version 3.11.7
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- seaborn - version 0.12.2


## Acknowledgements
- This project created as part of Upgrad's Machine Learning & AI course

## Contact
Created by [@salman-kgp](https://github.com/salman-kgp)

