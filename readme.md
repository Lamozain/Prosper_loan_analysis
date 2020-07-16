# PROSPER LOAN DATASET ANALYSIS
## by Amos Moses Omofaiye (UDACITY DAND SCHOLAR)


## Dataset

> This dataset is on Loan and their outcomes. The loan disbursing organization is Prosper. This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. For this analysis, I focused on the variables below. I believe I was able to demonstrate my skills and came up with useful observations on the loan data.

> The variables are:

<ul>
    <li>Term: The length of the loan expressed in months.</li>
    <li>Loan Status: The current status of the loan: Cancelled,  Chargedoff, Completed, Current, Defaulted, FinalPaymentInProgress, PastDue. The PastDue status will be accompanied by a delinquency bucket.</li>
    <li>BorrowerAPR: The Borrower's Annual Percentage Rate (APR) for the loan.</li>
    <li>ProsperScore: A custom risk score built using historical Prosper data. The score ranges from 1-10, with 10 being the best, or lowest risk score.  Applicable for loans originated after July 2009.</li>
    <li>ListingCategory: The category of the listing that the borrower selected when posting their listing: 0 - Not Available, 1 - Debt Consolidation, 2 - Home Improvement, 3 - Business, 4 - Personal Loan, 5 - Student Use, 6 - Auto, 7- Other, 8 - Baby & Adoption, 9 - Boat, 10 - Cosmetic Procedure, 11 - Engagement Ring, 12 - Green Loans, 13 - Household Expenses, 14 - Large Purchases, 15 - Medical/Dental, 16 - Motorcycle, 17 - RV, 18 - Taxes, 19 - Vacation, 20 - Wedding Loans </li>
    <li>BorrowerState: The two letter abbreviation of the state of the address of the borrower at the time the Listing was created.</li>
    <li>Occupation: The Occupation selected by the Borrower at the time they created the listing.</li>
    <li>EmploymentStatusDuration: The length in months of the employment status at the time the listing was created. </li>
    <li>EmploymentStatus: The employment status of the borrower at the time they posted the listing.</li>
    <li>AvailableBankCardCredit: The total available credit via bank card at the time the credit profile was pulled. </li>
    <li>StatedMonthlyIncome: The monthly income the borrower stated at the time the listing was created.</li>
    <li>LoanNumber: Unique numeric value associated with the loan.</li>
    <li>LoanOriginationQuarter: The quarter in which the loan was originated. </li>
    <li>Recommendations: Number of recommendations the borrower had at the time the listing was created.</li>
</ul>


#### Research Question
> I  explored based on the folowing broad research question:
<ol> 
    <li>What factors affect a loan’s status?</li>
</ol>


## Summary of Findings

> It became clearer that income, bank balance, listing category has a great influence on loan outcome status. Borrowers with higher monthly income has higher card credit, obtains lower category listing loans and have better loan completion status. Generally, higher monthly income tends to encourage favourable loan completion status.

> Moreover Employment Status Duration, Available Bank card Credit and  Recommendation have some relationship. It appears that the higher the employment duration, the higher the stated monthly income and the higher the number of recommendations. The higher the Available Bank card credit, the higher the number of recommendations.

> It is surprising to observe that Employment Status Duration and Available Bank card Credit do not have a linear relationship. Even when transformed, the relationship is very weak. I had expected the two to be strongly correlated.

>  From the various plots, I have observed that Loan Status often term loan outcome status is influenced by a lot of variables in different ways. For favourable loan outcome, such variables as income, bank credit, recommendations, employment status and employment status duration plays a great part. The better these variables are, the better the loan outcome status.


## Key Insights for Presentation

> The key insights are:

- High number of recommendations, available bank credit balance and  employment status encourages favourable loan status.
- Also recommendations, loan term, and listing category also affects loan status.
- I build on these for presentation by polishing up the required plots. I included the axes labels and titles.
