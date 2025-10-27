# Spotify-Azure-Data-Engineering
<img width="1920" height="1200" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/d344e357-dd69-4ef5-84d0-ab4fb9686d1f" />

🎧 Spotify Azure Data Engineering Project

An end-to-end data engineering solution built on Microsoft Azure, processing and transforming Spotify data using a modern data stack.

🏗️ Tech Stack

Azure Data Factory (ADF) – Orchestration & data movement

Azure SQL Database – Source system with CDC-enabled tables

Azure Databricks – Data processing with PySpark

Delta Live Tables (DLT) – Managed pipelines for incremental transformations

GitHub – Version control & CI/CD integration

⚙️ Project Features

Incremental ingestion pipelines using Azure Data Factory

Backfilling & looping logic for pipeline automation

Integration with Azure Logic Apps for workflow triggering

Spark streaming with Databricks Autoloader

Metadata-driven PySpark pipelines using Jinja2 templates

Star schema modeling and Slowly Changing Dimensions (SCD) implementation

Delta Live Tables (DLT) for declarative data pipelines

Databricks Asset Bundles for CI/CD and deployment automation
