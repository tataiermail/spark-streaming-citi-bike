
# spark-streaming-citi-bike
Integrated Data Pipeline using: Spark Batch and Structured Streaming for NYC Bike Rental data, provided by Citi.

### Objectives
* Static Analysis of Historical New York City Bike-ride & Station Data
* Real-Time Analysis of similar Data via Streaming Pipeline
* Cloud Agnostic Data Pipeline
* Streamlined approach for Batch & Streaming Data

![](https://i.ibb.co/6sQT4b9/Screenshot-from-2020-10-27-14-02-42.png)

### Data Source
* **[https://www.citibikenyc.com/system-data](https://www.citibikenyc.com/system-data)**

#### Batch Data Source
* Monthly trip data in .CSV.ZIP format
* Contains station details
* Basic rider demographics

#### Streaming Data Source
* 20+ REST APIs
* Station Status API for this Demo
* https://gbfs.citibikenyc.com/gbfs/en/station_status.json


### Technical Features
* Same Spark Framework for Batch & Streaming
* Realtime API Integration
* Nested JSON Parsing & Array Flattening
* ACID Compliance & Time Travel using Delta Lake
* Integration of Batch & Realtime Data during Analytics
* Batch & Real-time Analytics


### Requisites
* Databricks Runtime - single Node/Community Edition is fine
* Python 3
* Spark 2.4.x

