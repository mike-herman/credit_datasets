# Loan Datasets

This repo contains information about various publicly available datasets that pertain to lending, loans, or credit risk.

I am not including the dataset files in this repo, but I will point to URLs or an S3 bucket where the data can be downloaded.

# TVS Loan Default Data

Source: [Kaggle](https://www.kaggle.com/datasets/sjleshrac/tvs-loan-default)
Dowload URL: https://mikes-junk-drawer.s3.us-east-2.amazonaws.com/TVS.csv
Credit Products: Personal Loans

Details: Personal Loan product is an unsecured loan therefore it is vital to assess the risk of the customers by checking their credit worthiness. This must be done to prevent loan defaults.

Fields:

- V1: Customer ID
- V2: Customer has bounced in first EMI
- V3: No of times bounced 12 months
- V4: Maximum MOB
- V5: No of times bounced while repaying the loan
- V6: EMI
- V7: Loan Amount
- V8: Tenure
- V9: Dealer codes from where customer has purchased the Two wheeler
- V10: Product code of Two wheeler
- V11: No of advance EMI paid
- V12: Rate of interest
- V13: Gender
- V14: Employment type
- V15: Resident type of customer
- V16: Date of birth
- V17: Customer age when loanwas taken
- V18: No of loans
- V19: No of secured loans
- V20: No of unsecured loans
- V21: Max amount sanctioned in the Live loans
- V22: No of new loans in last 3 months
- V23: Total sanctioned amount in the secured Loans which are Live
- V24: Total sanctioned amount in the unsecured Loans which are Live
- V25: Maximum amount sanctioned for any Two wheeler loan
- V26: Time since last Personal loan taken (in months)
- V27: Time since first consumer durables loan taken (in months)
- V28: No of times 30 days past due in last 6 months
- V29: No of times 60 days past due in last 6 months
- V30: No of times 90 days past due in last 3 months
- V31: Tier
- V32: Target variable

# Bondora Peer-to-peer Lending Data

Source: [IEEE Data Port](https://ieee-dataport.org/open-access/bondora-peer-peer-lending-data)
Download URL: https://mikes-junk-drawer.s3.us-east-2.amazonaws.com/Bondora_raw.csv
Credit Products: Personal Loans, Peer-to-peer

Details: Data for the study has been retrieved from a publicly available data set of a leading European P2P lending platform, Bondora (https://www.bondora.com/en). The retrieved data is a pool of both defaulted and non-defaulted loans from the time period between 1st March 2009 and 27th January 2020. The data comprises demographic and financial information of borrowers and loan transactions. In P2P lending, loans are typically uncollateralized and lenders seek higher returns as compensation for the financial risk they take. In addition, they need to make decisions under information asymmetry that works in favor of the borrowers. In order to make rational decisions, lenders want to minimize the risk of default of each lending decision and realize the return that compensates for the risk. As in the financial research domain, there are very few datasets available that can be utilized for building and analyzing credit risk models. This dataset will help the research community in building and performing research in the credit risk domain.
