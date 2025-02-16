*Heart Disease Prediction with Azure Data Factory and Databricks*
**Overview**
This project leverages Azure Data Factory (ADF) and Databricks for processing heart disease prediction data. It integrates Azure Blob Storage and PySpark to clean, analyze, and transform data for further predictive modeling.

Project Architecture
The following diagram illustrates the architecture used in this project:

<p align="center"> <img src="Screenshot 2025-01-08 130519.png" alt="Project Architecture" width="70%"> </p>
Technologies Used
Cloud Services: Azure Data Factory, Azure Blob Storage, Azure Data Lake
Processing Frameworks: Databricks, PySpark
Languages: Python, SQL
Storage Format: Parquet
Project Highlights
✅ Azure Blob Storage was used to store raw heart disease data.
✅ Azure Data Factory (ADF) orchestrated data movement and transformation workflows.
✅ Databricks (PySpark) handled:

Data cleaning and missing value imputation.
Correlation analysis between features and the target variable.
One-hot encoding for categorical variables.
Data transformation for improved model usability.
✅ The processed dataset was stored in Azure Data Lake for further analysis.
Next Steps
📌 Implement predictive modeling using machine learning algorithms on Databricks.
📌 Automate pipeline execution with ADF event triggers.
📌 Deploy results into a dashboard or visualization tool.

