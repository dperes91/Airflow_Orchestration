# Project Overview
This project involves loading data into a Snowflake database, utilizing dbt for data transformation, and orchestrating the entire process with Apache Airflow. Below is an outline of the key components:

### Tools and Technologies Used:
DBT: Used for data transformation and modeling.
Snowflake: Serves as the data warehousing solution.
Apache Airflow: Orchestrates the data loading and transformation processes.
Docker: Containerizes the Airflow environment for easy deployment and management.

### Project Workflow:
1. Data Loading & Transformation:

- Data is loaded into the Snowflake database.
- dbt is configured to handle the transformation logic using YAML files, which define the connection to Snowflake and the target schema for data loading.

2. Orchestration with Airflow:

- Apache Airflow is used to manage and schedule the data workflows.
- A Dockerfile is provided to containerize Airflow, ensuring a consistent and replicable environment.

### Configuration:
- Snowflake Connection: Configuration is managed via YAML files, specifying access credentials and target schemas within Snowflake.
- Airflow Setup: Docker is used to containerize the Airflow environment, with the necessary configurations stored in a Dockerfile, allowing for streamlined setup and deployment.


This setup ensures a robust, scalable, and easily maintainable data pipeline, leveraging the strengths of dbt, Snowflake, and Airflow.
