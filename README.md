# **Heart Disease Prediction with Azure Data Factory and Databricks**

## **Overview**
This project leverages **Azure Data Factory (ADF)** and **Databricks** for processing heart disease prediction data. It integrates **Azure Blob Storage** and **PySpark** to clean, analyze, and transform data for further predictive modeling.

## **Technologies Used**
- **Cloud Services:** Azure Data Factory, Azure Blob Storage, Azure Data Lake
- **Processing Frameworks:** Databricks, PySpark
- **Languages:** Python, SQL
- **Storage Format:** Parquet

## **Project Architecture**
Below is the architecture of the data pipeline used in this project:

![Project Architecture](images/architecture.png)

## **Project Highlights**
- Configured **Azure Blob Storage** to store raw heart disease data.
- Utilized **Azure Data Factory (ADF)** to orchestrate data movement and transformation.
- Processed the dataset in **Databricks (PySpark)** by:
  - Handling missing values and data inconsistencies.
  - Performing **correlation analysis** between features and the target variable.
  - Applying **one-hot encoding** for categorical variables.
  - Transforming data for better usability in machine learning models.
- Stored the processed data in **Azure Data Lake** for further analysis.

## **Next Steps**
- Implement predictive modeling using **machine learning algorithms** on Databricks.
- Automate pipeline execution with **ADF event triggers**.
- Deploy results into a **dashboard or visualization tool**.
