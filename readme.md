# Prosper Loan Dataset Exploration

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

Detailed description of this dataset can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)


## Summary of Findings

In the exploration, I found that there was a strong relationship between the
Borrower's APR with EmploymentStatus, IncomeRange, BorrowerState, whether
the Income is Verifiable, Term of the loan (in Month), EstimatedLoss, EstimatedReturn
and ListingCategory. Moreover, this relationship was not fixed across the years of our dataset,
as some ListingCategories were either added/removed in 2011, data on EmploymentStatus improved after 2008,
also Borrower's APR in each state varied a lot up until 2013. Another important finding was how APR
spiked at 0.2, by taking deeper looks into the data, I found that it peaked with Term of 60 months period around 0.2,
unlike remaining Term values; Term of 60 Month varied the least around 0.2. I expected to find a strong relationship
between APR and OpenCreditLines however it was almost the same only varied across the years,
on the other hand APR has a strong with ProsperScore and it is negative.

Above findings were verified by further splitting the data by LoanStatus, or ListingCategories.

## Key Insights for Presentation

For the presentation, I focused on just answering those 3 Qs:
- What factors affect a loan’s outcome status?
- What affects the borrower’s APR or interest rate?
- Are there differences between loans depending on how large the original loan amount was?

by demonstrating my findings as figures to directly give answers to those questions.