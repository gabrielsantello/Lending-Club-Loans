# Lending Club Loan Default Prediction Dataset

## Overview
This dataset aims to predict whether a loan will default using historical data from 2007 to 2015. For companies like Lending Club, accurate loan default prediction is crucial. Here's a summary of the dataset:

- **Problem Statement**: Predict the likelihood of loan default for future loans.
- **Data Source**: Historical records from LendingClub.com.
- **Challenges**: The dataset is highly imbalanced and contains several features.

## Data Description
The dataset includes the following columns:

1. **credit.policy**: Binary (1 or 0) indicating whether the customer meets LendingClub.com's credit underwriting criteria.
2. **purpose**: The purpose of the loan (e.g., "credit_card," "debt_consolidation," "educational," etc.).
3. **int.rate**: The interest rate of the loan (stored as a proportion).
4. **installment**: Monthly installments owed by the borrower if the loan is funded.
5. **log.annual.inc**: Natural log of the self-reported annual income of the borrower.
6. **dti**: Debt-to-income ratio (amount of debt divided by annual income).
7. **fico**: FICO credit score of the borrower.
8. **days.with.cr.line**: Number of days the borrower has had a credit line.
9. **revol.bal**: Borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
10. **revol.util**: Borrower's revolving line utilization rate (credit line used relative to total credit available).
11. **inq.last.6mths**: Borrower's number of inquiries by creditors in the last 6 months.
12. **delinq.2yrs**: Number of times the borrower was 30+ days past due on a payment in the past 2 years.
13. **pub.rec**: Borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

## Exploration Ideas
Here are some exploration ideas to guide your analysis:

1. **Imbalanced Data**: Address the class imbalance issue due to loan defaults being rare.
2. **Feature Importance**: Determine which features are most relevant for predicting defaults.
3. **Model Selection**: Experiment with different machine learning models to find the best fit.

---

**Dataset Source**: [Kaggle](https://www.kaggle.com/datasets/urstrulyvikas/lending-club-loan-data-analysis) .
