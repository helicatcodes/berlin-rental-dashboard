# Berlin Rental Market Dashboard

An interactive dashboard analysing Berlin's rental market by district, price, and trend — my capstone for Le Wagon's Data Analytics bootcamp.

📊 [Explore the live dashboard](https://datastudio.google.com/reporting/a137163f-bea6-4481-99fc-dbc905532d92)

<a href="https://github.com/user-attachments/assets/45421da4-5ab6-4c7e-aa11-09d8e9f2dd72">
  <img src="https://github.com/user-attachments/assets/45421da4-5ab6-4c7e-aa11-09d8e9f2dd72" alt="Berlin Rental Market Analysis — overview: 12 districts, 82 neighborhoods, 30K listings" width="100%">
</a>

## Pipeline

1. **Extract** — real-world Berlin rental listing data loaded into BigQuery
2. **Transform** — cleaning and modelling with advanced SQL, organised into layered BigQuery datasets following the raw → intermediate → marts pattern, so each transformation step is isolated and reusable
3. **Visualise** — interactive exploration in Data Studio: filter by district, price band, and time period

## Tech stack

* **BigQuery** — data warehouse with layered datasets (raw / intermediate / marts)
* **SQL** — extraction, cleaning, aggregation
* **Data Studio (Looker Studio)** — interactive dashboard

## What the dashboard shows

<table>
  <tr>
    <td width="33%" valign="top">
      <a href="https://github.com/user-attachments/assets/9e2fa0bc-ac3f-435f-821a-7c93313914a0">
        <img src="https://github.com/user-attachments/assets/9e2fa0bc-ac3f-435f-821a-7c93313914a0" alt="Transit &amp; Centrality — rent distribution across Berlin" width="100%">
      </a>
      <br><sub><b>Transit &amp; Centrality</b><br>Centrality drives rent more than transit proximity.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/user-attachments/assets/fbf99570-ebc5-4e02-b9ed-be6770a854fe">
        <img src="https://github.com/user-attachments/assets/fbf99570-ebc5-4e02-b9ed-be6770a854fe" alt="Premium neighborhoods vs. rent — amenities and price gap over time" width="100%">
      </a>
      <br><sub><b>Premium Living</b><br>The high/low gap has grown 51% since 2020.</sub>
    </td>
    <td width="33%" valign="top">
      <a href="https://github.com/user-attachments/assets/e13ae683-11c8-4cfa-a5df-ff86d76d51ee">
        <img src="https://github.com/user-attachments/assets/e13ae683-11c8-4cfa-a5df-ff86d76d51ee" alt="Bigger Space for Better Value — apartment size vs. rent per m²" width="100%">
      </a>
      <br><sub><b>Best Value</b><br>Biesdorf, Hellersdorf and Marzahn lead on value score.</sub>
    </td>
  </tr>
</table>

## What I'd explore next

* Trend forecasting per district
* Joining in open data on transport access and amenities to explain price variation
