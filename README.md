# DSA3050A_MidSem_Hana_670555

## Business Intelligence Project using Microsoft Power BI

---

# Student Information

| Item              | Details                          |
| ----------------- | -------------------------------- |
| **Student Name**  | Hana Gashaw                      |
| **Student ID**    | 670555                           |
| **Course**        | DSA3050A – Business Intelligence |
| **Assessment**    | Mid-Semester Examination         |
| **Software Used** | Microsoft Power BI Desktop       |

---

# Table of Contents

1. Project Overview
2. Dataset Information
3. Dataset Schema
4. Power Query Data Preparation
5. Output of the Data Preparation
6. Dashboard Development
7. Dashboard Interactivity & Business Insights
8. Folder Structure
9. Screenshots Included
10. Software Used
11. Limitations
12. Reflection & Lessons Learned
13. Academic Integrity Statement
14. License
15. Collaboration

---

## Project Overview

This repository contains the complete submission for the **DSA3050A Mid-Semester Business Intelligence Examination**. The project demonstrates an end-to-end Business Intelligence workflow using Microsoft Power BI, from data preparation and transformation to interactive dashboard development and business insight generation.

The project is organized into three main sections:

* **Power Query Data Preparation**
* **Dashboard Development**
* **Dashboard Interactivity & Business Insights**

---

# Dataset Information

## Dataset Name

**Brazilian E-Commerce Public Dataset by Olist**

## Dataset Source

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset was obtained from Kaggle and contains historical Brazilian e-commerce transactions including customer information, orders, sellers, products, payments, product categories, customer reviews, and geographical data.

No AI-generated, fabricated, synthetic, or manually created records were added to the dataset.

---

# Dataset Files Used

The project integrates the following relational tables from the Brazilian E-Commerce Public Dataset by Olist.

| Table                        |      Rows | Columns |
| ---------------------------- | --------: | ------: |
| Customers                    |    99,441 |       5 |
| Orders                       |    99,441 |       8 |
| Order Items                  |   112,650 |       7 |
| Order Payments               |   103,886 |       5 |
| Order Reviews                |    99,224 |       7 |
| Products                     |    32,951 |       9 |
| Sellers                      |     3,095 |       4 |
| Product Category Translation |        71 |       2 |
| Geolocation                  | 1,000,163 |       5 |

These relational tables were connected through common keys and integrated into a unified analytical dataset to support business intelligence reporting and dashboard development.

---

# Dataset Schema

The following Entity Relationship Diagram (ERD) illustrates the relationships among the imported tables used throughout this project.

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Datasets/Schema_of_the_tables.jpeg" width="900"/>
</p>

---

# Final Analytical Dataset

# **FINAL ANALYTICAL TABLE**

## **Rows:** **99,441**

## **Columns:** **35**

The cleaned and transformed datasets were successfully merged into a single **Final Analytical Table** consisting of **35 columns** and **99,441 rows**. This consolidated dataset served as the primary data source for all dashboard visualizations, business analyses, and insights presented in this project.

The following column profile confirms the structure of the final analytical dataset after all Power Query transformations and merge operations.

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Screenshots/Column%20Profile/Profile_Final_Analytical_Table.png" width="900"/>
</p>

---

---

# Section 1 — Power Query Data Preparation

The imported datasets underwent extensive cleaning and transformation in Power Query to improve data quality, ensure consistency, and prepare the data for analysis.

---

## A. Basic Data Cleaning

* Renamed unclear column names
* Corrected data types
* Removed duplicate records where appropriate
* Removed blank rows
* Trimmed and cleaned text columns
* Replaced inconsistent values
* Removed unnecessary columns

---

## B. Intermediate Transformations

* Split date and time columns
* Merged multiple datasets into one analytical table
* Created custom columns (e.g., Delivery Days)
* Created conditional columns
* Extracted Year, Month, Quarter, and Day
* Applied filtering using multiple conditions
* Sorted data meaningfully
* Added an Index column

---

## C. Advanced Power Query Tasks

