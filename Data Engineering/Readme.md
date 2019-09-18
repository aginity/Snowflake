# Snowflake Package Summary

|Package Name| Package Description| Number of Queries in Package|
|------------|--------------------|-----------------------------|
|Aginity-Pro-Snowflake-Data-Engineering-Set1|Contains administrative queries to do common tasks in Snowflake   | 4 |




### The table below details all queries within the Aginity-Pro-Snowflake-Data-Engineering-Set1 package.



|Catalog Item Name               |Catalog Item Description            | Example     |
|--------------------------|------------------------------------|--------------------|  
|Generate table of increment dates   |  Will generate a list of dates based on input of rows to return  |  CREATE TABLE slug as SELECT * FROM  (@{/Community Queries/Snowflake/Data Engineering/Generate table of increment dates}) b; |
|Generate table of numbers from 0 to N   | Will generate a list of numbers.  Like above, you can use this to pivot data and numerous other data engineering uses |  CREATE TABLE slug as SELECT * FROM  (@{/Community Queries/Snowflake/Data Engineering/Generate table of numbers from 0 to N} ) b;  |
|Get SELECT stmt for 1 row sample for each table in a schema  | Run just as a command, enter in the schema and you will get a summary sample for each table in schema |@{/Community Queries/Snowflake/Data Engineering/Get SELECT stmt for 1 row sample for each table in a schema}   |
|Recursive CTE numbers up to given number  | Similar to number generation above.  This is another method to accomplish same result  | CREATE TABLE slug as SELECT * FROM  (@{/Community Queries/Snowflake/Data Engineering/Recursive CTE numbers up to given number} ) b; |
