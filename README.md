# Credit-Card-Default

## Problem Statement

Our client is a credit card company. They have brought us a dataset that includes some demographics and recent financial data (the past six months) for a sample of 30,000 of their account holders. This data is at the credit account level; in other words, there is one row for each account (you should always clarify what the definition of a row is, in a dataset). Rows are labeled by whether in the next month after the six month historical data period, an account owner has defaulted, or in other words, failed to make the minimum payment.

### Columns

The account ID column is referenced as ID. The remaining columns appear to be the features, with the last column being the response variable. 
**LIMIT_BAL:** Amount of the credit provided (in New Taiwanese (NT) dollar) including individual consumer credit and the family (supplementary) credit.
**SEX:** Gender (1 = male; 2 = female).
**EDUCATION:** Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
**MARRIAGE:** Marital status (1 = married; 2 = single; 3 = others).
**AGE:** Age (year).
**PAY_1–Pay_6:** A record of past payments. Past monthly payments, recorded from April to September, are stored in these columns.
PAY_1 represents the repayment status in September; PAY_2 = repayment status in August; and so on up to PAY_6, which represents the repayment status in April.
The measurement scale for the repayment status is as follows: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; and so on up to 8 = payment delay for eight months; 9 = payment delay for nine months and above.
**BILL_AMT1–BILL_AMT6:** Bill statement amount (in NT dollar).
BILL_AMT1 represents the bill statement amount in September; BILL_AMT2 represents the bill statement amount in August; and so on up to BILL_AMT7, which represents the bill statement amount in April.
**PAY_AMT1–PAY_AMT6:** Amount of previous payment (NT dollar). PAY_AMT1 represents the amount paid in September; PAY_AMT2 represents the amount paid in August; and so on up to PAY_AMT6, which represents the amount paid in April
