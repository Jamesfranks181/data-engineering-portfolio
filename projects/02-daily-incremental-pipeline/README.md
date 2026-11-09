# Project 2 — Daily Incremental Pipeline

**Goal:** Prove handling of real, changing data — not just one-off loads.

**Stack:** Python → S3 landing → Snowflake → dbt incremental models → data quality checks

**Data:** A daily-updating public API (weather / GitHub Archive — final choice in Phase 3)

## Steps
1. Daily extract appended to S3 landing zone, partitioned by date
2. Load new files only into Snowflake
3. dbt incremental model processes only new/changed rows
4. Quality checks: freshness, row counts, null checks — fail loudly, not silently

Status: Planned for Phase 3.
