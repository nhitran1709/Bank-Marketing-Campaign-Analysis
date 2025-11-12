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
<img width="948" height="76" alt="Image" src="https://github.com/user-attachments/assets/4712ced2-f425-46bf-aa51-858d325c382f" />

- Query results
<img width="1194" height="297" alt="Image" src="https://github.com/user-attachments/assets/645e55b0-f1b7-4032-950b-95ce9df6db95" />

- Query code
<img width="969" height="77" alt="Image" src="https://github.com/user-attachments/assets/04c51de1-2d24-4997-8515-d0bf61de9d21" />

- Query results
<img width="184" height="54" alt="Image" src="https://github.com/user-attachments/assets/5f1820bf-a18b-4426-8d78-dbf1253b33ee" />

- Query code
<img width="747" height="141" alt="Image" src="https://github.com/user-attachments/assets/033ece3f-144c-4418-bd90-8e530babdbef" />

- Query results
<img width="556" height="56" alt="Image" src="https://github.com/user-attachments/assets/9b16d06f-c50b-4e1e-ba06-73f392e9f646" />

- Query code
<img width="1159" height="180" alt="Image" src="https://github.com/user-attachments/assets/e23e7e9f-a041-4a07-bd3e-467e1af0a3d1" />

- Query results
<img width="261" height="64" alt="Image" src="https://github.com/user-attachments/assets/ffbf032d-c8cf-4581-b15c-31c07a42bcf8" />

## IV. Exploratory Data Analysis (EDA)
In this project, I will write 08 queries in BigQuery based on the Kaggle dataset.

### Query 01: Calculate total of customers, average balance, default rate and deposit rate
SQL code

Query results

### Query 02: Calculate average balance on each deposit status
SQL code

Query results






