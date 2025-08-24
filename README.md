# Azure E2E data eng project (Earthquake data pipeline)- databricks

## Project Overview

This project is an end-to-end data pipeline built on Microsoft Azure to ingest, transform, and analyze earthquake data. The goal is to provide a comprehensive and scalable solution for near-real-time data processing, enabling insights into seismic activity.

## Data Source

The primary data source for this pipeline is the [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). The pipeline ingests GeoJSON data from their API, which provides a live feed of earthquake events.

## Architecture

The data pipeline is orchestrated using Azure services to ensure reliability, scalability, and cost-effectiveness. 


* Configure Azure Databricks and securely access data in Azure Storage.
* Process and transform data using Databricks notebooks (bronze, silver, gold).
* Automate data pipelines with Azure Data Factory.

### Tools & Technologies

* Azure Databricks
* Azure Data Factory