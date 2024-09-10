## Project Overview
In this project, we will build an ETL (Extract, Transform, Load) pipeline using the spotify API. The pipeline will retrieve data from spotify API, transform it to desired format(structured), and load it into Local and Cloud(AWS s3, Azure Datalake).

## Steps Involved

- **Integrating with Spotify API and Extracting Data**:
  - Authenticate and access Spotify's API.
  - Extract the desired data, such as track details, playlists, artists, and other metadata.

- **Deploying Code on AWS Lambda for Data Extraction**:
  - Create a Python script to connect to the Spotify API.
  - Package and deploy the code to AWS Lambda to ensure scalable and serverless execution.

- **Adding Trigger to Run the Extraction Automatically**:
  - Set up a CloudWatch Event or API Gateway trigger to run the Lambda function on a scheduled basis (e.g., daily, weekly) or on-demand.

- **Writing Transformation Function**:
  - Build a function to clean, normalize, and transform the extracted data for downstream processing and analysis.
  - The function could include data deduplication, formatting, or filtering as necessary.

- **Building Automated Trigger for Transformation Function**:
  - Add an automated trigger (Lambda or Step Functions) to invoke the transformation process after the data extraction is complete.

- **Store Files on S3 Properly**:
  - Organize and store the raw and transformed data files in AWS S3 with a structured folder hierarchy (e.g., by date or data type).
  - Ensure proper file formats like CSV, JSON, or Parquet for compatibility with data analysis tools.

- **Building Analytics Tables on Data Files Using Glue and Athena**:
  - Set up AWS Glue jobs to catalog and transform the data.
  - Define Athena tables to query and analyze the processed data in S3 using SQL queries.


