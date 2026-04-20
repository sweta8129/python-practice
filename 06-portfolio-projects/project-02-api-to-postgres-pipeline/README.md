# API to Postgres Pipeline

## Objective
Ingest paginated API data with retries and upsert into Postgres with incremental loads.

## Enterprise scenario
This project mirrors a production data engineering workflow with reliability, observability, and repeatability as first-class goals.

## Suggested datasets
- Public open-data source (CSV/JSON/API)
- Add at least one evolving schema field to simulate real-world drift

## Architecture
- Ingestion layer: pull raw data
- Raw zone: immutable landing data
- Transform layer: clean and normalize
- Curated layer: analytics-ready outputs
- Validation layer: row count and schema checks

## Acceptance criteria
- Pipeline is idempotent (safe to rerun)
- Handles bad data without full job failure
- Includes basic tests in `tests/`
- Includes logs and a simple run report
- Documents assumptions and trade-offs

## Deliverables
- Working code under `src/`
- At least one notebook explaining transformations
- A short runbook section: how to execute and verify
