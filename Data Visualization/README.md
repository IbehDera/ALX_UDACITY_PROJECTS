# Prosper Loan Data Exploration
## by Ibeh Chidera


## Dataset

Prosper is a peer-to-peer lending platform funded by Investors. This data set contains 113,937 rows with 81 columns on each loan, including loan amount, borrower rate, current loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information. 

First, The Data Cleaning step:
I checked for the datatypes of each attributes relevant to my analysis and changed the datatypes to appropriate datatypes. I also splitted the Date column to 3 consecutive columns so as to get the year insight alone. I also dropped all irrelevant columns to simplify my analysis.

Secondly, The Data Exploration step:
I explored the dataset using the 'Question-Visualization-Observations' procedure, the exploration was first done on individual variables, followed by comparing the effect of two variables each other and lastly the effect of 3 variables. 

## Summary of Findings

The Analysis made, these are the insights I observed:
The Term with the major distribution is 36months, and Prosper Loan allocated more loan in 2013, and then there was a sharp decrease in 2014.

I plotted a heat map with the correlations of the numeric variables, there were no strong relationship between any of the variables. But i noticed something interesting with regards to my main feature question, there was a weak negative correlation between Loan Amount and Borrower Rate. My question was to find out what would help a Borrower get a Loan with good condition, i.e as the Loan Amount Increases, Borrower Rate reduces. 

So to find out what whether Employment Status and Income Range would affect the Amount of loan a Borrower can get, I did some categorical and numerical analysis. I observed that most Employed Borrowers have current loans, and the Borrower Rate is Low for High income earners.

I also observed that Low income earners with occupations like students and waiters/waitresses get low loan Amount, with High Borrower rate.

## Key Insights for Presentation

The main aim of the analysis is to determine the chances that a Borrower has to get a Loan with favorable loan conditions. Attributes like EmploymentStatus, Occupation, LoanOriginalAmount, IncomeRange, BorrowerRate, Debt-to-Income Ratio and LoanStatus helped to give me the appropriate insights to my analysis.  
![Uploading Prosper Loan Dashboard.jpg…]()
