# SQLServerToDataLake
An outline of how of an on-premise to Cloud based data migration
1. Generation of SQL-Server meta-data used to generate an Config file
2. Loading into DataLake with Datafactory 
a) To raw using the Config file
b) To silver with additional flows
3. Running checks and validating data
4. Displaying a data model in the Silver layer
