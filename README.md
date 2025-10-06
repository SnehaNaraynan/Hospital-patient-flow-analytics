# Hospital Patient Flow Analytics

## Business Objectives

- Monitoring patient admissions to minimize waiting times.
- Identify department-level bottlenecks (e.g., Emergency, Surgery,
ICU).
- Enable gender-based and age-based KPIs for demographic
insights.
- Automate Alerts in case of failures.

## Data Sources

- Real-time patient admission/discharge data from hospital registration systems.
- Daily batch extracts from Electronic Health Records (EHR) systems.
- Department metadata (capacity, staff numbers).

## Data Processing & Storage
- Store data in a Medallion architecture (Bronze → Silver → Gold)

## Data Quality
- Simulate realistic dirty data issues (e.g., missing admission times, duplicate patient IDs, wrong timestamps) and handle them in Silver layer processing
