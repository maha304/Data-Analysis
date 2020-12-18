# (Prosper Loan Data Exploration)
## by (Maha Ahmed )


## Dataset

>The dataset consisted of Loan Status and attributes of 113,937 loans. The attributes included  ListingCategory ,IncomeRange, loan term ,  Employment Status , 
original loan amount , and much more with 81 variables. 2280 data points were removed from the analysis due to missing values ,
25 values removed from BorrowerAPR and 2255 from EmploymentStatus .
 The dataset can be found in [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

> In the exploration, I've checked the factors that can be associated with loan Status, so I've choiced the  following variables
(Term,BorrowerAPR,BorrowerRate,ListingCategory (numeric),IncomeRange,LoanOriginalAmount,IncomeVerifiable,EmploymentStatus,StatedMonthlyIncome)

> The Term of the Loan was slightly correlated with the Loan Status about 34800 of borrowers with three year Term have  almost  Completed the  Loans .
and 35400 of borrowers with Three years term was still paying the loan .

BorrowerAPR, BorrowerRate, and  LoanOriginalAmont  had a negative relationship  with the Loan Status.

> there are  no significant  relationship between StatedMonthlyIncome.


## Key Insights for Presentation

> For the presentation, I focus on the  Loan Status types,  I start by introducing the LoanStatus variable, followed by the ListingCategory distribution, 
then plot the BorrowerAPR and LoanOriginalAmount.

> After that , I introduce each of the categorical variables one by one and plot them vs LoanStauts 