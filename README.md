# DSA3050A_MidSem_Hana_670555

## Business Intelligence Project using Microsoft Power BI

---

## Student Information

| Item              | Details                          |
| ----------------- | -------------------------------- |
| **Student Name**  | Hana Gashaw                      |
| **Student ID**    | 670555                           |
| **Course**        | DSA3050A – Business Intelligence |
| **Assessment**    | Mid-Semester Examination         |
| **Software Used** | Microsoft Power BI Desktop       |


---
## Repository Structure

```text
DSA3050A_MidSem_Hana_670555/
├── Datasets
│   ├── Schema_of_the_tables.jpeg
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
│
├── Insights
│   └── Insights.pdf
│
├── PBIX
│   └── MidSemExam.pbix
│
├── Screenshots
│   │
│   ├── Raw_Datasets
│   │   ├── Customers.png
│   │   ├── Orders.png
│   │   ├── Order_items.png
│   │   ├── Payments.png
│   │   ├── Order_review.png
│   │   ├── Products.png
│   │   ├── Sellers.png
│   │   ├── Geolocation.png
│   │   └── Category_translation.png
│   │
│   ├── Power_Query_Editor
│   │   └── Powerqueryeditor.png
│   │
│   ├── Applied_Steps
│   │   │
│   │   ├── Applied_Steps_Pane_Multi-table
│   │   │   │
│   │   │   ├── A_Basic_Data_Cleaning
│   │   │   │   ├── former_orders.png
│   │   │   │   ├── geolocation.png
│   │   │   │   ├── customers.png
│   │   │   │   ├── reviews.png
│   │   │   │   ├── payments.png
│   │   │   │   └── products.png
│   │   │   │
│   │   │   ├── B_Intermediate_Transformations
│   │   │   │   ├── former_orders.png
│   │   │   │   ├── sellers.png
│   │   │   │   └── Filter_Analytical_Table.png
│   │   │   │
│   │   │   └── C_Advanced_Power_Query
│   │   │       ├── Merge_Query.png
│   │   │       ├── Date_table.png
│   │   │       ├── Reference_table_summary.png
│   │   │       ├── Group_by.png
│   │   │       └── advanced_queries.png
│   │   │
│   │   └── Question_1_Power_Query_Data_Preparation
│   │       │
│   │       ├── A_Basic_Data_Cleaning
│   │       │   ├── Rename_Unclear_Columns
│   │       │   │   ├── English_name.jpeg
│   │       │   │   ├── Portugeuse_name.jpeg
│   │       │   │   └── Renamed.jpeg
│   │       │   │
│   │       │   ├── Correct_Data_Types
│   │       │   │   ├── Geolocation_zipcode_To_text.jpeg
│   │       │   │   └── Seller_Zipcode_to_text.png
│   │       │   │
│   │       │   ├── Remove_Duplicate_Rows
│   │       │   │   ├── Remove_dup_customers.jpeg
│   │       │   │   └── Remove_dup_sellers.png
│   │       │   │
│   │       │   ├── Remove_Blank_Rows
│   │       │   │   └── Remove_empty_order_review.png
│   │       │   │
│   │       │   ├── Trim_and_Clean_Text
│   │       │   │   ├── RemovefromCustomerCity.jpeg
│   │       │   │   └── Trim_customer_city.jpeg
│   │       │   │
│   │       │   ├── Replace_Inconsistent_Values
│   │       │   │   ├── Replace_inconsistent_product_dimentions.png
│   │       │   │   └── Replace_payment_method_inconsistencies.png
│   │       │   │
│   │       │   └── Remove_Unnecessary_Columns
│   │       │       └── Removed_three_columns.png
│   │       │
│   │       ├── B_Intermediate_Transformations
│   │       │   ├── Split_One_Column_Into_Multiple_Columns
│   │       │   │   └── Split_Purchase_Date.png
│   │       │   │
│   │       │   ├── Merge_Two_or_More_Columns
│   │       │   │   ├── Customer_City+State.png
│   │       │   │   └── Seller_City+State.png
│   │       │   │
│   │       │   ├── Create_Custom_Column
│   │       │   │   └── Delivery_Day.png
│   │       │   │
│   │       │   ├── Create_Conditional_Column
│   │       │   │   └── Delivery_Speed.png
│   │       │   │
│   │       │   ├── Extract_Year_Month_Quarter_Day
│   │       │   │   ├── Purchase_year.png
│   │       │   │   ├── Purchase_month.png
│   │       │   │   ├── Purchase_quarter.png
│   │       │   │   └── Purchase_day.png
│   │       │   │
│   │       │   ├── Filter_Rows_Using_Multiple_Conditions
│   │       │   │   ├── Filter_Condition_1.png
│   │       │   │   ├── Filter_Condition_2.png
│   │       │   │   ├── Filter_basedon_Order_status.png
│   │       │   │   └── Filter_basedon_Delivery_Day.png
│   │       │   │
│   │       │   ├── Sort_Data_Meaningfully
│   │       │   │   ├── Sort_by_paymentvalue.png
│   │       │   │   └── Sort_by_purchasedate.png
│   │       │   │
│   │       │   └── Add_an_Index_Column
│   │       │       └── Index_column.png
│   │       │
│   │       └── C_Advanced_Power_Query
│   │           ├── Merge_Queries_Using_a_Common_Key
│   │           │   ├── Merge_orders+customers.png
│   │           │   ├── Merge_Order_Item.png
│   │           │   ├── Merge_Products.png
│   │           │   ├── Merge_category_name_translation.png
│   │           │   ├── Merge_payment.png
│   │           │   ├── Merge_reviews_table.png
│   │           │   └── Merge_sellers.png
│   │           │
│   │           ├── Create_a_Date_Table_in_Power_Query
│   │           │   ├── Date_Table.png
│   │           │   └── Date_Table_result.png
│   │           │
│   │           ├── Create_a_Summarized_Query_Using_Reference_Query
│   │           │   ├── Reference_Table.png
│   │           │   └── Summary_Reference_Table.png
│   │           │
│   │           ├── Use_Group_By_with_Multiple_Aggregations
│   │           │   ├── sales_summary_by_location.png
│   │           │   └── sales_summary_by_location_result.png
│   │           │
│   │           └── Use_Column_Profiling_to_Identify_Data_Quality_Issues
│   │               ├── Profile_Final_Analytical_Table.png
│   │               └── comment_profile.png
│   │
│   ├── Column_Profile
│   │   ├── Profile_Final_Analytical_Table.png
│   │   └── comment_profile.png
│   │
│   ├── Final_Cleaned_Dataset
│   │   ├── Final_Analytical_Fact_Table.png
│   │   └── Final_Analytical_dataset_In_use.png
│   │
│   ├── Dashboard
│   │   ├── Sales_&_Revenue_Overview.png
│   │   └── Customer_&_Logistics.png
│   │
│   ├── Question_2_Power_BI_Dashboard_Development
│   │   ├── 3_KPIs.png
│   │   ├── Clustered_Bar_Chart.png
│   │   ├── Column_Chart.png
│   │   ├── Line_Chart.png
│   │   ├── Pie_Chart.png
│   │   ├── Table.png
│   │   ├── Matrix.png
│   │   ├── Map.png
│   │   ├── Gauge.png
│   │   └── Stacked_Bar_Chart.png
│   │
│   └── Question_3_Dashboard_Interactivity
│       ├── Atleast_Three_Slicers
│       │   ├── page_1_slicers.png
│       │   └── Page2_slicers.png
│       │
│       ├── Cross_Filtering
│       │   ├── cross-filtering.png
│       │   └── cross-filtering2.png
│       │
│       └── Drill_Down
│           └── drill-down.png
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## Project Overview

This repository contains the complete submission for the **DSA3050A Mid-Semester Business Intelligence Examination**. The project demonstrates an end-to-end Business Intelligence workflow using Microsoft Power BI, from data preparation and transformation to interactive dashboard development and business insight generation.

The project is organized into three main sections:

* **Section 1:** *Power Query Data Preparation*
* **Section 2:** *Dashboard Development*
* **Section 3:** *Dashboard Interactivity & Business Insights*


```text

