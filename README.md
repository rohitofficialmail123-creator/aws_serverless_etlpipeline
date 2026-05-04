# aws_serverless_etlpipeline
An AWS Lambda function that automates an end-to-end ETL (Extract, Transform, Load) pipeline triggered by S3 file upload events. It reads nested JSON order data, flattens it into a structured format, converts it to Parquet, stores it back in S3, and triggers an AWS Glue Crawler to update the data catalog.
