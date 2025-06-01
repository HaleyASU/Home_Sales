# Home_Sales
In this challenge, I use my knowledge of SparkSQL to determine key metrics about home sales data. I use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Final Homework – Data Bootcamp 2025
By Haley Armenta

📌 Overview
This project uses PySpark and SparkSQL to analyze a dataset of U.S. home sales. The assignment showcases core skills in distributed data processing, temporary views, caching, Parquet formatting, and performance benchmarking.

🛠️ Technologies Used
PySpark

SparkSQL

Google Colab / Jupyter Notebook

Pandas (lightly)

AWS S3 (for data sourcing)

📂 Data Source
home_sales_revised.csv

🔍 Analysis Breakdown
Task	Description
✅ DataFrame Creation	Loaded CSV data from AWS S3
✅ Temp View	Created home_sales temp table
✅ Query 1	Avg price of 4-bedroom homes sold per year
✅ Query 2	Avg price of 3 bed / 3 bath homes by year built
✅ Query 3	Avg price of 3 bed / 3 bath homes with 2 floors & ≥ 2000 sqft
✅ Query 4	Avg price by view rating (≥ $350K), with runtime logging
✅ Caching	Cached & verified home_sales table
✅ Performance	Re-ran query using cache and measured runtime
✅ Partitioning	Partitioned dataset by date_built into Parquet format
✅ Parquet Temp View	Created parquet_home_sales table
✅ Final Query	Reran query on Parquet data and measured runtime
✅ Cleanup	Uncached temp table and verified memory release

📈 Takeaways
Caching significantly improves query performance on repeated data access.

Partitioning data by relevant fields (like date_built) increases read efficiency.

SparkSQL is 🔥 for querying large datasets at scale.

🎉 Closing Notes
This was the final homework assignment of my bootcamp journey, and it was the most challenging — but also the most rewarding.

