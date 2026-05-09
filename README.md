# Insurance-Risk-Fraud-Analytics
### 📊 1.Executive Overview Page  

![Executive_overview](/Executive%20Overview.png)
### ℹ️ 2.Risk & Fraud Analytics page

![Risk & Fraud Analytics](/Risk%20Fraud%20Analytics.png)
### ℹ️ 2.Claims Operations page

![Claims Operations](/Claim%20Operations.png)

## 📌 Project Overview

Insurance companies face challenges in identifying high-risk claims, fraud-prone regions, and operational inefficiencies in claims processing.
This project provides an end-to-end analytics solution to monitor claim performance, fraud trends, settlement efficiency, and customer risk segmentation using Power BI and SQL.

The dashboard was built using **three Excel datasets**:

1. **Dim_Customers.xls** – customer details
2. **Dim_Policy** – Policies brought by customers
3. **Fact_Claims** – all Claim details raised by customer

## 🗂 Data Model

A clean **star schema** was developed consisting of:

* **Fact Table** – Claims
* **Dimension Tables** – Customers, Policies
* Relationships connected using Customer_ID and Policy_ID

  
