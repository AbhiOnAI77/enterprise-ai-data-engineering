# Enterprise AI Data Engineering

Hands-on projects, notes, and case studies combining Azure Data Factory (ADF) dataflows with enterprise AI and LLMOps. This repository demonstrates how data engineering patterns can power real-world AI use cases, from ingestion and transformation to machine learning pipelines and retrieval-augmented generation (RAG).

Each project is designed around realistic business problems, complete with input datasets, SQL equivalents, transformation logic, and pipeline patterns that reflect enterprise-scale scenarios.

---

## Repository Structure

- **Project 1 – Azure SQL to Data Lake Pipeline: Customer 360 Data Ingestion for Enterprise AI**  
  Demonstrates how to build a production-ready ingestion pipeline using Azure Data Factory that moves customer data from Azure SQL Database into Azure Data Lake Gen2 in Parquet format.  
  This ingestion layer is the foundation for Customer 360 platforms, churn prediction models, recommendation engines, feature stores, and LLM-powered applications.  
  [View Project →](./AzureSQL_to_DataLake/README.md)

- *(More projects will be added here as the repository grows.)*

---

## Takeaways

- How to design ingestion pipelines using Azure Data Factory for enterprise-scale AI.
- How to transform structured data into AI-ready formats like Parquet.
- How to integrate ingestion pipelines with downstream ML, feature store, and LLM workflows.
- How to translate data engineering logic into SQL equivalents for validation and reproducibility.

---

## Getting Started

1. Explore **Project 1** to understand the end-to-end ingestion pattern from Azure SQL to Data Lake.
2. Follow the pipeline setup steps in the project README.
3. Extend the pattern to other operational tables or use cases.
4. Combine multiple pipelines to build a feature store or feed RAG pipelines.

---

## Roadmap

- Project 2 – Event-driven Ingestion and Stream Processing for AI Workloads  
- Project 3 – Feature Store Construction for Predictive and Prescriptive AI  
- Project 4 – LLMOps Data Layer: Building Context Stores for RAG Pipelines  

Stay tuned for upcoming additions.
