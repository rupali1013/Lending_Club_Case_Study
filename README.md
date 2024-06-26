# Lending Club Case Study
> Lending Club is a finance company that provides various loans to city customers. 
The company has a major issue with its loan approval process. 
They need to make smart decisions to avoid losing money, especially from "risky" borrowers.
Losses occur when borrowers fail to repay their loans. 
Borrowers who don't repay are called "charged-off" and cause the most significant losses.


## Table of Contents
* Problem Statement
* General Info
* Conclusions
* Technologies Used
* Acknowledgements

## Problem Statement

### Business Understanding
Loan approved: If the company approves the loan, there are three possible outcomes:

Fully paid: The borrower has paid back the loan amount and interest in full.

Current: The borrower is making payments as scheduled, but the loan term isn't finished yet. These borrowers are not considered to have defaulted.

Charged-off: The borrower has not made payments for a long time and is considered to have defaulted on the loan.

Loan rejected: The company did not approve the loan (because the applicant did not meet the requirements). Since the loan was not approved, there is no payment history for these applicants, and this information is not included in the dataset.

### Objective
The objective is to find applicants at risk of defaulting on loans, enabling a reduction in credit losses. This case study aims to achieve this goal through exploratory data analysis.

## General Information

The main goal of this task is to help Lending Club reduce these credit losses. There are two main challenges:

1. It's important to identify good borrowers who will repay their loans because they generate profit through interest payments. If these  borrowers are rejected, the company misses out on potential business.
2. Approving loans for borrowers who might not repay and could default results in substantial financial losses for the company.


### Data Cleaning & Pre-processing Steps followed:
 * Loading data from loan CSV
 * Checking for null values in the dataset
 * Checking for unique values
 * Checking for duplicated rows in data
 * Dropping Records & Columns
 * Common Functions
 * Data Conversion
 * Outlier Treatment
 * Imputing values in Columns

## Dataset used in this case study 
 * Loan 

### factors need to check for deafulters
- Loan Amount 
- Grade the loan.
- Term  
- Purpose of Loan 
- Verification Status 
- Interest Rate 
- Installment 
- Grade 
- Sub grade 
- Term 
- Employment length 
- Issue year 
- Issue month 
- Issue quarter
- Home Ownership 
- Loan purpose 
- Loan status 
- Address State 
- Loan paid 


## Conclusions

### To prevent the increasing defaulters lending club should use following points:

* Implement Stricter Criteria for Grades B, C, and D: Consider implementing stricter risk assessment and underwriting criteria for applicants falling into Grades B, C, and D to minimize default risks.
* Focus on Subgrades B3, B4, and B5: Pay special attention to applicants with Subgrades B3, B4, and B5. Consider additional risk * * mitigation measures or offering lower loan amounts for these subgrades to reduce default rates.
* Evaluate and Limit 60-Month Loans: Evaluate the risk associated with 60-month loans. Consider limiting the maximum term or adjusting interest rates for longer-term loans to decrease the likelihood of defaults.
* Comprehensive Credit Scoring System: Develop a comprehensive credit scoring system that incorporates various risk-related attributes, as experience alone might not be sufficient to gauge creditworthiness.
* Capitalizing on Market Growth: Capitalize on the market's growth trend observed from 2007 to 2011 by maintaining a competitive edge in the industry while ensuring robust risk management practices.
* Anticipate Peak Periods: Anticipate increased loan applications during peak periods such as December and Q4. Ensure efficient processing to meet customer demands during these busy seasons.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
* Python 3.12.0
* numpy - 1.20.3
* matplotlib - 3.4.3
* seaborn - 0.11.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
* https://learn.upgrad.com/
* https://www.geeksforgeeks.org


## Contact
Created by [@rupali1013] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
