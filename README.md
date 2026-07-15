# Berlin Rental Market Dashboard

An interactive dashboard analysing Berlin's rental market by district, price, and trend — my capstone for Le Wagon's Data Analytics bootcamp.

📊 [Explore the live dashboard](https://datastudio.google.com/reporting/a137163f-bea6-4481-99fc-dbc905532d92)

Screenshot: dashboard overview -->
Screenshot: district-level drill-down -->

## Pipeline

1. **Extract** — real-world Berlin rental listing data loaded into BigQuery
2. **Transform** — cleaning and modelling with advanced SQL, organised into layered BigQuery datasets following the raw → intermediate → marts pattern, so each transformation step is isolated and reusable
3. **Visualise** — interactive exploration in Data Studio: filter by district, price band, and time period

## Tech stack

- **BigQuery** — data warehouse with layered datasets (raw / intermediate / marts)
- **SQL** — extraction, cleaning, aggregation
- **Data Studio (Looker Studio)** — interactive dashboard

## Repo contents

- `sql/` — key transformation queries per layer

## What I'd explore next

- Trend forecasting per district
- Joining in open data on transport access and amenities to explain price variation
