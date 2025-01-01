# Loan-Application-Risk-Prediction-Data-
Predicting Loan Success: Credit Insights for Smarter Decisions

### About Dataset
This dataset tells the story of people applying for loans in 2020, with some getting approved and others rejected. Many applied for loans to buy cars, start businesses, or handle emergencies. Full-time workers had better chances of getting loans, especially for smaller amounts. Some applicants, like a part-time worker who wanted $6,000 for a caravan, were lucky and got approved, while others, even with steady jobs, were rejected. The data shows how financial decisions affect people’s plans and dreams.

### **The dataset includes**:
`loan_applications.csv`: Sample loan applications with success/rejection labels.<br>
`credit_features_subset.csv`: Credit file details associated with applicants.<br>
`loan_data_dictionary.csv`: Data dictionary explaining feature columns.<br>

### credit_features_subset:
Here’s a detailed explanation of each columns in the credit_features_subset.csv <br>

`UID` : This is a unique identifier for each loan applicant. Each row has a different UID.<br>
`ALL_AgeOfOldestAccount`: The age of the applicant's oldest credit account in months. It indicates how long they have had their oldest account.<br>
`ALL_AgeOfYoungestAccount`: The age (in months) of the most recently opened account. It shows how recent the applicant's newest credit account is.<br>
`ALL_Count`: Total number of credit accounts the applicant has. This includes all types of accounts.<br>
`ALL_CountActive`: The number of active credit accounts the applicant currently holds.<br>
`ALL_CountClosedLast12Months`: Number of accounts the applicant closed in the past 12 months. This can indicate changes in their financial situation.<br>
`ALL_CountDefaultAccounts`: The number of accounts where the applicant has defaulted (failed to make payments). A higher number suggests higher credit risk.<br>
`ALL_CountOpenedLast12Months`: Number of accounts opened by the applicant in the last 12 months. Many new accounts could indicate credit-seeking behavior, which might be a risk factor.<br>
`ALL_CountSettled`: The number of accounts the applicant has settled (fully paid off). A higher number could indicate responsible behavior.<br>
`ALL_MeanAccountAge`: The average age of the applicant's credit accounts in months. It shows how well-established their credit history is.<br>
`ALL_SumCurrentOutstandingBal`: Total current outstanding balance across all accounts, including mortgages. This is how much the applicant still owes.<br>
`ALL_SumCurrentOutstandingBalExcMtg`: The total outstanding balance excluding mortgages. This focuses on other debts like personal loans, credit cards, etc.<br>
`ALL_TimeSinceMostRecentDefault`: Time (in months) since the applicant’s most recent default. -1 typically means no default history.<br>
**Example**: -1 (no defaults), 13 months since the last default.<br>

`ALL_WorstPaymentStatusActiveAccounts`: This represents the worst payment status across active accounts (e.g., missed payments). Higher values suggest worse payment behavior, with 0 meaning no missed payments and higher values indicating varying levels of delinquencies.<br>
**Example**: 7 (severe payment problems), 0 (no missed payments).


### Loan_Applications Datasets:
Here’s a detailed explanation of each columns in the loan_applications.csv <br>
`UID`: A unique identifier for each loan application.<br>
`ApplicationDate`: The date the loan application was submitted.<br>
`Amount`: The loan amount requested by the applicant.<br>
`Term`: The loan term, typically in months.<br>
`EmploymentType`: The employment status of the applicant (e.g., Employed full-time, Self-employed, Employed part-time).<br>
`LoanPurpose`: The reason the applicant is requesting the loan (e.g., Car, New car, Car repairs, Unexpected bills, etc.).<br>
`Success`: A binary indicator where:<br>
0 = Loan application was rejected.<br>
1 = Loan application was approved.<br><br>
    #### Key Observations of loan_applications.csv:<br>
    - The dataset has loan applications submitted by various applicants.<br>
    - The success of the loan application is indicated in the Success column.<br>
    - There is a mix of employment types (full-time, self-employed, part-time) and loan purposes (mostly car-related).<br>
    - The loan amounts and terms vary, allowing for analysis of how these factors impact loan success.<br>
