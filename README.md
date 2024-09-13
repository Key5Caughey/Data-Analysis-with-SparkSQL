# HomeSales-challenge-22

## BACKGROUND
Used SparkSQL to determine key metrics about home sales data. Then used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.
Answer the following questions using SparkSQL:
- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round 
off your answer to two decimal places.
- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.



### Using SparkSQL to determine key metrics about home sales data. Use Spark to create temporary views, partition data, cache and uncache a temporary table.

Read in home_sales_revised.csv, created temporary table. Answered required questions using SQL, cached temporary table, checked to see if it was cached. Reran query using cached table to compare with uncached runtime. Uncached table, check to see if it was uncached using PySpark.

### Libraries/Modules 

findspark, pyspark.sql, SparkSession, time, SparkFiles

### Resources

Class notes, Office hours, Tutor, Chatgpt
