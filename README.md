# Power BI Demographic Analysis — Poland vs Europe vs World

Interactive Power BI report analyzing demographic trends in Poland compared to Europe and the World, covering the years 2020–2024.

## Tools & Technologies
- Power BI Desktop
- Power Query (data transformation)
- DAX (measures and calculations)
- Data source: [OECD Data Explorer](https://data-explorer.oecd.org) — downloaded as xlsx files and embedded directly in the .pbix file

## Report Structure
**Note:** All dashboards are in Polish. English version may be added in the future.

### Dashboard 1 — Ageing Society
Analyzes the share of people aged 65+ across Poland, Europe and the World over time.

![Dashboard 1](images/dashboard_1.png)

### Dashboard 2 — Age Structure: Poland vs Europe vs World
Compares the percentage share of 18 age groups across all three regions, highlighting key structural differences.

![Dashboard 2](images/dashboard_2.png)

### Dashboard 3 — Year-over-Year Population Dynamics
Shows which age groups are growing and which are shrinking, with YoY change metrics for each region.

![Dashboard 3](images/dashboard_3.png)

## Key Findings

**Poland is ageing faster than the world average**
The share of people aged 65+ in Poland grew from ~18% in 2020 to nearly 20% in 2024 — a pace significantly higher than the global average of ~10% and comparable to the fastest-ageing European societies.

**Structural differences between regions are striking**
The World has 25% of its population under 14 years old and only ~10% aged 65+, while Poland and Europe show the opposite pattern — ~15% children and over 19–21% seniors. A classic contrast between a young and an ageing society.

**Poland's total population is declining — but unevenly**
Year-over-year data shows that while Poland's overall population is shrinking, the 65+ group is consistently growing. The youngest age groups are contracting, which signals long-term pressure on the labour market and pension system.

## DAX Measures
- `Total People` — base population aggregation
- `Total People PY` — previous year comparison using `SAMEPERIODLASTYEAR`
- `YoY Change` and `YoY Change %` — year-over-year dynamics
- `Age Group Share %` — percentage share of each age group
- `Share 65+%` — senior population KPI

## Files
- `demographic-analysis-poland-europe-world.pbix` — Power BI report file (data included)
