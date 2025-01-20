LENDING CLUB CASE STUDY

LENDING CLUB is a finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.Lending loans to 'risky' applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

There are two types of risks  associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. Those applicants will be potentially labelled as "risky" customer.

Primary objective of Lending Club Case Study to identify the customers to avoid the credit loss.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

General Information

Objectives-
The primary objective of a Lending Club case study is to identify patterns which indicate if a person is likely to default on their loans.For this case study we are trying to achieve our goal using Exploratory Data Analysis (EDA).

Associated risks-
Lending Club faces the risk of loan defaults, where borrowers fail to repay their loans.This can lead to significant financial losses for both the company and investors.   
On the other hand If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.


- Already we have a dataset which tells us about the applicant's payment history for previous loan. We need to find out if the applicant should be considered as risky or not for approving next loan using that dataset.


Conclusions
1. Loan Amount and Funded Amount- Though we have some outliners but it does not have huge impact on finding defaulters.
2. Annual Salary- For Few applicants annual income is low but the loan_amnt is in higher range and prevous loan status is charged off. Though the number is not huge those set of applicants should be considered risky. They have the chanes to default.
3. Purpose- Those who have taken loan for small buiness have the high tendency to be defaulters followed by renewable_energy.
4. Home_OwnerShip- For each category we have a chance to find defaulters.In case of home_ownership is Other there is a chance of getting high percentage of defaulters followed by rent and own.In case mortgage the value is lowest.
5. Revol_Util-loan_status Vs revol_util shows that borrower who have used their credit limit more are more likely to have Charged off status that means they are more likely to default
6. Employment_Length- Employment length doesn't really have a huge impact on repayment of loan.
7. DTI- DTI is not playing very important factor to find the defaulters
8. DELININQ_2_YEARS-When delinq_2yrs is 8 the defaulters value is 50 percent. We cannot predict a specific pattern to find the defauters considering delinq_2yrs as the pattern in not consistent.
9. Grade-It is a consistent pattern. The chance of finding defaulters is highest for grade G and lowest in grade A.Company should consider D,E,F and G grade as risky and implement proper risk asessment for those grades.
Technologies Used
- numpy 	    1.26.4
- pandas	    2.2.3
- matplotlib	3.9.2
- seaborn	    0.13.2


Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.


## Contact
Created by [@rituparnabiswas] and []
