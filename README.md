# Credit-risk-modeling-for-LendingClub
Created a credit-risk model and computed the expected loss for LendingClub in Python that enables one to compute the expected loss and helps decide whether a borrower should be granted a loan or not.

What is credit risk ?
It is the risk of borrower not repaying loan, credit card or any other type of loan. For example, if a borrower took a personal loan of $ 100,000 for 10 years at 9% interest rate and paid a few initial installments of loan to the bank but stopped paying afterwards, the remaining unpaid installments are worth $ 30,000 which is a loss to the bank.
Why is it important to identify such Non-Performing assets ? It is because, lending money to such borrowers may lead to huge financial crisis such as the recession of 2008. 

Thus, credit-risk modeling is used to compute the expected loss which is given by

EL = PD * LGD * EAD

where,
EL - Expected Loss
PD - Probability of Default
LGD - Loss Given Default and
EAD - Exposure at Default.

The steps undertaken to create the dredit-risk model are as follows -

Step 01 - Compute the probability of default for each of the potential borrowers 
Step 02 - Compute the loss given default
Step 03 - Compute the exposure at default
Step 04 - Multiply them and find a cumulative sum of expected loss for all the potential borrowers

This approach is called the Internal Ratings Based (IRB) approach and is widely used by financial institutions to create their own risk models.
