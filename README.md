# Exploration of Loan Data from Prosper
## by Kolawolé Ogounchi


## Dataset

For this project, we've chosen the "Loan Data from Prosper". The data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

Prior to start our exploration, we have removed the columns with missing values and those that would not be relevant for our analysis. We've made sure through our wrangling process to get to a tidy data set before proceeding with the next steps.


## Summary of Findings

We looked for insights about  "what makes a bad borrowers" i.e. a borrowers that it is expensive for the company to collect interests and principal from.
For that purpose we have explored the following variables: `LP_CollectionFees`, `Occupation`, `EmploymentStatus`, `BorrowerState`, `CreditScore`, `DebtToIncomeRatio`.
We have found that ironically, borrowers that have the highest collections fees are the one with the stable occupations, working full-time or employed, and with low debt-to-income ratio. However, overall those borrowers have below average credit score, which means a history of bad habits in terms of bill/debt payments.
Our conclusion is that bad borrower behaviours are not really associated to some specific features among those that have been explored, it seems more like behaviours motivated by personal traits or habits regarding personal finance management.
In the meantime, among those borrowers, there is some who even have above average credit score but are still causing high collection fees. It is possible that they have started having that behaviour after they got their loans but this still shows that those borrowers are not making their payments just out of bad will and by doing so, are causing high collection fees to the company.


## Key Insights for Presentation

When we look at the univariate exploration of **credit score** and **debt-to-income ratio** we see that even though the majority of borrowers with high collection fees have below average credit score, they manage to get qualify for their loan due to their good standing in terms of occupation, employment status, and precisely "low debt-to-income ratio" which means there's still room in their income to be able to afford the debt payment. However, it seems like after the loans are granted those borrowers show bad will in making their debt payment, a behaviour strongly correlated with those below average credit score found for the majority of them.

On the other hand, we noticed that the most extreme values in terms of collection fees have been noticed with borrowers that even have good credit score. Those are sure isolated cases, but still confirm our conclusions about the reason underlying this bad borrower behaviour.
