# E-Commerce-with-Hive-And-Spark

This is an E-Commerce Analytics project that leverages AWS Services like EC2, Containerization techniques like Docker, data warehouse (Apache Hive), Apache Sqoop and Apache Spark to create a database with and perform Analytics on it on the Cloud. 
We create an EC2 Linux Instance, set up Docker on it and create an image. We create an Ingestion Pipeline by ingesting data to HDFS via Apache Sqoop, and transfer the files to Hive. We process the data using Apache Spark and transfer the processed Parquet file to Hive.

## Approach
- Create and launch an AWS EC2 instance
- Prepare docker-compse file and create images on EC2 machine
- Create tables in MySQL
- Load from MySQL into HDFS using Sqoop commands
- Move data form HDFS to Hive
- Extract Customer Information from data using Scala and store as a parquet
- Move parquet from Spark to Hive
- Create tables in Hive and load data from parquet into tables

## Tech Stack

Language: Scala, SQL
Services: Git, AWS EC2, Docker, Apache Sqoop, Apache Hive, Apache Spark, 

## Further tasks

- Use Terraform to automate infrastructure creation
- Prepare an Interactive Dashboard
- Use AirFlow or other orchestration services like Luigi, Dagster or Prefect to schedule and orchestrate
