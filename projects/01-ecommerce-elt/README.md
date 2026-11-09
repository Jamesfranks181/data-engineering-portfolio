# Project 1 — E-commerce ELT Pipeline

**Goal:** End-to-end pipeline proving extract, load, transform, orchestration, and dashboard skills.

**Stack:** Python (requests, pandas) → S3 / local landing → Snowflake → dbt → Prefect → Power BI

**Data:** Fake Store API / Olist e-commerce dataset (orders, customers, products)

## Steps
1. Extract: Python script pulls source data, saves raw files unchanged
2. Load: Raw data loaded into Snowflake raw schema
3. Transform: dbt staging models (clean, rename, type) → mart models (sales by product, customer, day) with dbt tests
4. Orchestrate: Prefect flow schedules extract → load → dbt run
5. Serve: Power BI dashboard on mart tables

Status: Not started — begins Week 4 of Phase 1 (mini version), full build in Phase 3.
