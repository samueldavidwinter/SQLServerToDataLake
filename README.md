# SQLServerToDataLake
An outline of an on-premise to cloud migration

0. Establishing a models of bost on-premise databases 
1. Generation of SQL-Server meta-data used to generate an Config file
2. Loading into DataLake with Datafactory 
a) To a raw 'lake' style layer using the Config file
b) Establishing the scripts used to create valuable views within SQL Server
c) To a presenting reational layer with additional flows, influenced by SQL Server views
4. Running checks and validating data from the command line
5. Displaying a data vault model in the Silver layer
6. Displaying a star schema model in the Gold Layer 

An overview of Azure cloud migration can be seen here: https://medium.com/@samueldavidwinter/data-engineering-pipelines-a-reference-62763da9f0ff