========================================================================================
                      PROJECT PIPELINE OVERVIEW AT A GLANCE
========================================================================================

    [ INPUT: Raw Relational Data ]         [ PROCESS: Power Query ETL Engine ]
 ┌──────────────────────────────────┐    ┌─────────────────────────────────────────┐
 │  Olist E-Commerce Dataset        │    │  A. BASIC DATA CLEANING                 │
 │  • Customers      (99.4k rows)   │    │   ├── Correct Data Types (Zip to Text)  │
 │  • Orders         (99.4k rows)   │    │   ├── Remove Duplicates & Blank Rows    │
 │  • Order Items    (112.6k rows)  │    │   └── Trim, Clean & Standardize Text    │
 │  • Order Payments (103.8k rows)  │    │                                         │
 │  • Order Reviews  (99.2k rows)   │ ──>│  B. INTERMEDIATE TRANSFORMATIONS        │
 │  • Products       (32.9k rows)   │    │   ├── Date Splitting (Y / M / Q / D)    │
 │  • Sellers        (3.0k rows)    │    │   ├── Custom Columns (Delivery Days)    │
 │  • Category Trans (71 rows)      │    │   └── Conditional Logic (Speed Tier)    │
 └──────────────────────────────────┘    │                                         │
                   │                     │  C. ADVANCED MODELLING                  │
                   ▼                     │   ├── Star-Schema Remap (8-Way Merge)   │
 ┌──────────────────────────────────┐    │   ├── Generated Master Date Table       │
 │  Excluded for Performance:       │    │   └── Group By Summarized Reference     │
 │  • Geolocation (1M+ Rows)        │    └─────────────────────────────────────────┘
 └──────────────────────────────────┘                         │
                                                              ▼
                                               [ OUTPUT: Business Intelligence ]
                                         ┌─────────────────────────────────────────┐
                                         │  FINAL ANALYTICAL TABLE              │
                                         │   └── Dimensions: 99,441 Rows x 35 Cols  │
                                         │                                         │
                                         │  INTERACTIVE POWER BI DASHBOARD       │
                                         │   ├── Page 1: Sales & Revenue Overview  │
                                         │   │    └── Key Insight: Credit Card Max│
                                         │   └── Page 2: Customer & Logistics      │
                                         │        └── Key Insight: SP Hub Dominance│
                                         └─────────────────────────────────────────┘

