# Airbnb-DataEngineering-AWS-S3-Databricks

In this project, I have placed the data in AWS S3 bucket. I have created an ETL pipeline which makes use of databricks cluster and spark.

Project Steps:

Created one IAM user called "ashproj" with "AdministeratorAccess" policy .
I used its key and secret key to build an Databricks cluster and configured it. 
Extracted the data using spark from the AWS S3 by mounting the S3 onto databricks cluster
Analysized the extracted data and transformed the data and cleaned the data to remove abnormalities and null values.
Stored the fixed data in AWS S3 in parquet format
Performed EDA on data using spark SQL
