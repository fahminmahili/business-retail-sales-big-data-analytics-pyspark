# business-retail-sales-big-data-analytics-pyspark
Dive into Big Data Analytics using Apache Spark. Explore the "Superstore Dataset 2011-2015" from Kaggle. Tasks include working with Spark RDDs, Spark SQL, and Spark DataFrames to discover insights through transformations and SQL queries. Join the adventure in the world of Big Data! 


Big Data Analytics with Apache Spark

Overview
This project showcases the application of Big Data Analytics concepts using Apache Spark, a powerful open-source framework for distributed processing of large datasets. The project focuses on three main tasks: Spark RDDs, Spark SQL, and Spark DataFrames. Each task involves handling and analyzing a dataset using different Spark components.

Task 1: Spark RDDs
Dataset Selection: I chose the "superstore_dataset2011-2015.csv" from the Kaggle, available at https://www.kaggle.com/datasets/jr2ngb/superstore-data

Installation and Loading: Apache Spark was installed locally, and the dataset was loaded into the Spark environment.

RDD Transformations:
Map: Extracted relevant information from the dataset.
Filter: Removed entries with non-positive profits.
Reduce: Aggregated profits by category.
Count: Determined the total number of records.
GroupBy: Grouped data by category and calculated the sum of profits.


Task 2: Spark SQL
Dataset Loading: Utilized Spark SQL to load the same dataset.
Temporary Views and SQL Queries:
Aggregations: Performed category-wise profit aggregation.
Filtering: Selected entries with positive profits.
Sorting: Ordered data by profit in descending order.


Task 3: Spark DataFrames
Dataset Reading: Used Spark DataFrames to read the dataset.

Transformations and Actions:
Select: Extracted specific columns.
GroupBy: Grouped data by category and calculated the sum of profits.
OrderBy: Sorted data by profit in descending order.


How to Replicate

Clone the repository.
Install Apache Spark locally.
Run the provided Jupyter Notebook on Google Colab or your local environment.

Dataset Source
The dataset was obtained from this source. https://www.kaggle.com/datasets/jr2ngb/superstore-data

Conclusion
This project demonstrates practical applications of Big Data Analytics using Apache Spark, providing a foundation for understanding the distributed processing of large datasets and the versatility of Spark components. 
