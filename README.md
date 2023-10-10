# Lending Club Case Study
A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Team](#team)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

- If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

- To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

 
- We have been provided loan dataset contains the complete loan data for all loans issued through the time period 2007 t0 2011. We also have been provided data dictionary for dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:

- Annual income
- DTI
- Grades
- Public Record of Bankruptcies
- Verification Status


Other considerations for 'defaults' :

- Applicants with working experience 10+ years.
- Applicants having annual income in the range 50k-100k.
- Applicants having Public Recorded Bankruptcy.
- Applicants with least grades like E,F,G which indicates high risk.
- Applicants with very high Debt to Income value.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Data loading and manipulation libraries
- pandas : Version - 2.0.3

Data visualization libraries
- seaborn : Version - 0.12.2
- matplotlib.pyplot : Version - 3.7.2
- plotly.express : Version - 5.9.0

Utility
- IPython.display
 - Markdown
 - display
- warnings


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was while doing MS in Artificial Intelligence and Machine Learning from IIIT Bangalore


## Contact
* [Bibhuti Ranjan Sinha](https://www.linkedin.com/in/bibhutiranjansinha/) - feel free to contact me!
* [Heena Jain](https://www.linkedin.com/in/heena-s-jain/) - feel free to contact me!

## team
* [Bibhuti Ranjan Sinha](https://github.com/bibhutiranjansinha)
* [Heena Jain](https://github.com/Jheena-20/)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->