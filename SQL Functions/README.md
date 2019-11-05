# Snowflake Package Summary

|Package Name| Package Description| Number of Queries in Package|
|------------|--------------------|-----------------------------|
|Aginity-Pro-Snowflake-SQL-Functions.aginitypkg   | Common SQL functions to use when writing SQL |1   |

We highly recommend using our functions and referencing the Snowflake SQL Function Reference https://docs.snowflake.net/manuals/sql-reference-functions.html!  


### The table below details all queries within the Aginity-Pro-Snowflake-SQL-Functions package.


|Catalog Folder Name               |Catalog Folder Description            | Example     |
|--------------------------|------------------------------------|--------------------|
|Aggregate Functions|functions that take multiple rows/values as input and return a single value.|select count(col1, col2) from table1;|
|Bitwise Expression Functions|This family of functions can be used to perform Bitwise operations on numbers or a group of numeric records.||
|Conditional Expression Functions|Conditional expression functions return values based on logical operations using each expression passed to the function.|select 'true' where 1 between 0 and 10;|
|Context Functions|This family of functions allows gathering information about the context in which the statement is executed.|select current_warehouse(), current_database(), current_schema();|
|Conversion Functions|This family of functions can be used to convert an expression of any Snowflake data type to another data type.|select to_date('3/4/2013', 'dd/mm/yyyy');|
|Data Generation Functions|Data Generation functions allow you to generate data.|select random(4711) from table(generator(rowcount => 5));|
|Date & Time Functions|This family of functions can be used to construct, convert, extract, or modify DATE/TIME/TIMESTAMP data.||
|Numeric Functions|Numeric functions operator on numeric values and perform operations such as rounding and exponentiation.|select column1, abs(column1) from (values (0), (1), (-2), (3.5), (-4.5), (null));|
|Semi-structured Data Functions|These functions are used with semi-structured data (JSON, Avro, XML), typically stored in Snowflake in VARIANT, OBJECT, or ARRAY columns.||
|String & Binary Functions|This family of functions perform operations on a string input value, or binary input value (for certain functions), and return a string or numeric value.|select column1, ascii(column1)
  from (values('!'), ('A'), ('a'), ('bcd'), (''), (null));|
|System Functions|functions that perform control operations or return system-level information.|select system$abort_session(1065153868222);|
|Table Functions|functions that return results in tabular format.|select seq4(), uniform(1, 10, random(12)) from table(generator(rowcount => 10)) v order by 1;|
|Window Functions|subset of aggregate functions that can operate on a subset of rows.||

