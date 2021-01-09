# AWS-Cloud-ETL
Cloud ETL

# Cloud ETL with S3, PySpark, and RDS

### Instructions

* As the sole data person at your new company, you have been tasked with cleaning the data from an Excel spreadsheet—which has been exported as a CSV—and creating an SQL database with this data. In other words, you will be performing ETL.

* Take a moment to review the SQL table schemata, which reflect the requirements for the company's new database. Your company will be using S3 for file storage and RDS to host SQL databases.

* Then, complete the following tasks:

  * Upload the *employees.csv* file in the *Resources* folder to S3. **Note:** be sure to make the S3 bucket public.

  * Upload the unsolved jupyter notebook to Colab and use Spark to clean and transform the data.

  * With the *schema.sql* file from the *Resources* folder, use pgAdmin to create the table schemata in RDS.

  * Load the data from Pandas DataFrames into RDS.

### Attribution

The dataset was sourced from [https://github.com/Microsoft/sql-server-samples](https://github.com/Microsoft/sql-server-samples).
