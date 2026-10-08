# CareFlow – Azure Data Factory

This repository contains the Azure Data Factory (ADF) implementation of the CareFlow data engineering project.

The repository includes ADF pipelines, datasets, and linked services used to orchestrate and manage data ingestion workflows.

## 🏗️ Project Structure

```text
careFlow_adf_rep/
│
├── dataset/
│   └── ADF Dataset definitions
│
├── linkedService/
│   └── ADF Linked Service definitions
│
├── pipeline/
│   └── ADF Pipeline definitions
│
├── publish_config.json
└── README.md
```

## 🔄 Data Pipeline

The ADF pipelines are designed to orchestrate the movement and processing of data between different data sources and the data processing layer.

```text
Source Systems
      │
      ▼
Azure Data Factory
      │
      ├── Linked Services
      │
      ├── Datasets
      │
      └── Pipelines
      │
      ▼
Data Storage / Processing Layer
      │
      ▼
Azure Databricks
      │
      ▼
Delta Tables
```

## ⚙️ Azure Data Factory Components

### Pipelines

ADF pipelines are used to orchestrate the end-to-end data workflow, including data movement, processing, and execution of dependent activities.

The pipeline definitions are available in the `pipeline/` directory.

### Datasets

Datasets define the structure and location of the data used by ADF activities.

Dataset definitions are available in the `dataset/` directory.

### Linked Services

Linked Services contain the connection configuration required by ADF to connect with external data stores and services.

Linked Service definitions are available in the `linkedService/` directory.

## 🔑 Key Concepts Demonstrated

* Azure Data Factory pipeline orchestration
* Linked Services
* Datasets
* Copy Data activity
* Pipeline parameters
* Dynamic content and expressions
* Activity dependencies
* Data ingestion workflows
* Integration with Azure data services
* ADF and Azure Databricks integration

## 🛠️ Technology Stack

* **Azure Data Factory**
* **Azure Databricks**
* **PySpark**
* **SQL**
* **Delta Lake**
* **Azure Storage**

## 📌 Purpose

The purpose of this repository is to demonstrate practical implementation of Azure Data Factory for data ingestion and pipeline orchestration as part of a modern Azure Data Engineering workflow.

ADF is used for orchestration and data movement, while Azure Databricks can be used for scalable data transformation and processing.

## 🔐 Security

No passwords, access keys, connection strings, or other sensitive credentials should be stored in this repository.

Environment-specific credentials should be configured securely within Azure.

## 👤 Author

**Vishal Chandra**

Data Engineering | Azure Data Factory | Azure Databricks | PySpark | SQL
