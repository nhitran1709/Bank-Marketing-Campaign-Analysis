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
- SQL code
<img width="778" height="130" alt="Image" src="https://github.com/user-attachments/assets/aed3b5c4-6e29-463f-9f24-9e587eceed68" />

- Query results
<img width="558" height="51" alt="Image" src="https://github.com/user-attachments/assets/1d184b11-db72-407a-a21a-8493a1f40f65" />

### Query 02: Calculate average balance on each deposit status
- SQL code
<img width="567" height="129" alt="Image" src="https://github.com/user-attachments/assets/addba27f-1cff-4d0b-9f42-fb5e02e64b45" />

- Query results
<img width="279" height="82" alt="Image" src="https://github.com/user-attachments/assets/423fb5c0-dd51-4b2c-a9a6-50e38b665ae9" />

### Query 03: Divide balance into 6 groups and calculate total customers, total customers of having deposit and percentage of total customers of having deposit on total customers of dataset
- SQL code
<img width="715" height="418" alt="Image" src="https://github.com/user-attachments/assets/374034fd-8b94-4559-97a6-48986821e43a" />

- Query results
<img width="634" height="188" alt="Image" src="https://github.com/user-attachments/assets/6d7bc341-d69e-483f-86cf-deaea5a18347" />

### Query 04: Calculate average balance based on every job titles, following by total customers having loan and housing debts
- SQL code
<img width="583" height="165" alt="Image" src="https://github.com/user-attachments/assets/ff712e86-2212-4d73-9275-c5e908ad1aa1" />

- Query results
<img width="633" height="352" alt="Image" src="https://github.com/user-attachments/assets/8f47ffef-b851-4341-9ec9-4ad4c4ccddfd" />

### Query 05: Calculate total customers of having deposit and percentage of total customers of having deposit on total customers of dataset based on job titles
- SQL code
<img width="693" height="301" alt="Image" src="https://github.com/user-attachments/assets/d99ed0ee-1bf6-4f13-8fa0-051ac9b41860" />

- Query results
<img width="686" height="352" alt="Image" src="https://github.com/user-attachments/assets/fe5d1eb2-4e2f-4189-9378-09f6657555c3" />

### Query 06: Divide age into 3 groups and calculate total customers, total customers of having deposit and percentage of total customers of having deposit on total customers of dataset
- SQL code
<img width="673" height="225" alt="Image" src="https://github.com/user-attachments/assets/a7bf2fe1-8bc4-4995-b582-bebe8db83676" />

- Query results
<img width="635" height="111" alt="Image" src="https://github.com/user-attachments/assets/0d5ee908-ef6c-4dc5-b694-1e23ebbf2b63" />

### Query 07: Calculate total customers, total customer having deposit and proportion of them on each marital status
- SQL code
<img width="690" height="149" alt="Image" src="https://github.com/user-attachments/assets/2927daf9-b8e2-4d4c-a00f-15369fef30f6" />

- Query results
<img width="633" height="111" alt="Image" src="https://github.com/user-attachments/assets/a5133421-9589-448b-8dd5-d62fece2f547" />

### Query 08: Calculate success calling rate by month
- SQL code
<img width="701" height="177" alt="Image" src="https://github.com/user-attachments/assets/07ce796d-b094-4fdc-8df9-afffaaa1138b" />

- Query results
<img width="634" height="356" alt="Image" src="https://github.com/user-attachments/assets/9e0d45ce-4687-4d73-9ebf-3df27b43a3ef" />

## V. Business Insights
- *Retired, self_employed* customers have the *highest average balance* (≈2417, ≈1865 respectively) but a moderate deposit rate (4.62%, 1.68% respectively).
  
- Although students have the smallest customer count, their deposit rate (2.41%) relative to base size is promising — when combined with the *Under 30 age group*, which has the *highest deposit* rate (59.83%), it shows strong potential for future long-term customers.
  
- The largest customer segment falls within the *0–20K balance range*, accounting for *over 80%* of total customers (9,643 out of 11,162).
  
- The 30–50 age group forms the majority (7140 customers) but has the lowest deposit rate (42.69%) => This indicates a key segment that should be re-targeted with tailored offers or incentives.
  
- *Blue-collar, technician, and admin* roles show high housing loan counts, yet lower average balances, implying a strong loan dependency — these customers may prioritize debt repayment over deposits.

## VI. Recommendations
- Target Retired and Over-50 Customers for Premium Deposits
  - Develop specialized “Retirement Savings” or “Wealth Stability” deposit products, leveraging their high balances and financial maturity.
  - Use personalized advisory services to convert savings into deposits.
    
- Engage the 30–50 Segment with Mid-term Incentives
  - Offer flexible-term deposits or interest bonuses tied to account tenure to re-engage this large but passive group.
  - Use cross-selling (insurance, investment funds) to strengthen their long-term commitment.
    
- Educate and Nurture Blue-Collar and Technician Segments
  - Launch financial literacy campaigns to increase awareness of deposit benefits.
  - Introduce micro-deposit options or salary-linked savings programs with automatic transfers.

- Capture Young Customer Loyalty Early
  - Design student and young professional deposit accounts with low barriers, gamified savings, and mobile-first onboarding.
  - Encourage early deposit behavior to build long-term brand loyalty.



