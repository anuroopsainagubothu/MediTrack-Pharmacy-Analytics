# MediTrack – Pharmacy Sales & Inventory Analytics

## 1. Project Overview

MediTrack is a data analytics project focused on analysing pharmacy sales transactions and inventory records. The project uses Python, MySQL, and Microsoft Power BI to explore datasets, examine data quality, perform SQL-based analysis, and develop interactive dashboards.

The primary objective is to understand pharmacy sales performance and inventory movement through data-driven analysis and visualization.

## 2. Business Problem

Pharmacies generate large volumes of sales and inventory data. Analyzing this information can help businesses understand product performance, monitor stock movement, identify sales trends, and make informed operational decisions.

MediTrack addresses this need by analyzing sales and stock transaction datasets and presenting useful information through interactive dashboards.

## 3. Project Objectives

- Analyze pharmacy sales transactions.
- Examine inventory and stock movements.
- Identify missing values and data quality issues.
- Explore drug categories and product information.
- Perform SQL queries to answer business questions.
- Analyze sales and inventory performance.
- Build interactive Power BI dashboards.
- Present findings in an understandable visual format.

## 4. Dataset Overview

The project uses two datasets from the Indonesian Retail Pharmacy Sales and Stock Transaction Dataset (2023–2025).

### Dataset 1: Sales Dataset

- Total Records: 649,656
- Total Columns: 30

The dataset contains information about:
- Invoice numbers
- Transaction dates
- Cashier information
- Drug names and codes
- Drug categories and classes
- Quantity sold
- Unit prices
- Discounts
- Payment types
- Total transaction prices

### Dataset 2: Stock Dataset

- Total Records: 804,027
- Total Columns: 23

The dataset contains information about:
- Warehouse details
- Drug names and codes
- Transaction descriptions
- Initial stock
- Stock-in quantities
- Stock-out quantities
- Remaining stock
- Drug categories
- Inventory status

### Dataset Source

Indonesian Retail Pharmacy Sales and Stock Transaction Dataset (2023–2025).

Source: Mendeley Data

https://data.mendeley.com/datasets/w6zjtdjk9m/2

## 5. Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data exploration and analysis |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| MySQL | Database management and SQL analysis |
| Microsoft Power BI | Interactive dashboards |
| Excel | Data inspection and spreadsheet operations |

## 6. Project Workflow

The project follows these stages:

1. Dataset collection
2. Data loading and inspection
3. Data exploration using Python
4. Data quality assessment
5. Database and table creation in MySQL
6. SQL-based data analysis
7. Dashboard development in Power BI
8. Project documentation and GitHub publication

## 7. Python – Data Exploration and Quality Assessment

Python libraries were used to inspect and understand the sales and stock datasets.

### Activities Performed

- Imported Pandas, NumPy, Matplotlib, and Seaborn.
- Loaded the sales and stock datasets.
- Checked dataset dimensions.
- Examined the first and last records.
- Inspected column names and data types.
- Analyzed missing values and missing-value percentages.
- Identified completely empty columns.
- Examined hyphen placeholders in the sales dataset.
- Extracted and analyzed batch number information.
- Checked unique values in categorical columns.
- Analyzed Drug Class and Category information.
- Created working copies of the datasets.

The purpose of this stage was to understand the structure and quality of the data before further analysis.

## 8. MySQL – Database and SQL Analysis

MySQL was used to store and analyze pharmacy sales and inventory information.

### Key SQL Activities

- Database and table creation
- Data exploration and validation
- Aggregate functions:
  - SUM()
  - COUNT()
  - AVG()
  - MIN()
  - MAX()
- GROUP BY and HAVING
- Filtering using WHERE
- INNER JOIN and LEFT JOIN
- Subqueries
- Common Table Expressions (CTEs)
- Date-based analysis

### Business Analysis Areas

The SQL analysis focuses on examining:
- Pharmacy sales performance
- Revenue and transaction information
- Drug category performance
- Product-level performance
- Inventory movement
- Stock availability

These analysis areas help organize the data into meaningful information for business reporting.

## 9. Power BI – Dashboard Development

Microsoft Power BI was used to develop interactive dashboards for sales and inventory analysis.

### Dashboard 1: Sales Performance Dashboard

The sales dashboard focuses on monitoring pharmacy sales performance.

Key Performance Indicators:
- Total Sales Revenue
- Total Invoices
- Total Quantity Sold
- Unique Customers

Analysis areas:
- Sales and revenue trends
- Product performance
- Drug category performance
- Payment type analysis
- Transaction trends

### Dashboard 2: Inventory Intelligence Dashboard

The inventory dashboard focuses on understanding stock movement and inventory availability.

Analysis areas:
- Initial stock
- Stock-in quantities
- Stock-out quantities
- Remaining stock
- Inventory status
- Drug category analysis

The dashboards provide a visual overview of the sales and inventory datasets.

## 10. Expected Business Value

The project is designed to support the following business objectives:

- Better understanding of pharmacy sales performance.
- Improved visibility into product and category performance.
- Monitoring of inventory movement.
- Easier identification of stock availability patterns.
- Faster access to important business metrics.
- Support for data-driven business decisions.

These are intended uses of the analysis, not claims of measured business improvements.

## 11. Project Deliverables

The project repository contains the following components:

| Folder | Description |
|---|---|
| 01_Data | Dataset information and download links |
| 02_Python | Python data exploration notebook |
| 03_SQL_Analysis | SQL scripts and analysis |
| 04_PowerBI | Power BI dashboard information and download links |
| 05_Documentation | Project documentation |

## 12. Conclusion

MediTrack demonstrates the application of data analytics techniques to pharmacy sales and inventory datasets.

The project combines Python for data exploration and quality assessment, MySQL for database management and SQL analysis, and Power BI for interactive visualization.

By working with two large datasets containing more than 1.4 million records combined, the project provides practical experience in handling structured business data and developing analytical reports.

MediTrack also demonstrates an end-to-end data analytics workflow, from collecting and inspecting raw data to analyzing information and presenting it through dashboards.

## 13. Future Scope

The MediTrack project can be further enhanced through:

- Automated data updates and reporting.
- Advanced sales forecasting.
- Inventory demand prediction.
- Low-stock alerts and expiry-date monitoring.
- Advanced customer and product behavior analysis.

These improvements could help extend the project into a more comprehensive pharmacy analytics solution.

## 14. Author

N.Anuroop Sai | Data Analyst |

Tools Used :- | Excel | Python | SQL | PowerBI |
