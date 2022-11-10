# Lending Club Case Study
> The objective is to identify predictors of default so that at the time of loan application we can use those variables for approval / rejection of the loan.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
  - This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
    Borrowers can easily access lower interest rate loans through a fast online interface.
  - Some borrowers are risky and can result in defaulting on the loans. This results in credit loss and at the same time the company doesn't want to lose business by denying valid loans  
  - Identify applicants that are considered risky there by reducing credit loss but also not incurring business loss due by denying loans
  - A complete dataset of loan data for all loans issued between 2007 and 2011 and also the metadata describing the data are provided

## Conclusions
- High DTI indicates higher risk so should be provided with higher Interest Rates
- Even if lower DTI, if there is no sufficient information of annual income, home-owner ship etc. should be considered a Riskier Loan
- At year-end customer tend to take riskier loans and defaults. It might be better to avoid the holiday season or only take customers with good credit history during this time
- Balance should be struck between the loan term and the interest rate – Longer the term for moderate interest rate, the less chance the customer will default
- Customers with high salary and high DTI will most probably default when taking on large projects / investments
- High Income states with low DTI can get lower interest rates
- Low-income states with high DTI should get higher interest rates for their loans as they are riskier

## Technologies Used
- Python 3.9
- seaborn 0.11.2
- pandas 1.4.4
- numpy 1.21.5

## Acknowledgements
Give credit here.
- As part of the Upgrad Course on ML&AI
- 
## Contact
Created by [@jtkSource] - feel free to contact me!
