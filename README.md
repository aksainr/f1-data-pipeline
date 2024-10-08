# F1 Data Pipeline
This project focuses on constructing a comprehensive and seamlessly integrated data pipeline. The main objective is to retrieve the latest race information by using the Ergast F1 Data source and storing the obtained data in Google Cloud Storage. After the data is collected, the data is processed by applying column filters, performing transformations, and then loaded into BigQuery. To enhance the dataset, DBT is leveraged to generate additional columns, tables and views. Finally Google Looker Studio is used to build dashboards to visualize the data and perform analysis.

## Project Components
The project consists of the following components:

Data Extraction: Data is extracted from the Ergast API, providing comprehensive race information.

Data Storage: The extracted data is saved to Google Cloud Storage (GCS) for further processing.

Data Loading: The transformed data is loaded into BigQuery for storage and querying.

Orchestration: Prefect manages and monitors the entire pipeline workflow, which is broken down into smaller tasks and flows.

DBT Integration: DBT is utilized to derive new columns and maintain an up-to-date dataset.

Data Visualization: The transformed data is visualized through a looker dashboard for easy analysis.

## Pipeline Architecture
![image](https://github.com/user-attachments/assets/4ef5568e-07b2-405e-8f59-9c3aeae108f2)

[Dashboard Link](https://lookerstudio.google.com/reporting/9fd225dd-a9b8-45d9-87dc-7d7dbae0c841/page/nAHVD)
