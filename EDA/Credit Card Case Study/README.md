
# Credit Card Case Study:

The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credit history. Because of that, some consumers use it as their advantage by becoming a defaulter. 
Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
This EDA case study will help the learner in developing a basic understanding of risk analytics in banking and financial services and understand how data is used to minimize the risk of losing money while lending to customers and ensure that the applicants capable of repaying the loan are not rejected.

## Business obejective:
This case study aims to identify patterns/variables which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

## Dataset Information

This dataset has 3 files as explained below: 
1. 'application_data.csv' contains all the information of the client at the time of application.The data is about whether a client has payment difficulties.

2. 'previous_application.csv' contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
3. 'columns_description.csv' is data dictionary which describes the meaning of the variables.
Please use the below link for downloading the dataset:

[Loan application dataset](https://drive.google.com/drive/folders/16RQztUqCfJOlbooHqYlJrp6Q7iL65uZB)

## Result
1.	Females are more likely to repay loan inspite of failing to repay on time. Bank can target more to female for profit.
2.	Though married people used to take loan more but they are also first in defaulter list, so bank should give loan to them with caution to avoid loss.
3.	Bank can target people whose purpose of loan is education as they are less likely to reject it also they are less likely to comes under default category.
4.	Banks should focus less on income type ‘Working’ as they are having most number of unsuccessful payments 
5.	Bank can focus on these purposes for which the client is having for minimal payment difficulties.

    a.	'Building a house’, ‘Everyday expense','Medicine','Payment on the loans' are some purpose in which payment of difficulties is almost same.
    
    b.	On housing type ‘with parents’, ‘House\apartment’ and ‘municipal apartment’ for successful payments.



## Software and Libraries

[Python 2.7 or Higher](https://www.python.org/downloads/)

[Numpy](https://pypi.org/project/numpy/)

[Matplotlib](https://pypi.org/project/matplotlib/)

[Pandas](https://pypi.org/project/pandas/)

[Jupyter Notebook](https://jupyter.org/install)

[Seaborn](https://pypi.org/project/seaborn/)

