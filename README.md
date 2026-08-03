# Finance Analysis Dashboard using Microsoft Fabric

## Project Description

This project demonstrates an end-to-end Finance Analytics solution developed using Microsoft Fabric. The objective is to transform raw financial transaction data into an interactive Power BI dashboard that enables business users to monitor financial performance, transaction activity, customer segments, and revenue trends. The project follows the Medallion Architecture (Bronze, Silver, Gold) for efficient data processing and reporting.

---

## Project Objective

The objective of this project is to provide real-time financial insights that help organizations monitor revenue, transaction fees, taxes, customer segments, and transaction performance for better business decision-making.

---

## Architecture

```
CSV / Excel (Source Data)
        │
        ▼
Lakehouse Files (Bronze Layer)
        │
        ▼
Dataflow Gen2 (Data Cleaning & Transformation)
        │
        ▼
Lakehouse Tables (Silver Layer)
        │
        ▼
Semantic Model
        │
        ▼
Power BI Dashboard (Gold Layer)
```

---

## ETL Process

- Imported finance transaction and customer data into Microsoft Fabric Lakehouse.
- Performed data cleaning and transformation using Dataflow Gen2.
- Loaded transformed data into Lakehouse Tables.
- Created a Semantic Model with relationships and DAX measures.
- Developed an interactive Finance Dashboard in Power BI.

---

## Dashboard Features

### KPIs (Calculated using DAX)

- Total Amount
- Total Fee
- Total Tax
- Total Transactions
- Average Transaction Value

### Interactive Visualizations

- Total Fee by Day
- Transaction Status Analysis
- Customer Segment Analysis
- Total Fee by State
- Transaction Type Analysis
- Dynamic Metric Selection
- Year Filter
- Occupation Filter
- Category Filter

### Interactive Slicers

- Dynamic Metric
- Year
- Occupation
- Category

---

## Business Insights

The dashboard enables users to:

- Monitor total transaction amounts and fees.
- Analyze transaction status (Success, Failed, Pending).
- Compare customer segments.
- Identify top-performing states by transaction fee.
- Analyze transaction types such as Bill Payment, Card Payment, Deposit, Transfer, Loan EMI, Investment, and Refund.
- Track financial performance using dynamic filters.

---

## Skills Demonstrated

- Microsoft Fabric
- Dataflow Gen2
- Lakehouse
- SQL Analytics Endpoint
- Semantic Modeling
- Power BI Dashboard Development
- DAX
- SQL
- Medallion Architecture
- Financial Data Analytics

---

## Project Outcome

Developed an end-to-end Finance Analytics solution using Microsoft Fabric that transforms raw financial transaction data into interactive dashboards, enabling finance teams to monitor KPIs, analyze customer behavior, and support data-driven business decisions.
