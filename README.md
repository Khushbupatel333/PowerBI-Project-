# HDFC Bank Data Analysis: PowerBI Dashboard
![Bank](https://github.com/user-attachments/assets/4ebf76cd-02e8-4613-84d3-542ea2402abb)


# Objective :
Your task is to employ Power BI to analyze these banking datasets, aiming to unravel the intricate patterns and behaviors within the data. This involves in-depth data cleaning, robust data modeling, and strategic use of DAX for complex analytics. Your goal is to create a comprehensive, interactive dashboard that not only illustrates transactional trends and customer profiles but also offers a holistic view of the banking ecosystem. This analysis should include understanding customer transaction behaviors, identifying relationships between account characteristics and financial health, and exploring factors influencing credit scores and loan management. Your insights will guide FinInsight Group in advising banking institutions on optimizing their services, enhancing customer satisfaction, and managing financial risks effectively.

# DataSet : 
There are two datasets in this project- 
## BankingDataset1 : -
TransactionID: A unique identifier for each transaction. 

AccountNumber: The account number associated with the transaction. (Foreign Key)

TransactionType: The type of transaction (e.g., Transfer, Deposit, Withdrawal, Payment).

Amount: The amount of money involved in the transaction.

TransactionDate: The date when the transaction occurred.

BranchCode: The code of the bank branch where the transaction took place.

Currency: The currency in which the transaction was made.

TransactionTime: The time of day when the transaction occurred (in hours).

## BankingDataset2 : -
AccountNumber: A unique identifier for each account, corresponding to 'AccountNumber' in "BankingDataset1.xlsx". (Primary Key)

AccountHolder: The name of the account holder.

AccountType: The type of account (e.g., Credit, Loan, Checking).

Balance: The current balance of the account.

InterestRate: The interest rate applicable to the account.

CreditScore: The credit score of the account holder.

OpeningDate: The date when the account was opened.

LoanAmount: The amount of loan associated with the account (if applicable).

AccountHolderDetails: Details about account holders - employment sector, years at current residence, and city of residence etc.

# Data Preprocessing : -
Imported both datasets into Power BI and performed an initial review to identify data quality issues or inconsistencies. Merge the datasets on the AccountNumber column, ensuring accurate integration and completeness of data. Address any missing values, duplicate entries, and irrelevant data points to maintain data integrity. Converted  columns to appropriate formats and made calculation using new measure function. Utilized diffrent DAX quries to get new data for graphs and tables.

# Outcome :- 
- Developed dynamic interactive dashboard to illustrate transactional trdes,customer profile and historic view of banking ecosystem.

- Added diffrent slicers to show the data in proper manner.I used slicer on AccountType and BranchCode columns to show the data based on diffrent AccountType and BranchCode.

- Used variour charts and graphs including pie charts ,bar charts ,scatter plots and line charts,after utilizing this all graphs I noticed the diffrent aspect of data.

# Dashboards :
![Dashboard2_Image](https://github.com/user-attachments/assets/2151e3b9-870c-44f0-bba6-343c95731b34)











