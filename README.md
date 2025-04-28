# Analyze data with Apache Spark in Fabric

This lab covers the steps of reading, analyzing, and processing data using Apache Spark in Microsoft Fabric. PySpark is the default programming language in Fabric notebooks and provides powerful tools to interact with data.

### 1. Creating a Workspace
Before starting to work with data in Microsoft Fabric, you need to create a **workspace**. After logging into Fabric, you can create a new workspace from the "Workspaces" section in the left menu and select the appropriate license model.

### 2. Lakehouse and File Upload
A Lakehouse is an environment where data is stored. In this environment, you can upload data in file formats such as CSV. In this step, CSV files for the years 2019, 2020, and 2021 will be downloaded into a folder called "orders" and uploaded to the Fabric Lakehouse to be processed.

### 3. Creating a Notebook
A **notebook** must be created to work with the data. Fabric provides an interactive environment where you can write, execute, and view results using PySpark. A notebook can be divided into code cells and markdown cells.

### 4. Creating a DataFrame
A DataFrame is the primary data structure for data processing in Spark. You can create a DataFrame by reading the uploaded CSV file. It is important to load the file with the appropriate parameters to ensure that the first row is used as the header.

### 5. Filtering the Data
During data analysis, it may be necessary to select only certain rows or group data based on specific criteria. You can use PySpark to select specific columns, perform filtering, and execute grouping operations. For example, you can select customer information who purchased the "Road-250 Red, 52" product.

### 6. Grouping and Aggregating Data
You can group data and perform aggregation operations such as summing or averaging on specific columns. For instance, you could group sales quantities by product or calculate annual sales numbers.

### 7. Transforming the Data
In data engineering processes, transforming the data is a key step for analysis. With PySpark, you can add new columns, transform existing columns, or reshape the dataset. For example, you can split a customer name field into "FirstName" and "LastName" columns.

### 8. Saving the Data
You can save the processed data in an efficient format such as **Parquet** for future analysis. The Parquet format ensures data compression and provides high performance for large-scale data analysis.

### 9. Partitioning the Data
Partitioning data in large datasets can significantly improve data processing and query performance. Spark divides the data based on criteria such as year and month, storing each partition in separate files. This method speeds up data loading and querying operations.

### 10. Querying Data with SQL
Fabric provides the ability to query data using SQL. By using PySpark’s SQL capabilities, you can write SQL queries on your dataset and analyze the results. For example, you can calculate the total gross income for specific years.

### 11. Visualizing the Data
Data visualization helps analysts quickly spot patterns and trends in the data. Fabric offers built-in chart views, and you can also use Python libraries like matplotlib for more advanced visualizations.

### Conclusion
This lab comprehensively teaches the steps of reading, processing, transforming, and visualizing data using Apache Spark and PySpark within the Microsoft Fabric environment. This process is an essential skill for data engineers and data scientists and enables efficient work with large datasets.
