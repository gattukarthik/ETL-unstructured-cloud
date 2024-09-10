## Project Overview
In this project, we will build an ETL (Extract, Transform, Load) pipeline using the spotify API. The pipeline will retrieve data from spotify API, transform it to desired format(structured), and load it into Local and Cloud(AWS S3, Azure Datalake).

## Problem Statement
Build a data pipeline to extract, process, and store the top 100 trending Telugu songs from the Spotify API. The pipeline should be able to fetch the data, transform it into a structured format, and store it in multiple locations including local storage, AWS S3, and Azure Data Lake for further analysis.

## Architecture

## Steps Involved
- **Integrating with Spotify API and Extracting Data**:
  - Extract the unstructured data from Spotify's API using proper authentication methods for further processing.
    
- **Data Processing in Jupyter Notebook (Python)**:
  - Create a Python script to connect to the Spotify API.
  - Transform the unstructured data into a structured format using Python and Pandas.
    
- **Load the Structure data into Local, AWS S3 and Azure Data Lake Integration**:
  - Stored the transformed data in three locations: locally for immediate access, on AWS S3 for scalable and secure cloud storage, and in Azure Data Lake for long-       term storage and advanced analytics.

