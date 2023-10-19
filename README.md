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


### Cardinality and filtering

Cardinality
  

