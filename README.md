# SQLServerToDataLake
An outline of how of an on-premise to Cloud based data migration
0. Establishing a models of bost on-premise databases 
1. Generation of SQL-Server meta-data used to generate an Config file
2. Loading into DataLake with Datafactory 
a) To raw using the Config file
b) To silver with additional flows
3. Establishing the scripts used to create valuable views withing SQL Server
4. Running checks and validating data
5. Displaying a data model in the Silver layer
