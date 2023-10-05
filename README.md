# SalesManagmentDataAnalysisproject
Welcome to the "Internet Sales Management Data Analysis" project repository. This project focuses on leveraging SQL for data cleansing and Power BI for visualization to gain valuable insights from internet sales data.

# Internet Sales Management Data Analysis

## Business request Overview
Visual dashboard and improved Sales reporting or follow for sales
delivered file: budgets have been delivered in excel file **SalesBudget.xlsx** for 2022 - 2021

![requests](https://github.com/JawaherCharfeddine/SalesManagmentDataAnalysisproject/blob/main/overview.png)


This project focuses on leveraging SQL Express for data cleansing and Power BI for visualization to gain valuable insights from internet sales data.

## Project Objectives

- **Data Collection**: Gather data from [AdventureWorksDW2022.bak](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2022.bak) databse.

- **Data Cleansing and Transformation with SQL Express**:

  Utilize SQL Express for data cleaning and preprocessing using the sql script:
    - DIM_Calender.sql
    - DIM_Customers.sql
    - DIM_Products.sql
    - FACT_InternetSales.sql
  
  extract data to Excel files:
    - DIM_Calender.csv
    - DIM_Customers.csv
    - DIM_Products.csv
    - FACT_InternetSales.csv  

- **Data Analysis with Power BI**:
  1. Data Model:
     Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.This data model also shows how FACT_Budget tabel has been connected to   
     FACT_InternetSales table and other necessary DIMENSIONAL tables.
     ![data model](https://github.com/JawaherCharfeddine/SalesManagmentDataAnalysisproject/blob/main/data%20model.png)
     
  3. Data visualization (Dashboard):
     the represented screenshot show the sales overview dashboard
     ![dashboard](https://github.com/JawaherCharfeddine/SalesManagmentDataAnalysisproject/blob/main/sales%20overview%20dashboard.png)


## Technologies Used

- **Data Cleansing**: SQL Express for data cleaning and preprocessing.

- **Data Visualization**: Power BI for creating interactive and informative data visualizations, dashboards.

## Installation and Usage

**used data for this scenario**: 
  - [Download AdventureWorksDW2022.bak](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2022.bak)
**used Softwares for this scenario**:
  - [Download SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms)
  - [Download Power BI Desktop](https://powerbi.microsoft.com/fr-fr/desktop/)


## License

- MIT License (or specify the project's license).


## Author
- [JawaherCharfeddine]





