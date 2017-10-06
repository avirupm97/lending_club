The data is publicly available data from LendingClub.com.

About: Since 2007, the company has been bringing borrowers and investors together, transforming the way people access credit. Over the last 10 years, they have helped millions of people take control of their debt, grow their small businesses, and invest for the future.

Columns representation:

1. credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
2. int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com      to be more risky are assigned higher interest rates.
3. installment: The monthly installments owed by the borrower if the loan is funded.
4. dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).
5. fico: The FICO credit score of the borrower.
6. days.with.cr.line: The number of days the borrower has had a credit line.
7. revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
8. revol.util: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
9. inq.last.6mths: The borrower's number of inquiries by creditors in the last 6 months.
10. delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
11. pub.rec: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).
12. purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business",      and "all_other").
13. log.annual.inc: The natural log of the self-reported annual income of the borrower.

Consider the following columns and apply the algorithms in accordance to column: not.fully.paid, 1:True, 0:False
