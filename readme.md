# Home Credit Default Risk
## Can you predict how capable each applicant is of repaying a loan?

Welcome to my model of the follwowing [Kaggle competition](https://www.kaggle.com/c/home-credit-default-risk/). We are given the problem:

"Many people struggle to get loans due to insufficient or non-existent credit histories. And, unfortunately, this population is often taken advantage of by untrustworthy lenders.

Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In order to make sure this underserved population has a positive loan experience, Home Credit makes use of a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.

While Home Credit is currently using various statistical and machine learning methods to make these predictions, they're challenging Kagglers to help them unlock the full potential of their data. Doing so will ensure that clients capable of repayment are not rejected and that loans are given with a principal, maturity, and repayment calendar that will empower their clients to be successful."


### Goal
Our goal for this project is to create a model that predict a new clients ability to repay a loan. 

### Evaluation
Submissions are evaluated on area under the ROC curve between the predicted probability and the observed target.

### Data 
We are given multiple connected datasets to work from. They are as follows:
1. application_{train|test}.csv - This is the main dataset we are working off of. It contains the primary keys which connect this table to other more specific tables.
2. bureau.csv
3. bureau_balance.csv
4. POS_CASH_balance.csv
5. credit_card_balance.csv
6. previous_application.csv
7. installments_payments.csv
8. HomeCredit_columns_description.csv

# This project is a work in progress. I am currently on the EDA part of the project!
