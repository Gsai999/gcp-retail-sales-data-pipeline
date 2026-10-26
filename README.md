# GCP Retail Sales Data Pipeline — Project 1

**Status:** In Progress

## Overview

This project aims to build a batch data engineering pipeline for multi-year retail sales data using Python and Google Cloud Platform (GCP).

The goal is to prepare reliable, structured data for business analysis by validating source files, handling data quality issues, and loading processed records into BigQuery.

## Architecture

![GCP Retail Sales Data Pipeline Architecture](docs/gcp-retail-sales-architecture.png)

*Planned architecture — cloud components will be updated as they are implemented and tested.*

## Business Problem

Retail sales data is available across multiple yearly files, along with order returns and manager information. Analysing these files separately makes it harder to produce consistent business reports.

This project aims to consolidate the data and prepare it for reliable sales and profitability analysis.

## Technology Stack

- **Python:** Pipeline logic and data processing
- **pandas:** Reading, validating, and transforming datasets
- **Google Cloud Storage:** Planned storage for raw source files
- **BigQuery:** Planned cloud data warehouse
- **SQL:** Planned transformations and business analysis
- **Git and GitHub:** Version control and project documentation

## Planned Pipeline Workflow

1. Inspect and validate the source files.
2. Store original files in Google Cloud Storage.
3. Use Python and pandas to clean and standardise records.
4. Load validated data into BigQuery.
5. Apply SQL transformations and data quality checks.
6. Analyse sales, profit, regional performance, and returns.

## Data Quality Checks

Initial local exploration includes:

- Row and column counts
- Missing-value checks
- Exact duplicate-row detection
- Column-name and file-format inspection

Further validation rules will be added as the pipeline develops.

## Current Progress

- [x] Created the local project folder.
- [x] Loaded a sales CSV using Python and pandas.
- [x] Inspected dataset structure and initial data quality.
- [x] Created the GitHub repository.
- [x] Added the planned architecture diagram.
- [ ] Finalise and test the Python pipeline.
- [ ] Upload source data to Google Cloud Storage.
- [ ] Create BigQuery tables and load data.
- [ ] Build SQL transformations and analytical queries.
- [ ] Document final results and execution instructions.

## Expected Outcomes

- A repeatable data processing workflow
- Structured sales data suitable for analytics
- Data quality checks and validation results
- SQL analysis of sales, profit, and returns

## Disclaimer

This is a learning and portfolio project. Cloud services and pipeline stages marked as planned are not yet implemented. Only datasets that are permitted to be shared will be published in this repository.
