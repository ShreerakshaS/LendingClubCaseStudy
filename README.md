
LENDING CLUB CASE STUDY



INTRODUCTION:

Solving this assignment will give you an idea about how real business problems are solved using EDA. 
In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.



TABLE OF CONTENTS:

-Introduction
-Business Understanding
-Business Objective
-Data Understanding 
-Data Analysis(Visual Representation with Insights)
-Conclusion



BUSINESS UNDERSTANDING:

You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile. 
Two types of risks are associated with the bank's decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

When a person applies for a loan, there are two types of decisions that could be taken by the company:
I. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
     1. Fully paid: Applicant has fully paid the loan (the principal and the interest rate).
     2. Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates     are  not labelled as 'defaulted'.
     3. Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.
II. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).



DATA UNDERSTANDING:

This dataset has 2 files as explained below:
1. loan.csv contains all the information of customer's loan application data and their financial history. 
2. Data_Dictionary.xlsx  is a Data Dictionary which describes the meaning of Data variables.



CONCLUSION:

By the end of EDA for loan data set, the key factors influencing the defaulter's rate are as follows:
I. Minor Impact:
   1. Higher loan amount
   2. Higher instalment amount
   3. Lower annual income
   4. Higher debt to income ratio (above 15%)
   5. Applicant's address state (NV, SD, AK, FL, etc.)
   6. Loan issue month (Dec, May, Sep)

II. Heavy impact:
   1. Higher interest rate
   2. Repayment term (60 months)
   3. Loan grade & sub-grade (F to G)
   4. Loan purpose (debt consolidation)



RECOMMENDATIONS:

1. Lending loan to customers with Grades and sub-grades beyond F is of higher risk and thorough verification of documents is required before lending loan.
2. If customer is opting for the Repayment term of 60 months, the risk seems to be higher. However we can ask for some collateral deposit from the customer depending upon the amount of loan he is requesting for , to avoid losses for the Lending club.
3. As the loan amount requested by the customer increases, the chances of him/her becoming defaulter increases. In this case the Lending club can do a thorough verification on the customer's annual income and the properties owned based on which "funded amount" and "funded amount investment" can be decided.
4. If the Home Ownership status is "Other", analysis predicts it be having higher risk rate. So its recommended to investigate further on the property status.
5. Loans taken with purpose mentioned as Debt consolidation possesses higher risk. So, its recommended to partially process the loan amount.
Example: 35-40% of the annual income of customer can be granted as the loan funded amount.
6. If the DTI ratio is high and Annual income is low, it is recommended to reduce the funded amount investment for a particular customer.



Created by [@ShreerakshaS, @ShivaSharaj] - feel free to contact me!
