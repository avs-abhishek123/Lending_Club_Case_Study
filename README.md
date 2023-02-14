# Lending Club Case Study for Loan Defaulters Prediction System
> In this case study, we are attempting to solve a real world business problem using Exploratory Data Science techniques. We will be understanding and solving a risk analytics problem in Banking and Financial Domain.We will be checking how data can be used effectively to solve business problems like defaulters prediction in Loan Lending club

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#Contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

We will be using Exploratory Data Analysis Techniques for Loan Lending System.

- What is the background of your project?

In this case study, we are attempting to solve a real world business problem using Exploratory Data Science techniques. We will be understanding and solving a risk analytics problem in Banking and Financial Domain.We will be checking how data can be used effectively to solve business problems like defaulters prediction in Loan Lending club

- Business Problem Statement:

We are working for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1)If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2)If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- What is the dataset that is being used?

The data given to us contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- If more loan amount is given Lending Club will be in profit because the interest rate increases with higher loan amount.
- Grades should be analyzed thoroughly before lending money as A-grade is a top grade for lending.
- A derogatory item can be considered as a negative entry by the lenders as it indicates public records & collections reflect financial obligations that were not paid as agreed. Inturn, risk and hurts your ability to qualify for credit or other services. Those who have pub_rec value 1 or 2 have higher chances of charged-off than who have no derogatory Public Record. pub_rec count with 3 or 4 cannot reach on any conclusions as there are less numbers.
- States NV,CA and FL states & Dec, May, Sep are the Loan issue month shows high numbers of charged offs  in good number of applications. So, the Lending Club should issue less loans in these states  & during these issue months.
- Less loans to these kind of applicants who are not working or have less than 1 year of work experience have high chances of getting charged off. 
- Lending Club should issue less loans to Small Business Owners as they defaults the  most.

Heavy impact
- Higher interest rate (above 13%)
- Higher revolving line utilization rate (above 58%)
- Repayment term (5 years)
- Loan grade & sub-grade (D to G)
- Missing employment record
- Loan purpose (small business, renewable energy, educational)
- Derogatory public records (1 or 2)
- Public bankruptcy records (1 or 2)

Minor Impact
- Higher loan amount (above 15.5K)
- Higher installment amount (above 325)
- Lower annual income (below 36.7K)
- Higher debt to income ratio (above 14.7%)
- Applicant’s address state (NV, SD, AK, FL, etc.)
- Loan issue month (May, Sep, Dec)

Combined impact
- High interest rate & loan amount for lower income applicants
- Longer repayment term & High installment 
- Home ownership (other) and loan purpose (car, moving or small business)
-Loan purpose & Residential state
- Income group & loan purpose

Loan Acceptance
- For Weddings, Major Purchases, Car
and Credit Card purposes.
- Loan amount ranging between 5,000
USD and 10,000 USD.
- Annual Income of applicants more
than 1,00,000 USD.
- Calculated interest rate for loan less
than 7.5%.
- Grade A&B.
- Loan applicant is owning a house.
- Loans for 36 months term.


Loan Risk Factors
- Loans for purpose of Small Business.
- Loans for loan amount 30,000 USD
and above.
- Loan applicants annual income
whose annual income is less than 25000
USD.
- Loans having calculated interest rate
more than 15%.
- Loans in grade E, F&G.
- Loan applicant is either living on rent
or mortgage.
- Loans for 60 months term.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.6.9
- Numpy - version 1.21.5
- Pandas - version 1.3.5
- Seaborn - version 0.11.2
- dataprep - 0.4.0
- re - 2.2.1


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad.
- This project was based on Upgrad's Tutorial.


## Contact
Created by 

| Contributors | GitHub | Linkedin |
| ----------- | ----------- | ----------- |
| Shruti Pandit  | [GitHub](https://github.com/shrutipandit707) | [LinkedIn](https://www.linkedin.com/in/shruti-pandit-7b946883/) |
| Allena Venkata Sai Abhishek | [GitHub](https://github.com/avs-abhishek123) | [LinkedIn](https://www.linkedin.com/in/allena-venkata-sai-abhishek-381937156/) |

  feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
