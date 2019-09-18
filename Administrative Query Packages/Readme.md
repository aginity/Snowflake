# Snowflake Package Summary

|Package Name| Package Description| Number of Queries in Package|
|------------|--------------------|-----------------------------|
|Aginity-Pro-Snowflake-Admin-Set1|Contains administrative queries to do common tasks in Snowflake   | 8  |




### The table below details all queries within the Aginity-Pro-Snowflake-Admin-Set1 package.



|Catalog Item Name               |Catalog Item Description            | Required Table     |
|--------------------------|------------------------------------|--------------------|
|Generate DROP tables in schema   | Will generate drop statements for any table in schema  | information_schema.tables  |
|Get Constraints on tables for given schema   |Get any constraints that are tied to a table within a schema  |  information_schema.table_constraints |
|Get query history for the last N hours   |A very cool query that allows you to see what SQL statements have run in the last N hours |information_schema.query_history   |
|Get running Queries   | A list of actively running queries  |  information_schema.query_history_by_session |
|Get tables DDL stmt in a schema   | Generate all ddl within a schema  |   INFORMATION_SCHEMA.TABLES   |
|Get Tables from Data Dictionary   | Generate a list of tables within a schema  | information_schema.tables   |
|Get Tables Size in MB in a schema   | List size of tables within a schema  |   information_schema.tables |
|Show Tables in a schema   | Show detail about tables within a schema | Uses show tables command  |
