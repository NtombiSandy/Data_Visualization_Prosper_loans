# Prosper Dataset Exploration
## by Ntombi Mashila


## Dataset

>The Prosper data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. I decided to focus on loans that have resulted in a net loss for the bank. I used the feature LP_NetPrincipalLoss to create a subset of the Prosper data set.


## Summary of Findings

>The score dsitribution is bell shaped, with most customers scoring at the middle of the distribution and very few customers at the lower and upper tails. 

>LP_NetPrincipalLoss is strongly correlated with Original Loan amount. 

>Wedding loans and business loans carry large loss amounts when they default.

>The longer the term of the loan the higher the loss amount.(LP_NetPrincipalLoss).

>The Loss amount increases with the Risk Score.

>In the presentation will show the distribution of Prosper Score,Box plot of Term vs LP_NetPrincipalLoss, violin plot of top 10 listing categories vs LP_NetPrincipalLoss and a pointplot of LP_NetPrincipalLoss vs ProsperScore.


## Key Insights for Presentation

>The loss increases as the score increases. This might help Prosper to focus on revising their lending strategy for higher scoring customers to mitigate the loss for this group. And since the loss amount is correlated with Original Loan amount, they could reduce the amount of credit available for certain groups of borrowers.

>I will only show charts that support the key findings from the exploratory analysis.