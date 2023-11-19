# Loan-application-analysis

## Business Context
Loan-providing entities often face challenges when extending credit to individuals with limited or nonexistent credit histories. Such situations may lead to increased incidences of defaulters, which some consumers might exploit. Imagine you're part of a finance firm that offers a variety of loans to city dwellers. Your task is to employ EDA techniques to uncover patterns in the data, ensuring that loans are not unjustly withheld from applicants who have the means to honor their debts.

## Loan Decision Risks
When a loan application is received, the firm must make an informed decision based on the applicant's profile. This decision is fraught with two primary risks:

Type I Risk: Declining a loan to an applicant who would have repaid it, leading to a missed revenue opportunity.
Type II Risk: Approving a loan for an applicant prone to defaulting, potentially resulting in a financial write-off.
Data Synopsis
The dataset provided includes details of loan applications at the time of submission. It categorizes applicants into:

Those with repayment issues: marked by delays exceeding X days for at least one of the first Y loan instalments,
Punctual repayments: where all payments are made on time.
Decision Categories
Upon loan application, the following outcomes are possible:

Approved: The loan application has been sanctioned.
Cancelled: The application was withdrawn by the applicant for various reasons, such as a change of mind or unfavorable loan conditions due to high-risk assessments.
Refused: The loan was denied due to the applicant failing to meet the firm's criteria.
Unused offer: The applicant opted not to proceed with the loan after initial acceptance.
Objective of the Case Study
The case study's objective is to discern patterns that suggest difficulties an applicant may have with loan repayments. Such insights could inform decisions like denying a loan, adjusting loan amounts, or offering loans at increased interest rates to high-risk applicants. Identifying such patterns through EDA is the crux of this case study.

In essence, the firm is eager to comprehend the pivotal factors that influence loan defaults. These indicators can then be used for portfolio and risk management strategies.
