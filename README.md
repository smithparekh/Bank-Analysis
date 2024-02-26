Czechoslovakia Banking Financial Data Analysis
Introduction
The Czechoslovakia Bank has generously provided a comprehensive dataset encompassing its financial activities over the past five years. The dataset comprises several tables, each offering valuable insights into different aspects of the bank's operations.

Tables Overview
Account:

Contains information about the accounts held by the bank's clients.
Fields: Account ID, Date of Account Opening, Client ID, Account Type.
Card:

Includes information about the cards issued by the bank.
Fields: Card ID, Date of Card Issuance, Card Type.
Client:

Provides details about the bank's clients.
Fields: Client ID, Birthdate, Gender, District of Residence.
Disposition:

Describes the relationship between clients and their accounts.
Fields: Disposition ID, Client ID, Disposition Type (e.g., owner, authorized person).
District:

Offers information about various districts in Czechoslovakia.
Fields: District ID, District Name, Demographic and Economic Indicators.
Loan:

Contains data about the loans issued by the bank.
Fields: Loan ID, Date of Loan Issuance, Associated Account ID, Loan Amount.
Order:

Holds information on orders issued by the bank's clients.
Fields: Order ID, Associated Account ID, Date of Issuance, Order Description.
Transaction:

Provides insights into transactions made by the bank's clients.
Fields: Transaction ID, Associated Account ID, Transaction Date, Transaction Type, Transaction Amount.
Repository Structure
Data: This directory contains the raw dataset provided by the Czechoslovakia Bank.

Analysis: Base in SQL snowflake 

Visualizations: Find visual representations of data insights in this directory.

How to Use
If you're interested in exploring the financial data or replicating the analyses:

Clone the repository to your local machine.
Navigate to the 'Analysis' directory to find the scripts.
Use the provided Jupyter notebooks or Python scripts to run analyses.
Feel free to contribute, report issues, or suggest improvements. Happy analyzing!

