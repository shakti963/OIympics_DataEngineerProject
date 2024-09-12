# Tokyo Olympic Data Analysis on Azure

The **Tokyo Olympic Data Analysis on Azure** project is a complete solution for analyzing and visualizing Olympic Games data using Azure cloud services. This project demonstrates how to use Azure's powerful tools to handle large datasets and uncover insights from historical Olympic data.

## Table of Contents

- [Introduction](#introduction)
- [Architecture](#architecture)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Data Ingestion](#data-ingestion)
  - [Data Processing](#data-processing)
- [Conclusion](#conclusion)

## Introduction

This project builds a full data analysis pipeline on Azure. It involves:

1. **Collecting** raw Olympic data.
2. **Transforming** the data into a clean and structured format.
3. **Analyzing** the data to find meaningful insights.
4. **Visualizing** the results with interactive reports.

The project uses Azure Databricks, Azure Data Factory, and other Azure services to achieve this.

## Architecture
![architecture ](https://github.com/shakti963/OIympics_DataEngineerProject/blob/main/images/Archietecture.png)

### Overview

The project architecture includes several key components:

- **Azure Databricks**: Used for processing and analyzing the data. It provides a collaborative environment to handle large-scale data tasks and perform complex
  transformations.

- **Azure Data Factory**: Manages the data workflow, including extracting data from various sources, transforming it, and scheduling tasks. It ensures smooth data movement and processing.

- **Azure Storage**: Acts as the data lake where both raw and processed data are stored. It also supports data durability and scalability.

- **Azure SQL Database**: Stores the cleaned data, making it easy to query and analyze.

- **Power BI**: Connects to Azure SQL Database to create interactive dashboards and reports for visualizing the data.

## Technologies Used

- Azure Databricks
- Azure Data Factory
- Azure Storage
- Azure SQL Database
- Power BI

## Getting Started

### Prerequisites

- An Azure subscription
- An Azure Databricks workspace
- An Azure Data Factory instance

### Data Ingestion

Data ingestion is handled by Azure Data Factory. It collects data from different sources and loads it into Azure Storage for initial processing.

### Data Processing

Azure Databricks is used for cleaning and transforming the raw data into a format ready for analysis.

## Conclusion

The Tokyo Olympic Data Analysis on Azure project shows how to use Azure services for managing, processing, and visualizing large datasets. By following the instructions and guides provided in this repository, you can adapt this setup for other data projects or build on this example.

Happy analyzing!
