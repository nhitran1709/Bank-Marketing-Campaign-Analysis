# [SQL] Bank Marketing Campaign Analysis
## I. Project Overview
This project explores a ***Bank Marketing Dataset*** on [Kaggle](https://www.kaggle.com/datasets) to uncover insights into customer behavior and marketing campaign performance.
The goal is to identify what factors influence a customer’s decision to open a deposit account — using SQL for analysis in Google BigQuery.
## II. Dataset Information
- Dataset Source: [*Bank Marketing Dataset*](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset/data)
- Reference: https://www.kaggle.com/code/mlippo/py-business-case-eda/notebook
- Rows: 11,162 | Columns: 17

| Variable Name | Type | Description |
|---|---|---|
| age | INTEGER | age |
| job | STRING | type of job |
| marital | STRING | marital status |
| education | STRING | education level |
| default | BOOLEAN | has credit in default? |
| balance | INTEGER | average yearly balance |
| housing | BOOLEAN | has housing loan? |
| loan | BOOLEAN | has personal loan? |
| contact | STRING | contact communication type |
| duration | INTEGER | last contact duration, in seconds |
| campaign | INTEGER | number of contacts performed during this campaign and for this client |
| pdays | INTEGER | number of days that passed by after the client was last contacted from a previous campaign |
| previous | INTEGER | number of contacts performed before this campaign and for this client |
| poutcome | STRING | outcome of the previous marketing campaign |
| deposit | BOOLEAN | has the client subscribed a term deposit? |
| day | INTEGER | last contact day of the week |
| month | STRING | last contact month of year |

## III. Data Cleaning (SQL)
During this stage, I performed several SQL cleaning steps to ensure data quality and consistency.

- Query code

<img width="491" height="54" alt="Image" src="https://github.com/user-attachments/assets/266f2e15-bd7b-443c-989c-fa168fe67b11" />

- Query results

<img width="1194" height="297" alt="Image" src="https://github.com/user-attachments/assets/99edeb98-cc02-43ca-8409-3ac86febfefb" />


- Query code

<img width="484" height="39" alt="Image" src="https://github.com/user-attachments/assets/a8b664f2-6d11-430e-b531-d47f7be8f147" />

- Query results

<img width="184" height="54" alt="Image" src="https://github.com/user-attachments/assets/8d8e2aa8-aebc-490a-97c1-d4b5f9af784f" />


## IV. Exploratory Data Analysis (EDA)
In this project, I will write 08 queries in BigQuery based on the Kaggle dataset.

### Query 01: Calculate total of customers, average balance, default rate and deposit rate
SQL code

Query results

### Query 02: Calculate average balance on each deposit status
SQL code

Query results






