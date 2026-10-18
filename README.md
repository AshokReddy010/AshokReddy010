# Ashok Reddy Bhimavarapu

Data Analyst at Broadridge, with over four years making numbers trustworthy in financial services, healthcare and technology: SQL and dbt data models, automated reconciliation and data quality checks, and the dashboards built on top. M.S. in Information Science (AI and Machine Learning), University at Albany.

**Portfolio:** [ashokreddy010.github.io](https://ashokreddy010.github.io) · **LinkedIn:** [linkedin.com/in/ashokreddy1](https://www.linkedin.com/in/ashokreddy1)

## Projects

Ten projects, each with tests and CI, and each with something you can open and use: a live dashboard, a status page updated by a scheduled pipeline, or a tool that runs in the browser.

| Project | What it is | Live | Tools |
|:--|:--|:--|:--|
| [Fund Proxy Voting Analysis](https://github.com/AshokReddy010/fund-proxy-voting) | 73.8 million SEC fund votes from 12,416 funds, testing whether ESG-named funds vote differently. Tested dbt pipeline, proposal matching, LLM labelling scored on a held-out set (91%). | [Explorer](https://ashokreddy010.github.io/fund-proxy-voting/) | Python, DuckDB, dbt, BigQuery, LLM evaluation |
| [Same Diagnosis, Different Bill](https://github.com/AshokReddy010/medicare-cost-analysis) | Every CMS Medicare inpatient release, 2013–2024 (2.1M rows), modelled to compare what hospitals bill with what they are paid, case-mix adjusted. Refreshed monthly. | [Dashboard](https://ashokreddy010.github.io/medicare-cost-analysis/) | dbt, DuckDB, SQL, Python, GitHub Actions |
| [SQL Bench](https://github.com/AshokReddy010/text-to-sql-eval) | 50 business questions over a realistic DuckDB warehouse, scoring language models by whether their SQL returns the right answer, in a read-only sandbox, with confidence intervals. | [Leaderboard](https://ashokreddy010.github.io/text-to-sql-eval/) | Python, DuckDB, sqlglot, LLM evaluation |
| [Feed Watch](https://github.com/AshokReddy010/pipeline-observability) | Data observability running every 3 hours on three public APIs: freshness, volume, schema, completeness and drift checks, with incidents raised as GitHub issues. | [Status page](https://ashokreddy010.github.io/pipeline-observability/) | Python, pandas, anomaly detection, GitHub Actions |
| [Data Contract Guard](https://github.com/AshokReddy010/data-contract-guard) | YAML data contracts enforced in CI: validate files, draft contracts from data, and flag breaking schema changes. Ships as a GitHub Action. 75 tests. | [Playground](https://ashokreddy010.github.io/data-contract-guard/) | Python, pandas, GitHub Actions, Pyodide |
| [NYC 311 Pulse](https://github.com/AshokReddy010/nyc-311-pulse) | A daily briefing on New York's 311 requests: unusual complaint types for the weekday, a map, trends and agency closure speed. Refreshed every morning. | [Dashboard](https://ashokreddy010.github.io/nyc-311-pulse/) | Python, pandas, Socrata API, Leaflet |
| [Data Validation Framework](https://github.com/AshokReddy010/data-validation-framework) | Two-level reconciliation of three systems. A live console injects random faults daily and scores whether every one is caught with the right reason. | [Console](https://ashokreddy010.github.io/data-validation-framework/) | SQL, dbt, DuckDB, Python |
| [Olist Analytics Engineering](https://github.com/AshokReddy010/olist-analytics-engineering) | Ten raw e-commerce tables modelled into tested dbt marts (24 models, 80 tests), a lead-scoring model, and a web dashboard. | [Dashboard](https://ashokreddy010.github.io/olist-analytics-engineering/) | dbt, DuckDB, SQL, Python, Power BI |
| [A/B Testing Toolkit](https://github.com/AshokReddy010/ab-testing-toolkit) | Experiment planning, health checks, significance tests, CUPED and a ship decision, verified against simulation. | [Experiment Desk](https://ashokreddy010.github.io/ab-testing-toolkit/) | Python, SciPy, pandas, Pyodide |
| [Stock Market Analysis and Prediction](https://github.com/AshokReddy010/Stock-Market-Analysis-and-Prediction) | Full-stack app with 7-day forecasts backtested against a no-change baseline, news sentiment, JWT accounts; tested and packaged with Docker Compose. | Docker | Python, FastAPI, React, SQLite |

## What I work with

| Area | Tools |
|:--|:--|
| Analytics and BI | SQL, Python, Power BI, Tableau, Excel |
| Data modelling and quality | dbt, Snowflake, BigQuery, Redshift, DuckDB, reconciliation, automated tests |
| Modelling and AI | scikit-learn, forecasting, A/B test analysis, LLM evaluation, FastAPI |
| Ways of working | Git, GitHub Actions, CI/CD, Docker, Agile |
