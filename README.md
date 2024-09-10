## Project Overview
In this project, we will build an ETL (Extract, Transform, Load) pipeline using the spotify API. The pipeline will retrieve data from spotify API, transform it to desired format(structured), and load it into Local and Cloud(AWS S3, Azure Datalake).

## Problem Statement
Build a data pipeline to extract, process, and store the top 100 trending Telugu songs from the Spotify API. The pipeline should be able to fetch the data, transform it into a structured format, and store it in multiple locations including local storage, AWS S3, and Azure Data Lake for further analysis.

## Architecture Design

## Steps Involved
- **Integrating with Spotify API and Extracting Data**:
  - Extract the unstructured data from Spotify's API using proper authentication methods for further processing.
    
- **Data Processing in Jupyter Notebook (Python)**:
  - Create a Python script to connect to the Spotify API.
  - Transform the unstructured data into a structured format using Python and Pandas.
    
- **Load the Structure data into Local, AWS S3 and Azure Data Lake Integration**:
  - Stored the transformed data in three locations: locally for immediate access, on AWS S3 for scalable and secure cloud storage, and in Azure Data Lake for long-       term storage and          advanced analytics.
 
## Unstructured Data Design
    ![Unstructured Json](https://github.com/gattukarthik/ETL-unstructured-cloud/blob/main/SPOTIFY_API.png?raw=true)

## Step-by-Step Approach
   - Step 1: Register on Spotify account(create an account in Soptify Developer Website -> create app and get credentials(CLIENT_ID and CLIENT_SECRET))
   - Step 2: Explore Spotify Library using Python(Import necessary Libraries and use SpotifyClientCredentials will be used to make authenticated requests to fetch data for spotify client)
   - Step 3: Extract unstructured data from the source(Spotify API) and transform the data and convert entire proper dataframe using pandas
   - Step 4: Convert the Dataframe into csv file and store it into local storage.
   - Step 5: Import necessary Libraries for Authenticate the AWS and Azure Storage account.
   - Step 6: Load the csv file into AWS S3 and Azure Datalake.

## Conclusion
   -We have successfully extracted the top 100 trending Telugu songs, including details about the artists who performed them and the movies they are associated with. Each piece of         
    information has been organized into separate tables, enabling comprehensive analysis and insights into the music trends.
  
