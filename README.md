# power-BI-Demo

## INTRODUCTION

### Data Modelling 
Data Modelling in power BI is one of the features used to connect multiple Data sources
using a relationship.
A relationship defines how data sources are connected with each other and you can create
an interesting data visualization on multiple data sources.

### Importance of Data Modelling

- It helps create a unified view of data by defining tables , columns , and relationships.
- It improves data organisation, effective analysis, and reporting .

### Key Components

- Facts tables : It stores quantitative and measurable data such as sales, transactions , finam=ncial metrics,
  or event data.

  They contain foreign keys to link to dimension tables and captures the context and details of each transactions.
  or event.

- Dimension Tables : It provides descriptive information about the business entities or aspects relate to the facts

  They contain attributes like customer names, product details , geographyical information , and time dimension.

- Primary Keys uniquely identify each record in a table and ensure data intergrity.

- Foreign keys establish relationhips by linking to the primary key of another table.


### Data Modelling and Relationship types

Power BI supports three relationship types:

- One_to_one relationship: This links one record in a table to exactly one record in another table.

- One_to_many relationship : This linkks one record to multiple related records in another table.

- Many_to_many relationship :This involves intermediate tables to establish connections between multiple records in
different tables.


### PROBLEM SOLVING

USING THE NORTHWIND TRADERS DATASET

- MODEL

- VISUALIZE AND

- ANALYZE YOUR INSIGHTS


### SOLUTION

Open your power BI

click on get data 

Import data from the files you saved with

Transform to power query to clean the datasets

Load and it will be imported to your power BI.

On the left pane of your power BI desktop

Click on Model

By default, power BI will create a relationship.

Then adjust or remove unwanted connections by right clicking on the connectors.



![modelling.png](https://github.com/Ifunanya993/power-BI-Demo/blob/9cb328e444a825e25bfbf733fc9054ba0299aa79/modelling.png)


 
Employees table and Customer table : The tables was connected by City, which is the common column.

Shippers table and Orders table: The tables was connected by ShipperID, which is the common column.

Order details  table and Products table : The tables was connected by ProductID, which is the common column.

Employees table and Orders table : The tables was connected by EmployeeID, which is the common column.

Category table and Product table : The tables was connected by CategoryID, which is the common column.

Shippers table and Order table : The tables was connected by ShippersID, which i the common column.

Order details table and Order table : The tables was connected by OrderID, which is the common column.

Shippers table and Customer table : The tables was connected by Companyname, which is the common column.

Customers table and Order table : The tables was connected by CustomerID, which is the common column.


### VISUALIZATION

This comprises of :

1. Sum of Freight

2. Average unitprice of the products

3. Number of quantity of products sold

4. Sum of discounts by company name

5. sum of quantity by company name


### ANALYSIS

1. Sum of freight.
The total cost of goods freighted to the customers is

2. The 






















  

