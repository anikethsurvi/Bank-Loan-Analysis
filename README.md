OBJECTIVE - 
As a data analyst for a bank, analyze the loan portfolio performance and provide insights on:
•	Loan Portfolio Health 
•	Application Trends 
•	Loan Purpose Distribution 
•	Risk Metrics 
•	Portfolio Growth 

DOMAIN KNOWLEDGE -
How Banks Operate in Lending 
1.	Primary Function: Financial Intermediation
o	Banks serve as intermediaries, taking money from depositors (savings accounts, fixed deposits) and lending it to borrowers (personal loans, home loans, etc.).
o	Banks earn money through the spread: the difference between the interest they pay depositors and the interest they charge borrowers.
Money Inflow (Revenue Sources):
1.	Interest Payments from Loans:
o	Borrowers pay interest on the principal loan amount, which forms the primary income for banks. For example:
	A loan of $10,000 at a 12% interest rate generates $1,200 annually in interest.

2.	Loan Origination Fees:
o	Banks charge a processing fee when loans are approved. This fee is often a percentage of the loan amount.
3.	Penalties on Late Payments:
o	Borrowers failing to pay installments on time incur late payment charges, adding to the bank's revenue.
4.	Income from Investments:
o	Banks invest surplus funds in government securities, bonds, and financial instruments to generate interest income.
Money Outflow (Expenses):
1.	Interest Paid to Depositors:
o	Banks pay interest on savings accounts, fixed deposits, and other deposit schemes. This is their primary cost.
2.	Loan Defaults:
o	When borrowers fail to repay (charged-off loans), banks incur losses. These are classified as Non-Performing Assets (NPAs).
3.	Operational Costs:
o	Salaries, branch maintenance, technology upgrades, etc., form part of the bank's expenses.
4.	Cost of Borrowing:
o	Banks sometimes borrow money from central banks or other financial institutions to maintain liquidity.


How Lending Works 
1.	Loan Application:
o	Borrowers apply for loans, stating their purpose, income, credit score, and other details.
2.	Credit Assessment:
o	Banks evaluate the creditworthiness of borrowers using their financial history, debt-to-income ratio, and credit score.
o	Loans are graded into categories (A, B, C) to indicate risk levels.
3.	Loan Issuance:
o	Approved loans are disbursed to borrowers. Interest payments begin immediately, often in the form of EMIs (Equated Monthly Installments).
4.	Repayment and Cash Flow:
o	Borrowers repay the loan through installments, which include principal repayment and interest.
o	A portion of the received money is used to cover bank costs, while the rest contributes to profits.



DATA KNOWLEDGE(Dataset) -
1. id: A unique identifier for the loan or borrower.
2. address_state: The state where the borrower resides.
3. application_type: Indicates whether the loan application is individual or joint.
4. emp_length: The borrower’s employment length (e.g., 1 year, 5+ years).
5. emp_title: The borrower’s job title or occupation.
6. grade: A risk grade assigned to the loan, typically based on creditworthiness (e.g., A, B, C).
7. home_ownership: Indicates the borrower’s housing status (e.g., Own, Rent, Mortgage).
8. issue_date: The date the loan was issued.
9. last_credit_pull_date: The most recent date the borrower’s credit profile was reviewed.
10. last_payment_date: The date the borrower made their most recent loan payment.
11. loan_status: Current status of the loan (e.g., Fully Paid, Charged Off, Current).
12. next_payment_date: The scheduled date for the borrower's next loan payment.
13. member_id: A unique identifier for the borrower.
14. purpose: The reason for the loan (e.g., debt consolidation, home improvement).
15. sub_grade: A more granular classification of loan risk (e.g., A1, B2, C3).
16. term: The loan duration, typically in months (e.g., 36 months, 60 months).
17. verification_status: Indicates whether the borrower’s income and identity have been verified.
18. annual_income: The borrower’s reported annual income.
19. dti: Debt-to-Income ratio, measuring the borrower’s monthly debt obligations as a percentage of income.
20. installment: The fixed monthly payment the borrower needs to make.
21. int_rate: The interest rate on the loan.
22. loan_amount: The total amount borrowed.
23. total_acc: The total number of credit accounts the borrower has.
24. total_payment: The total amount paid by the borrower, including principal and interest.


