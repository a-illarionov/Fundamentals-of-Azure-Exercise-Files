# Fundamentals of Azure
## Azure Resources 
For this excerise you will need: 
- Azure Tenant
- Azure Subsciption
## Objectives 
- Create a resource group
- Create a SQL Database
- Create a SQL Server
- Update the firewall to include your IP address
- Connect to the SQL server and run a SQL query 

Message me if you have any questions. 
## Excerise: 
### Create a Resource Group
  Create a resource group named "rg-test-<azureregion>-sql-001
### Create a SQL Database
  Create a SQL database with Sample Data
### Create a SQL server  
  Create a serverless SQL server with a globally unique name 
### Update the firewall to include your IP address
  Use the built-in client to update the SQL database firewall to allow your public IP address.
### Connect to the SQL server and run a SQL query 
  Authenticate your user on the SQL server and run a SQL query with the sample database. 
  You can use the code below for reference: 
```
SELECT TOP 20 pc.Name as CategoryName, p.name as ProductName
FROM SalesLT.ProductCategory pc
JOIN SalesLT.Product p
ON pc.productcategoryid = p.productcategoryid;
```

  
### You can find the answers here
  [Answer doc](Answers.md) 
