# Spotify_ETL_Pipeline
## Objective: Extract data from SPOTIFY API on weekly basis.
*  Used SPOTIFY API to extract  *TOP SONGS - GLOBAL* Data from Spotify.
*  Used AWS LAMBDA service and wrote a python function to EXTRACT data LOAD on to AWS S3 Bucket.
*  Wrote another AWS LAMBDA function to TRANSFORM data and then store it to another Bucket in AWS S3.
*  Used AWS CRAWLER to infer schema of data and create an AWS CATALOG.
*  Used AWS ATHENA to perform queries on data.

Architecture of the Pipeline
![Architecture](https://github.com/arzanish/Spotify_ETL/assets/54699317/f9c86228-17a2-4480-909a-2b5f2ae9ef22)

