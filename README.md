# Iowa Liquor sales Data Modeling

## Tasks

#### Part 1: Load into separate staging tables
- **Task 1: Load staging tables with Talend**
  - Choose staging tables options: Azure SQL, SQL Server, MySQL, or Azure MySQL.

- **Task 2: Create a Dimensional Data Model**
  - Create a dimensional data model using ER/Studio or Navicat.
  - Create SQL DDL script for the dimensional data model for the same database as stage tables.

#### Part 2: Load integration schema (dimensional model)
- **Task 1: Load data from STG tables to dimensional model & perform data cleansing**
  - Load integration schema (dimensional model).
  - Query integration schema to answer business questions.
  - Use Alteryx data prep tool to load data.
  - Document data cleansing tasks and results.
  - Query dimensional data model with the listed business questions as a minimum.

- **Task 2: Load Dimensional Model**
  - Load staging tables with Talend.
  - Choose dimensional tables options: Azure SQL, SQL Server, MySQL, or Azure MySQL.

#### Task 3: Query Integration Schema to answer business questions & Create dashboards
- **Query Integration Schema to answer business questions**
  - Write SQL queries.
  - Create dashboards using Power BI Service or Tableau Online.
  
- **Business questions: Iowa Liquor Sales**
  - **Liquor sales: Measures**
    - Sales $
    - Sales volume (gallons)
    - Sales volume (bottles)
    - Gross profit (retail price cost)
    - Sales $ per Capita
  - **Liquor Sales by time**
    - Total
    - Year
    - Year, Month
    - Year over Year (YOY)
  - **Liquor sales by dimension**
    - Store
    - County
    - City
    - Category
    - Item
    - Vendor
  - **Liquor sales by sales $**
    - Yearly sales including 2022 YTD
    - Top 20 stores (all time)
    - Top 20 cities (all time)
    - Top 10 counties (all time)
    - Top 20 categories (all time)
    - Top 50 items (all time)
    - Top 20 vendors (all time)

