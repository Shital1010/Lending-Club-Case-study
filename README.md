# Project Name
> LendLoan Guidelines

## Table of Contents
* Sheetal_Chetna.ipynb file conatins python code for EDA & data visualization.
* LendLoan_Guide.pptx contains presentation for the project.
* This project is developed on python 3.9.0 , jupyter notebook.

## General Information
- This project is developed to minimise risks involved in lending loan to any person by consumer company.
- When company approves/rejects  loan to any applicant , there are 2 types of risks involved 
    1. Business loss - when user can pay loan but company has not approved loan to him/her.  
    2. Financial loss - When company approves loan but end user don't pay loan.
- Dataset used for making all conclusions - Loan.csv


## Conclusions
- Data was used for analysis was 39717 rows * 111 columns. 

- Out of total data , 
    (i) 32950 data was of customers who fully paid their loan.
   (ii) 5627 data was of customers who have not paid their loan(defaulters data).
  (iii) 1140 data was of customers whose loan is in progress of payment.

- For all loans , loan amount lies in the range of 5k to 15k.

- For all loans , interest rate lies in the reange of 9% to 30%.

- To fetch more insights from data, we have divided dataset in 2 parts; having 1st part of users who had fully paid loan and 2nd part       contains data of users who had nod paid loan and hence falls into defaulters category.

- Analysis of Fully paid data :
    1. Loan term lies nearby to 36 months.
    2. Loan grade is A,B,C.
    3. Employment length ranges between 3 yrs to 9 yrs.
    4. Purpose behind taking loan : Other, wedding, debt_consolidation sometimes house,moving,renewable_energy,educational.

- Analysis of defaulters data :
    1. Loan term lies between 36 months to 60 months.
    2. Loan grade is F,D,A,B.
    3. Employment length ranges between 1 yrs to 3 yrs and 9+yrs.
    4. Purpose behind taking loan : debt_consolidation, major_purchase.

- After analysing all above data, we conclude that, 
Whenever any end user submit application for loan , following points need to be check before approving / rejecting loan to minimise risk involved.
    1. Loan should be given to people whose employment length ranges between 3 to 9 yrs.
    2. Loan term should be nearby 36 months where financial risk is less.
    3. Purpose behind taking loan should be checked - generally speaking if purpose is debt_consolidation or major_purchase then should be avoided such customer to avoid credit loss in future.

## Technologies Used
- pandas  - version 2.8.2
- numpy   - version 1.25.2
- seaborn - version 2.0.3
- matplotlib - version 3.6.1

## Acknowledgements
- This project has been developed as an assignment provided on Upgrad platform under Programme of Post Graduate in Machine Learning.
- This project was based on lectures completed till today related to EDA, python basics & data visualization.


## Contact
Created by [@Shital1010] - feel free to contact me!




