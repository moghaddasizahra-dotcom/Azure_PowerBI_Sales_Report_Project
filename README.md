# Azure_PowerBI_Sales_Report_Project
This project showcases skills learned during an Azure Data Fundamentals week, where I explored:

- Relational data in Azure SQL Database
- Non-relational data in Azure Cosmos DB / Storage
- Analytics and reporting using Azure Synapse Analytics and Power BI

Since the virtual machine environment is no longer accessible, this repository focuses on the Power BI Sales Report created during the labs, supported by explanations of the Azure services involved.

---

## **Data Flow:**
```text
 Source Data (Relational + Non-Relational)
                      ↓
 Azure Data Lake Storage (Raw Layer)
                      ↓
 Azure Synapse Analytics (Transform)
                      ↓
 Power BI Desktop (Visualise)
                      ↓
 Sales Analytics Dashboard (Insights)
```
This represents a typical cloud-based data analytics pipeline.

## **Power BI Sales Report**

This repository includes a Sales Report created in Power BI based on the dataset provided during the Azure week exercises.

The report contains visuals such as:

- Revenue by Category
- Quantity by Category
- Revenue by City (Map)
- Basic sales performance insights (relationships, data types, categories)

All visuals are available in:

- **PDF Report:**
  
[Download Sales Report PDF](Lab3%20.%20Sales%20Report.pdf)


- **Screenshot Preview:**

| Sales Report Dashboard |
|------------------------|
| ![](Sales%20Report.jpg) |

---
## Screenshot Preview

<p align="center">
  <img src="Sales%20Report.jpg" width="600">
</p>
---
## **What I Learned:**

Relational Data
- How structured data is stored in Azure SQL
- Tables, relationships, schemas
- Querying using SQL

Non-Relational Data
- How semi-structured data is stored in Azure Storage (Blob, ADLS)
- Basic concepts of NoSQL and Cosmos DB

Analytics in Azure
- Using Synapse Studio to explore and transform data
- Using Power BI to visualise cleaned datasets

## **Tools Used**

- Power BI Desktop
- Azure SQL Database
- Azure Data Lake Storage (Gen2)
- Azure Synapse Analytics
- Virtual Machines (Azure Lab Environment)

  
