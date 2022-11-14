# Prosper Loan Dataset

## by Nwokocha Hannah

## Prosper Loan

> This dataset is a financial dataset and is related to the borrowers, lenders, interest rates on different loans. Prosper or Prosper Marketplace Inc. is a San Francisco, California based company specializing in loans at low interest rates to the borrowers. In this dataset, I am analysing data from Prosper database and trying to find the pattern in the Prosper data. This may be tedious because of the sheer size of the dataset and the complicated nature of all the financial datasets. I am using Python, an advanced high level programming language for the analysis with some of its most popular graphic package matplotlib and seaborn.

> The dataset is comprised of 81 variables and contains 113937 entries.

## Summary of Findings

> - The distribution of **BorrowerAPR** looks normal but with a spike in value at around 0.3 - 0.4
> - The **prosper Score**, **Prosper Rating (Alpha)** and **Prosper Rating (Numeric)** are identical, the alpha column is just a alphabetic representation of the numeric column. Rating 4 has the highest frequency. The rating was increasing till it got to 4 then it also steadily decreased from 4.
> - The distribution of **EmploymentStatus** showed that Employed people tend to apply for loan more than others. This may be because of the missing values of those features were filled with their mode but that just implies that they were already leading results in said features.
> - The distribution of **LoanOriginalAmount** is not skewed. Even with a log transformation, there is no change. There is a high frequency with an origination amount of about 4000 - 5000
> - While the distribution of **TotalTrades** was skewed to the right, it still showed that most people tended to have trade lines of between 20 - 25.
> - From the distribution of **Monthly Loan Payment** it can be discovered that most of Prosper monthly loan payment are less than 1,000 ($), which indicates that prosper's services are mainly on personal loans.
> From the relationship between the **Prosper Score** and **Borrower APR**. It shows that:
> - Prosper Score (5) had a wider range of Borrower APR and the lowest Borrower APR of all the Score. 
> - Prosper Score 4 had the highest Borrower APR. 
> - There were a lot of outliers in Prosper Score 1 and it also had the lowest range of Borrower APR.
> - The above visualizations shows the relationship between the **Numeric Prosper Rating** and **Prosper Score** against **Employment Status**. It shows that for every Rating and Score, `Employed` people made up most of the consideration. `Not available` and `Part-time` made up the least except in the Rating `4` and Score `5` where `Full-time` makes the highest consideration and `Not available` also made a considerable portion compared to others.
> - The plot show strong correlation between the **Prosper rating** or **Prosper score** with the  **Borrower Rate**. Generally, borrowers have no clue on their prosper scores.  So these information can not be included in our model.
> - The above visualization shows the relationship between **Prosper Rating** and **Prosper Score**. Each Rating had varying levels of Score but Rating 5 had the highest Score of 4. I also noticed that Scores 8, 9, 10, 11 had no relationhip with the Ratings.
> - The above visualization shows the distribution of **Monthly Loan Payment** for each **Prosper Rating (Alpha)**. It shows that Rating `C` had the most occurence of Monthly Loan Payment.

## Key Insights for Presentation

> - What is the relationship between `ProsperScore` and `ProsperRating`?
> - Does `ProsperScore` influence `BorrowerAPR`?