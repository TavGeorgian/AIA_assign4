# Sentiment Analysis on Hotel Reviews Using Azure Services

This project demonstrates performing sentiment analysis on a large dataset of hotel reviews using Microsoft Azure services, with data visualization in Power BI.

## Key Steps in the Project:
- **Data Storage:** 
  - The dataset is uploaded to **[Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/)** for secure and scalable storage.
- **Data Ingestion:**
  - Ingested data into **Azure SQL Database** using **Azure Data Factory** and the **built-in copy task**.
  - Data is retrieved by selecting the **top 1000 rows** for analysis.
- **Data Analysis:**
  - Performed sentiment analysis on the dataset using **Python** and **Jupyter Notebooks**.
  - Analyzed the sentiment of hotel reviews to derive insights into customer experiences.
- **Data Visualization:**
  - Visualized the results using **Power BI**:
    - Retrieved data from Azure SQL Database via **Get Data → Azure → Azure SQL Database**.
    - Created interactive dashboards to display sentiment insights and trends.

## Tools & Technologies:
- **Microsoft Azure**: Blob Storage, Data Factory, Azure SQL Database
- **Power BI**: For data visualization
- **Python (Jupyter Notebook)**: For data processing and sentiment analysis

## Data Source:
- The dataset used in this project is available through **[Kaggle: Hotel Reviews Dataset](https://www.kaggle.com/datasets/)**.
