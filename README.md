# Victoria Road Crash Dashboard

An interactive data dashboard built on Databricks analysing road crash 
data across Victoria, Australia from 2012 to 2025.

---

## Dashboard Overview

![Dashboard Overview](dashboard_overview.png)

Key metrics visualised:
- 194.44K total accidents from 2012–2025
- Average 2 people involved per accident
- Serious injuries broken down by suburb
- Top 10 accident LGAs (35% of all crashes)
- Crash frequency by day of week and hour
- Fatality rate by regional location

---

## Data Source

- Source: [DataVic – Victorian Government Data](https://discover.data.vic.gov.au/dataset/victoria-road-crash-data)
- Period: 2012 – 2025
- Processing: Raw dataset was cleaned using SQL irrelevant columns were 
  dropped and only crash severity, location, time, and person count fields 
  were retained.



---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Databricks (Free Edition) | Compute & dashboard hosting |
| Databricks SQL | Querying & aggregating crash data |
| PySpark / Python | Data preprocessing in notebooks |
| Mapbox | Geospatial crash map visualisation |
| DataVic Open Data | Source dataset |

---

## SQL Scripts

Each SQL file corresponds to a specific dashboard widget:

| File | Description |
|------|-------------|
| `01_victoria_map.sql` | Victoria Map |
| `02_serious_injury_by_suburb.sql` | Serious Injury by Suburb |
| `03_accidents_by_week.sql` | Accident by Week |
| `04_top10_accident_zones.sql` | Top 10 LGA's |
| `05_accidents_by_hour.sql` | Crash Peak Time |
| `06_total_accidents_by_year.sql` | Total number of accidents from 2012 - 2025 |
| `07_top10_local_areas_by_fatality_rate` | Fatality Rate by Location |
---

##  Key Insights

- Friday 3–5 PM is the highest crash risk window
- Melbourne, Yarra, and Geelong lead in serious injuries
- Buloke and Corangamite have the highest fatality rates despite fewer 
  total crashes — a rural road safety concern
- Accident volume has remained relatively stable year-on-year since 2012

---


## Author

**Abhishek Koppal**  
[LinkedIn](https://www.linkedin.com/in/abhishek-koppal/) | [GitHub](https://github.com/Abhishek-koppal)