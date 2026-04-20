# Python + Data Engineering Roadmap (12 Weeks)

## How to use this roadmap

- Study 5-6 days each week, 90-120 minutes per day.
- For each topic folder, work in this order: `concepts.ipynb` -> `exercises.ipynb` -> `solutions.ipynb`.
- Do not open `solutions.ipynb` until you attempt all exercises.
- At the end of each week, complete the revision notebook in `05-weekly-revisions/`.

## Study protocol (daily)

1. Warm-up (10 min): revisit yesterday's notes and one past bug.
2. Concept pass (35-45 min): read markdown, run examples, make one variation.
3. Practice pass (35-45 min): complete exercises without looking at solutions.
4. Reflection (10 min): write 3 bullet points: what clicked, what failed, what to revise.

## Self-check rules

Move forward only if all are true:

- You can solve at least 70 percent of exercises without copying.
- You can explain each topic in your own words with one real example.
- You can debug your own code errors in less than 10 minutes.

If not, repeat that topic next day with two fresh custom exercises.

## 12-week curriculum

### Week 1
- Data structures: lists, tuples, sets, dicts
- Comprehensions and generators (memory-efficient processing)
- Revision: week-01-revision notebook

### Week 2
- Advanced functions (`*args`, `**kwargs`, lambda, map/filter/reduce, decorators)
- Error handling and retries for pipelines
- File I/O, context managers, `pathlib`
- Revision: week-02-revision notebook

### Week 3
- OOP, classes, dataclasses
- Modules, packages, virtual environments
- Pythonic idioms (`enumerate`, `zip`, unpacking)

### Week 4
- NumPy foundations
- Pandas fundamentals

### Week 5
- Pandas advanced transforms
- CSV, JSON, Parquet
- Datetime handling

### Week 6
- SQL basics and joins
- Aggregations and window functions

### Week 7
- CTEs and subqueries
- Python + SQL integration
- Portfolio Project 1: CSV to SQLite ETL

### Week 8
- APIs, pagination, retries, rate limiting
- Chunking large data
- Portfolio Project 2: API to Postgres pipeline

### Week 9
- DuckDB + Polars
- Portfolio Project 3: Parquet data lake

### Week 10
- PySpark DataFrames and Spark SQL
- UDF basics and joins at scale

### Week 11
- Airflow orchestration and scheduling
- Cloud storage with S3 and boto3
- Portfolio Project 4: Airflow daily DAG

### Week 12
- Data quality with Pandera
- Testing with pytest
- Logging and monitoring
- Portfolio Project 6: end-to-end capstone

## Weekly revision framework

Every weekly revision notebook includes:

- 10 mixed questions (easy -> hard)
- 1 timed mini-test (45 minutes)
- 1 debug challenge from intentionally broken code
- 1 reflection section

## DE interview prep built into this roadmap

After each week, answer these:

- What problem does this tool/topic solve in production?
- What are the common failure modes?
- How would you monitor and test it?

By Week 12, prepare a portfolio walkthrough:

- Problem statement
- Data source and schema decisions
- Pipeline design and idempotency strategy
- Validation and observability
- Trade-offs and future improvements
