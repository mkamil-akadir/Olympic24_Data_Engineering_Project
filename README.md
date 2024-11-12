>**Disclaimer** : All credit for the original project goes to [Darshil Parmar](https://github.com/darshilparmar), and this repository is created solely for educational purposes. It represents my learning process and understanding of the data engineering workflow using Azure services.

# Data Engineering Project - Paris Olympic Dataset

## **Overview**

This project follows the data engineering process demonstrated by [Darshil Parmar](https://github.com/darshilparmar). All credit for the original project and its resources goes to Darshil Parmar. This repository showcases my learning journey in data engineering using Azure services and the Paris Olympic dataset.

The objective of this project was to understand the end-to-end process of data ingestion, processing, analysis, and visualization using Azure Data Factory, Azure Data Lake Storage (ADLS2), Azure Databricks, Azure Synapse Analytics, and Power BI.

## **Data Source**

The dataset used in this project is the **Paris Olympic dataset**, which was originally provided by Darshil Parmar. You can access the dataset through the following GitHub link:  
[Paris Olympic Dataset](https://github.com/darshilparmar/tokyo-olympic-azure-data-engineering-project/tree/61c85acb7978897c2dbcd8453890de2f94a49a14/data)

## **Tools Used**

- **Azure Data Factory**: For data ingestion and orchestration
- **Azure Data Lake Storage (ADLS2)**: For raw data storage
- **Azure Databricks**: For data processing and cleaning
- **Azure Synapse Analytics**: For data warehousing and analysis
- **Power BI (PBI)**: For data visualization and reporting

## **Process Flow**

1. **Data Ingestion**:  
   Using **Azure Data Factory**, data is ingested by pulling raw CSV files from the GitHub repository (HTTP path) and then stored in **Azure Data Lake Storage (ADLS2)**.

2. **Data Cleaning & Transformation**:  
   The raw data is processed in **Azure Databricks** for necessary cleaning and transformations to prepare it for analysis.

3. **Storage**:  
   The cleaned and processed data is then stored back in **Azure Data Lake Storage (ADLS2)** for further use.

4. **Data Warehouse**:  
   The processed data is pulled into **Azure Synapse Analytics** where further aggregation and analysis are performed.

5. **Data Visualization**:  
   The aggregated data from **Azure Synapse Analytics** is pulled into **Power BI** for creating insightful visualizations for reporting.

## **Challenges**

- **Azure Account**:  
   The process requires an active **Microsoft Azure account** (I am using a free trial account with 12 months of access and one month of free credits). There is an ongoing cost associated with Azure services once the trial and credits expire.

- **New Learning Curve**:  
   This was my first time working on a full data engineering pipeline, and I faced challenges in understanding and working with Azure services, which was a new learning experience.

- **File Format Issue**:  
   When pulling data into **Azure Synapse Analytics**, the processed CSV files had to be converted to **Parquet** format to avoid errors. I had to research and troubleshoot this issue to ensure smooth data transfer.

## **What I Learned**

- **Data Engineering Process Flow**:  
   I gained hands-on experience with the end-to-end data engineering process flow, from data ingestion to data transformation, storage, analysis, and visualization.

- **Azure Services**:  
   I learned about the capabilities and usage of various Azure services for data engineering, including **Azure Data Factory**, **Azure Data Lake Storage**, **Azure Databricks**, and **Azure Synapse Analytics**. Each service plays a crucial role in modern data engineering pipelines.


Feel free to reach out if you want to discuss the project further or have any questions!
