# Project Name : Lending Club Case Study
Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in      EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while     lending to customers.
  
- What is the background of your project?
  The consumer finance company specializes in lending various types of loans to urban customers. When the company receives a loan application, it has to make a decision for loan     approval based on the applicant profile.
  Loan Acceptance Scenarios:
    If the applicant is likely to repay the loan, then not approving the loan results in a loss of business.
    If the applicant is not likely to repay the loan (i.e., likely to default), approving the loan may lead to a financial loss for the company.
  Loan Rejection:
    If the loan is rejected, there is no transactional history with the company, and thus, this data is not available in the dataset.
  
- What is the business probem that your project is trying to solve?
  The goal is to identify patterns that indicate if a person is likely to default, which can be used for taking actions such as denying the loan, reducing the loan amount, or
  lending to risky applicants at a higher interest rate.
  
- What is the dataset that is being used?
  39,717 Loan applications from 2007 to 2011
  Loan Amount: Loans range from small to large amounts, with most loans being smaller.
  Interest Rate: Rates are generally centered around mid-ranges.
  Loan Status: Most loans are in good standing, either fully paid or current.

  
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Strong Correlations (> 0.3)
    Loan Amount (loan_amnt): Often shows a moderate to strong positive correlation with loan defaults. Larger loan amounts are associated with a higher likelihood of default.
    Interest Rate (int_rate): Typically shows a moderate positive correlation with loan defaults. Higher interest rates are associated with higher default risk.
    Debt-to-Income Ratio (dti): Generally shows a moderate positive correlation with loan defaults. Higher DTI ratios indicate higher default risk.
    Loan Term (term): Commonly shows a moderate positive correlation with loan defaults. Longer loan terms (60 months) are associated with higher default rates.
    Verification Status (verification_status): Should show a significant correlation, where verified income typically results in lower defaults. Verified income status reduces the     risk of default.
- Weaker Correlations (< 0.3)
    Annual Income (annual_inc): Often weaker correlation with loan defaults.
    Employment Length (emp_length): Usually weaker correlation with loan defaults.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.26.4
- Pandas - version 2.1.4
- Matplotlib - version ?
- Seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad Statistics Essential Case Study Assignment Submission
- References if any...
- This project was based on [(https://learn.upgrad.com/course/5802/segment/50929/312242/946628/4723992)]


## Contact
Created by @ashish.vxii76 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
