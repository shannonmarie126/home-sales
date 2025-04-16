# home-sales

- This project uses a large data set on home sales, querying different information using a Temporary view via spark. 
The final query is cached then run again, measuring time to show a decrease in run time.
- The data frame is then partitioned by year built and formatted to parquet and run again, showing a further decrease in run time. 
- Overall, this project displays how to use spark to run sql queries on large data sets and ways to decrease run times on querying the data. 
