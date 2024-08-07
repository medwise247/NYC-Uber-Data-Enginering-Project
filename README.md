# NYC Uber Data Analytics | Modern Data Engineering GCP Project Using Mage AI

## Introduction
This project delves into Uber data analytics by leveraging advanced data engineering techniques on the Google Cloud Platform (GCP). We will use a range of powerful tools, including Mage.ai to build an efficient ETL pipeline, BigQuery for robust data warehousing, Looker Studio for insightful data visualization, and Cloud Storage for seamless data management throughout the entire process. This comprehensive strategy will allow us to extract valuable insights from Uber's extensive datasets and improve decision-making capabilities.

## Architecture
![Project Architecture](architecture.jpg)

## Technology Stake
1. Programming & Scripting Languages:
    - Python
    - SQL 
2. Google Cloud Platform:
    - Google Storage
    - Google Engine
    - Big Query
    - Looker Studio
3. Modern Data Pipeline Tool:
    - Mage.AI - https://www.mage.ai

## Uber Dataset Overview
The Uber dataset provides detailed information on rides, including timestamps, locations, trip distances, and fare details. This data is essential for analyzing travel patterns, peak hours, and geographic distribution of rides.

## Data Dictionary

| Column Name            | Description                                        |
|------------------------|----------------------------------------------------|
| `VendorID`             | ID of the vendor providing the trip                |
| `tpep_pickup_datetime` | Timestamp of when the ride started                 |
| `tpep_dropoff_datetime`| Timestamp of when the ride ended                   |
| `passenger_count`      | Number of passengers in the ride                   |
| `trip_distance`        | Distance traveled during the ride (in miles)       |
| `pickup_longitude`     | GPS longitude of the pickup location               |
| `pickup_latitude`      | GPS latitude of the pickup location                |
| `RatecodeID`           | Rate code ID assigned to the trip                  |
| `store_and_fwd_flag`   | Flag indicating if the trip record was held in vehicle memory before sending to the vendor |
| `dropoff_longitude`    | GPS longitude of the dropoff location              |
| `dropoff_latitude`     | GPS latitude of the dropoff location               |
| `payment_type`         | Mode of payment (e.g., card, cash)                 |
| `fare_amount`          | Fare charged for the trip                          |
| `extra`                | Extra charges during the trip                      |
| `mta_tax`              | MTA tax amount                                     |
| `tip_amount`           | Tip amount given by the passenger                  |
| `tolls_amount`         | Tolls paid during the trip                         |
| `improvement_surcharge`| Surcharge for improvement                          |
| `total_amount`         | Total amount paid for the trip                     |

Here is the dataset CSV format: https://github.com/medwise247/Uber_Data-Enginering_Project/blob/main/data/uber_data.csv
## More Info About Dataset
Original Data Source: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
Original Data Dictionary: https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
![Project Data Model](data_model.jpeg)

## Script for Project
[Extract Python File](mage-files/extract.py)

[Transform Extract Python File](mage-files/transform.py)

[Load Python File](mage-files/load.py)


