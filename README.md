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
- Loan Amount (loan_amnt):
The scatter plots show that both "Fully Paid" and "Charged Off" loans are spread across all loan amounts. However, there is a higher density of "Fully Paid" loans at lower loan amounts. Higher loan amounts do not show a clear trend towards more defaults, but there is a slight increase in "Charged Off" loans at higher loan amounts.
Weak negative correlation with loan status (-0.06). Loan amount has a weak association with loan status, indicating it is not a strong predictor of defaults.

- Interest Rate (int_rate):
There is a noticeable concentration of "Charged Off" loans at higher interest rates. The density plot shows a higher peak for "Charged Off" loans at higher interest rates compared to "Fully Paid" loans. Higher interest rates are associated with a higher likelihood of defaults.
Moderate negative correlation with loan status (-0.10). Higher interest rates are somewhat associated with higher defaults.

- Annual Income (annual_inc):
"Charged Off" loans are more frequent in the lower annual income ranges, though "Fully Paid" loans are also present across all income levels. The density plot shows a higher peak for "Fully Paid" loans at higher incomes.
Lower annual incomes are associated with a higher likelihood of defaults.
Weak positive correlation with loan status (0.07). Higher incomes are slightly associated with lower defaults.

- Debt-to-Income Ratio (dti): 
There is a higher concentration of "Charged Off" loans at higher dti values. The density plot shows a higher peak for "Charged Off" loans at higher dti values compared to "Fully Paid" loans. Higher dti values are associated with a higher likelihood of defaults.
Weak negative correlation with loan status (-0.04). Higher dti values have a slight association with higher defaults.

- Employment Length (emp_length):
Both "Fully Paid" and "Charged Off" loans are distributed across all employment lengths, with a slight increase in "Charged Off" loans at shorter employment lengths. Shorter employment lengths might be associated with a higher likelihood of defaults, though this is not a strong predictor.
Very weak negative correlation with loan status (-0.01). Employment length has a very weak association with loan status.


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
