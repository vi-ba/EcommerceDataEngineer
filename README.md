# E-commerce End-to-End Data Integration Pipeline

## Overview
This project demonstrates an end-to-end data engineering pipeline for integrating
and processing data

## Use Case
- Integrate data from Brazilian E-Commerce Public Dataset by Olist 
- Clean and transform raw data into analytics-ready tables
- Enable business metrics such as revenue, order volume, and customer behavior

📄 Detailed use case: [docs/use_case.md](docs/use_case.md)

## Architecture
The pipeline follows a layered data architecture:
- **Ingestion**: Raw data ingestion from source systems
- **Processing**: Data cleaning, transformation, and enrichment
- **Storage**: Structured tables optimized for analytics
- **Orchestration**: Automated pipeline execution

📄 Architecture details: [docs/architecture.md](docs/architecture.md)

## Tech Stack
- **Language**: Python, SQL
- **Data Processing**: Pandas / PySpark
- **Storage**: PostgreSQL / Data Lake (S3 / local)
- **Orchestration**: Airflow
- **Version Control**: Git, GitHub
- **Containerization (optional)**: Docker

## Data Flow
1. Ingest raw e-commerce data
2. Validate and clean data
3. Apply transformations and business logic
4. Load curated datasets into analytics layer

## Project Structure
```text
├── data/
├── src/
├── dags/
├── docs/
│   ├── use_case.md
│   ├── architecture.md
├── README.md