========================================================================================
```

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

## Business Scenario

A Business Intelligence solution was developed based on a large raw e-commerce dataset containing inconsistencies, missing values, errors, and poorly structured fields. The dataset was cleaned and transformed using **Power Query**, integrated into a consolidated analytical model, and used to develop an interactive **Power BI** dashboard that supports business analysis and informed decision-making.

---

# Section 1 — Power Query Data Preparation

The imported datasets underwent extensive cleaning and transformation in Power Query to improve data quality, ensure consistency, and prepare the data for analysis.

---

## A. Basic Data Cleaning

* **Renamed unclear column names:**

  *Example:* Renamed **Column 2** to **English_Name** in the **Product Category Translation** table.
* **Corrected data types:**

  *Example:* Changed **Zip Code** from **Whole Number** to **Text** in the **Geolocation** table.
* **Removed duplicate records where appropriate:**

  *Example:* Removed duplicate records using **customer_id** in the **Customers** table.
* **Removed blank rows:**

  *Example:* Removed blank rows from the **Order Reviews** table.
* **Trimmed and cleaned text columns:**

   *Example:* Applied **Trim** and **Clean** transformations to the **customer_city** column in the **Customers** table.
* **Replaced inconsistent values:**

  *Example:* Standardized inconsistent **payment_type** values in the **Order Payments** table.
* **Removed unnecessary columns:**

  *Example:* Removed product dimension columns such as **product_length_cm** and **product_height_cm** from the **Products** table as they were not required for the intended analysis.

---

## B. Intermediate Transformations

* **Split date and time columns:**

  *Example:* Split **purchase_timestamp** into separate **Purchase Date** and **Purchase Time** columns.
* **Merged two or more columns:**

  *Example:* Combined **seller_city** and **seller_state** into a single **Seller Location** column in the **Sellers** table.
* **Created custom columns:**

  *Example:* Created a **Delivery Days** column by calculating the difference between the purchase and delivery dates.
* **Created conditional columns:**

   *Example:* Created a **Delivery Speed** column to categorize deliveries as *Fast*, *Standard*, or *Slow*.
* **Extracted Year, Month, Quarter, and Day:**

   *Example:* Extracted **Year**, **Month**, **Quarter**, and **Day** from the **Purchase Date** column.
* **Applied filtering using multiple conditions:**

  *Example:* Filtered records to include **Delivered** orders with **Delivery Days < 30**.
* **Sorted data meaningfully:**

  *Example:* Sorted the **Orders** table by **Purchase Date** in descending order to display the most recent orders first.
* **Added an Index column:**

  *Example:* Added an **Index** column to the **Orders** table for row identification.


---

## C. Advanced Power Query Tasks

* **Merge Queries using common keys**

  **Example:**

  Merged **8 relational tables** into a single **Final Analytical Table** following the sequence below:

  ```text
  Orders
      │ order_id
      ▼
  Customers
      │ customer_id
      ▼
  Order Items
      │ order_id
      ▼
  Products
      │ product_id
      ▼
  Product Category Translation
      │ product_category_name
      ▼
  Order Payments
      │ order_id
      ▼
  Order Reviews
      │ order_id
      ▼
  Sellers
      │ seller_id
      ▼
  Final Analytical Table
  (99,441 Rows × 35 Columns)
  ```

* **Create a Date Table**

  **Example:**

  Created a dedicated **Date Table** from the **Purchase Date** column to support time-based analysis, filtering, and dashboard visualizations.

* **Create a Summarized Reference Query**

  **Example:**

  Created a **Reference Query** from the **Final Analytical Table** and summarized **Total Revenue by Customer Location** for reporting purposes.

* **Group By with Multiple Aggregations**

  **Example:**

  Aggregated **Customer Location** to calculate:

  * Total Sales
  * Number of Orders
  * Average Delivery Days

* **Use Column Profiling to Identify Data Quality Issues**

  **Example:**

  Applied **Column Profiling** to identify data quality issues in the **Order Reviews** table and to validate the completeness, uniqueness, and overall quality of the **Final Analytical Table** before dashboard development.

---


## *Output of the Power Query Preparation*

## Final Analytical Table

After completing all cleaning and transformation tasks, the individual datasets were integrated into a single **Final Analytical Table**.

This analytical table combines customer, order, payment, seller, review, and product information into one consolidated dataset optimized for reporting, dashboard development, and business analysis.

---

# Section 2 — Dashboard Development

An interactive Power BI dashboard was developed to transform the cleaned analytical dataset into meaningful business insights through effective data visualization. The dashboard was designed with a professional layout, consistent formatting, interactive navigation, and user-friendly visuals to support informed decision-making.

## Dashboard Contents

The dashboard includes the following visualizations:

* KPI Cards
* Bar Chart
* Column Chart
* Line Chart
* Pie/Donut Chart
* Table Visual
* Matrix Visual
* Filled Map
* Tree Map
* Ribbon Chart
* Interactive Slicers and Filters

## Analytical Focus

The dashboard provides insights into:

* Revenue Distribution
* Order Volume
* Customer Geographic Distribution
* Payment Methods
* Delivery Performance
* Customer Satisfaction

---

## Dashboard Preview

### Dashboard Page 1 — Sales & Revenue Overview

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Screenshots/dashboard/Sales%20%26%20Revenue%20Overview.png" width="1000"/>
</p>

---

### Dashboard Page 2 — Customer & Logistics

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Screenshots/dashboard/Customer%20%26%20Logistics%20.png" width="1000"/>
</p>

---

# Section 3 — Dashboard Interactivity & Business Insights

The dashboard was designed with interactive features that enable users to dynamically explore the dataset and uncover insights from different business perspectives. These features improve usability by allowing users to filter, drill into, and interact with visualizations for more detailed analysis.

## Dashboard Interactivity Features

### Interactive Slicers

The dashboard contains multiple slicers that allow users to filter the report by different business dimensions such as customer location, payment method, order period, and product category.

#### Page 1 Slicers

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Screenshots/dashboard/Question%203Dashboard%20Interactivity/Atleast%20three%20slicers/page%201%20slicers.png" width="900"/>
</p>

#### Page 2 Slicers

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Screenshots/dashboard/Question%203Dashboard%20Interactivity/Atleast%20three%20slicers/Page2%20slicers.png" width="900"/>
</p>

---

### Cross-Filtering

Cross-filtering enables selections made in one visual to automatically filter and highlight related information across the remaining visuals on the report page, providing a more interactive analytical experience.

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Screenshots/dashboard/Question%203Dashboard%20Interactivity/Cross-filtering/cross-filtering2.png" width="900"/>
</p>

---

### Drill-Down Analysis

Drill-down functionality allows users to navigate from higher-level summaries to more detailed levels of information, enabling deeper exploration of trends and patterns within the data.

<p align="center">
  <img src="https://raw.githubusercontent.com/ibtj21/DSA3050A_MidSem_Hana_670555/main/Screenshots/dashboard/Question%203Dashboard%20Interactivity/Drill-down/drill-down.png" width="900"/>
</p>


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


# Screenshots Included In The Repository


| Category                                      | Screenshots Included                                                                                                                                 |
| --------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Raw Datasets**                              | Customers, Orders, Order Items, Order Payments, Order Reviews, Products, Sellers, Geolocation, Product Category Translation                          |
| **Power Query Editor**                        | Power Query Editor interface                                                                                                                         |
| **Applied Steps Pane (Multi-table)**          | Applied Steps Pane for Basic Data Cleaning, Intermediate Transformations, and Advanced Power Query across multiple tables                                 |
| **Question 1 – Basic Data Cleaning**          | Rename Columns, Correct Data Types, Remove Duplicates, Remove Blank Rows, Trim & Clean Text, Replace Inconsistent Values, Remove Unnecessary Columns |
| **Question 1 – Intermediate Transformations** | Split Date & Time, Merge Columns, Custom Column, Conditional Column, Extract Year/Month/Quarter/Day, Filter Rows, Sort Data, Add Index Column        |
| **Question 1 – Advanced Power Query**         | Merge Queries, Create Date Table, Reference Query, Group By, Column Profiling                                                                        |
| **Column Profiling**                          | Final Analytical Table Profile, Column Quality & Distribution                                                                                        |
| **Final Cleaned Dataset**                     | Final Analytical Table, Final Dataset in Use                                                                                                         |
| **Dashboard Overview**                        | Sales & Revenue Overview, Customer & Logistics Dashboard Pages                                                                                       |
| **Question 2 – Dashboard Development**        | KPI Cards, Clustered Bar Chart, Stacked Bar Chart, Column Chart, Line Chart, Pie Chart, Table, Matrix, Filled Map, Gauge                             |
| **Question 3 – Dashboard Interactivity**      | Slicers (Page 1 & Page 2), Cross-Filtering, Drill-Down                                                                                               |


---

## Software Used

* Microsoft Power BI Desktop

---

## Limitations

* **Geolocation information was not incorporated into the final analytical model** due to its large size (over one million records), which exceeded the project's hardware constraints on an 8 GB RAM system and could negatively impact Power BI performance. Consequently, geographic analyses were conducted using **customer state and city** rather than precise latitude and longitude coordinates.


---

## Reflection & Lessons Learned

This project strengthened my understanding of the complete Business Intelligence lifecycle, from raw data preparation to interactive dashboard development. I gained practical experience in using Power Query for data cleaning, transformation, query merging, and analytical modeling.

Additionally, I developed a deeper appreciation for the importance of data quality, effective dashboard design, and transforming raw business data into actionable insights that support strategic decision-making.

---

## Academic Integrity Statement

This project was completed using a publicly available dataset obtained from Kaggle. All data preparation, transformation, visualization, dashboard development, and analysis were performed using Microsoft Power BI.

No AI-generated, fabricated, synthetic, or artificially created datasets were used in this project.

---

## License

This project is released under the **MIT License**.

---

## Collaboration

Contributions, suggestions, and constructive feedback are welcome.


