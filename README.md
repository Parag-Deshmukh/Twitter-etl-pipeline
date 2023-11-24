# ETL Project: Twitter Data Extraction and Transformation

## Overview
This ETL (Extract, Transform, Load) project involves fetching data from Twitter, performing transformations using pandas, and storing the processed data in an S3 bucket. The entire workflow is orchestrated using Apache Airflow on an EC2 instance.

## Project Structure
- `etl_script.py`: Python script for extracting and transforming Twitter data.
- `airflow_dag.py`: Apache Airflow DAG (Directed Acyclic Graph) script for scheduling and orchestrating the ETL workflow.
- `requirements.txt`: List of Python dependencies.

## Prerequisites
1. **Twitter Developer Account:**
   - Obtain API keys and tokens from the [Twitter Developer portal](https://developer.twitter.com/en/apps).

2. **AWS Account:**
   - Set up an S3 bucket for storing the processed data.
   - Obtain AWS access key and secret key with S3 permissions.

3. **EC2 Instance (for Airflow):**
   - Launch an EC2 instance for running the Airflow scheduler and tasks.
   - Ensure the instance has the necessary permissions to access Twitter API and S3.

## Installation
1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-repo.git
