# Redshift Package Summary

|Package Name| Package Description| Number of Queries in Package|
|------------|--------------------|-----------------------------|
|Aginity-Pro-Redshift-SQL-Functions.aginitypkg   | Common SQL functions to use when writing SQL |1   |

We highly recommend using our functions and referencing the [Amazon Redshift SQL Reference manual](https://docs.aws.amazon.com/redshift/latest/dg/cm_chap_SQLCommandRef.html)!  




### The table below details all queries within the Aginity-Pro-Redshift-Data-Engineering-DateLogic package.



|Catalog Folder Name               |Catalog Folder Description            | Example     |
|--------------------------|------------------------------------|--------------------|
|Aggregate Functions   |  This folder holds all SQL aggregate functions for Redshift.   | Example functions are things like SUM() and AVG() |
|Conditional Expressions   | This folder contains all SQL functions used to evaluate and take conditional action on data  | The most common is the usage of the CASE statement.   |
|JSON Functions   | Want to work with JSON that is stored in table column?  Use these functions to manipulate that data.   | Use JSON_EXTRACT_ARRAY_ELEMENT_TEXT to get at values in the JSON object  |
|Math Functions   | Typical mathematical operators available to use in Redshift  | Fucnctions like Absolute Value (ABS)   |
|String Functions   | Want to transform those strings or find something in them?  Use these functions to do that transformation   | Substring a common function to extract part of a string.   |
|Window Functions   | Need to do multi-pass type analysis using SQL, then Windowing functions are for you.  |  My favorite is the PERCENT_CONT to do segment data sets.  |
