Sentiment Analysis on Hotel Reviews Using Azure Services

This project involves performing sentiment analysis on a large dataset of hotel reviews using Microsoft Azure's powerful cloud services. The primary goal is to analyze customer sentiments and visualize the results for insights using Power BI.

Key Components:
Azure Blob Storage: The dataset is uploaded to Azure Blob Storage for secure and scalable storage.

Azure Data Factory: Data ingestion is performed through Azure Data Factory, where data is transferred from the blob storage to an Azure SQL Database using the built-in copy task.

Data Analysis & SQL: In Azure SQL Database, the data is queried and visualized to extract insights. The top 1000 rows are selected for the analysis.

Power BI: Data visualization is done using Power BI, where I retrieve the data from Azure SQL Database to create interactive dashboards, helping stakeholders make data-driven decisions.

Tools & Technologies Used:
Microsoft Azure: Blob Storage, Data Factory, Azure SQL Database

Power BI: For interactive data visualization

Python (Jupyter Notebook): For data processing and sentiment analysis

This project demonstrates the integration of cloud services and data analytics tools to effectively analyze large datasets and extract meaningful insights.
