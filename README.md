# BankSim Fraud Analysis Dashboard

An interactive Power BI report exploring transaction patterns and 
flagged fraud in the simulated BankSim dataset.

## Dashboard pages

- **Overview:** Key metrics, fraud by merchant category, fraud rates, 
and fraudulent transaction amount by simulation day.
- **Category Detail:** Filter a category to examine its transactions, 
fraud rate, and merchants.
- **Merchant Analysis:** Compare merchants by fraudulent transactions, 
fraud rate, and fraudulent transaction amount.

## Key findings

- The dataset contains **594,643 transactions**, including
 **7,200 flagged as fraud** (**1.21%**).
- **Sportsandtoys** has the highest number of flagged 
fraudulent transactions.
- **Leisure** has the highest fraud rate: **474 of 499 
transactions (94.99%)**.
- Merchant **M480139044** has the highest fraud count, 
with **1,634 flagged transactions out of 3,508 (46.58%)**.

## Tools and methods

Power BI Desktop, Power Query for category cleanup, and
 DAX measures for transaction counts, fraud rate, and 
fraudulent transaction amount.
 Slicers and page navigation make the report interactive.

## Files

- `BankSim_Fraud_Dashboard.pbix` — interactive Power BI report
- `Overview.png`, `Category_Detail.png`, `Merchant_Analysis.png` — page screenshots

**Data note:** BankSim is simulated data. The findings describe 
this dataset and should not be interpreted as real-world fraud rates. 
Transaction amount is not labeled as financial loss.
