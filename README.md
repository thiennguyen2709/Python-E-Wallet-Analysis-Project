# Python e-Wallet Analysis Project
### **I. Project Assumption**
My company runs business in e-Wallet field. My manager requires more business information such as payment status, transaction volumn of each type,... As a data analyst, I need to analyze and response to him by using:
- Data tables: including 3 data tables:
  + payment_report.csv: Recording monthly payment volume of products
  + product.csv: Saving product information
  + transactions.csv: Recording transactions information
- Tool: Google Colab
### **II. Project Objectives**
1. Exploratory Data Analysis: Standardize data by finding and solving duplicates, missing value, data type error
2. Data Wrangling: Use datasets to meet some requirements:
- Top 3 product_ids with the highest volume.
- Given that 1 product_id is only owed by 1 team, are there any abnormal products against this rule?
- Find the team has had the lowest performance (lowest volume) since Q2.2023. Find the category that contributes the least to that team.
- Find the contribution of source_ids of refund transactions (payment_group = ‘refund’), what is the source_id with the highest contribution?
- Define type of transactions (‘transaction_type’) for each row
- Of each transaction type (excluding invalid transactions): find the number of transactions, volume, senders and receivers
### **III. Project Execution Steps**
_**1. Import datasets and nescessary library**_

![image](https://github.com/user-attachments/assets/72f048ba-7068-431d-9128-32a3528f66db)

_**2. Exploratory Data Analysis**_

![image](https://github.com/user-attachments/assets/b24942eb-49da-4f3c-88e8-330590414e2a)

![image](https://github.com/user-attachments/assets/d8414727-7b7b-44e6-ac30-a2a115babf57)

_**3. Data Wrangling**_

![image](https://github.com/user-attachments/assets/6144b551-92b3-4153-b931-d2e2be69a91b)

![image](https://github.com/user-attachments/assets/8589562d-7a12-4137-9a07-96f17e4611cf)

![image](https://github.com/user-attachments/assets/8171d1e5-df24-4e25-880b-5b60504de2a0)

![image](https://github.com/user-attachments/assets/da6c3d3e-dbc0-4bbe-b899-ed819e6a1a98)