* Merge Queries using common keys
* Create a Date Table
* Create a summarized Reference Query
* Group By with multiple aggregations
* Use Column Profiling to identify data quality issues

---

# Output of the Power Query Preparation

## Final Analytical Table

After completing all cleaning and transformation tasks, the individual datasets were integrated into a single **Final Analytical Table**.

This analytical table combines customer, order, payment, seller, review, and product information into one consolidated dataset optimized for reporting, dashboard development, and business analysis.

---

# Section 2 — Dashboard Development

An interactive Power BI dashboard was developed to provide meaningful business insights across multiple operational and financial dimensions.

The dashboard focuses on:

* Revenue Distribution
* Order Volume
* Customer Geographic Distribution
* Payment Methods
* Delivery Performance
* Customer Satisfaction

---

## Dashboard Preview

### Dashboard Page 1

```text
Placeholder: dashboard_page1.png
```

---

### Dashboard Page 2

```text
Placeholder: dashboard_page2.png
```

---

# Section 3 — Dashboard Interactivity & Business Insights

The dashboard includes interactive slicers, filters, drill-down functionality, and cross-visual interactions, enabling users to explore the dataset across different business dimensions and make data-driven decisions.

---

## Key Business Insight 1

### Revenue is Highly Concentrated in São Paulo

São Paulo (SP) generates the largest share of both revenue and order volume, producing approximately four times more orders than the second-largest state.

### Recommendation

Increase warehousing capacity, logistics infrastructure, and seller recruitment in São Paulo while investing in growth initiatives within RJ and MG to reduce dependency on a single market.

---

## Key Business Insight 2

### Credit Card Dominates Customer Payments

Credit card transactions contribute approximately **79%** of the total payment value, making it the platform's primary payment channel.

### Recommendation

Continue optimizing the credit card checkout experience while encouraging greater adoption of faster digital payment alternatives among boleto users to improve operational efficiency and cash flow.

---

## Key Business Insight 3

### Customer Satisfaction Remains High

Despite relatively slow delivery performance for many orders, the average customer review score remains above **4 out of 5**, indicating strong overall customer satisfaction.

### Recommendation

Improve delivery turnaround times for slower shipments to further increase customer satisfaction and reduce the occurrence of low-rated customer reviews.

---

# Folder Structure

```text
DSA3050A_MidSem_HanaGashaw_670555
│
├── Dataset
│
├── PBIX
│
├── Screenshots
│
├── README.md
│
└── Insights.pdf
```

---

# Screenshots Included

The submission contains screenshots demonstrating the complete project workflow.

* Raw Imported Dataset
* Power Query Editor
* Applied Steps
* Column Profiling
* Final Cleaned Dataset
* Advanced Power Query Tasks
* Dashboard Pages

---

# Software Used

* Microsoft Power BI Desktop

---

# Limitations

* The analysis is based solely on the publicly available Olist dataset and reflects historical transactions.
* Some product attributes contained missing values that may affect certain product-level analyses.
* Geolocation information was not incorporated into the final analytical model to maintain project scope and improve performance.
* Findings represent the available dataset and should not be generalized beyond the covered period.

---

# Reflection & Lessons Learned

This project strengthened my understanding of the complete Business Intelligence lifecycle, from raw data preparation to interactive dashboard development. I gained practical experience in using Power Query for data cleaning, transformation, query merging, and analytical modeling.

Additionally, I developed a deeper appreciation for the importance of data quality, effective dashboard design, and transforming raw business data into actionable insights that support strategic decision-making.

---

# Academic Integrity Statement

This project was completed using a publicly available dataset obtained from Kaggle. All data preparation, transformation, visualization, dashboard development, and analysis were performed using Microsoft Power BI.

No AI-generated, fabricated, synthetic, or artificially created datasets were used in this project.

---

# License

This project is released under the **MIT License**.

---

# Collaboration

Contributions, suggestions, and constructive feedback are welcome.

If you have ideas for improving the dashboard, enhancing the analytical model, or extending the business insights, feel free to fork the project or open a pull request.

Thank you for taking the time to review this project.

