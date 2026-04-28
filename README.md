# Uber Trip Analytics Dashboard (Tableau)

<p align="left">
  <img src="https://img.shields.io/badge/Focus-Data%20Analytics-111111?style=for-the-badge" alt="Focus Data Analytics" />
  <img src="https://img.shields.io/badge/Domain-Uber%20Trips-276EF1?style=for-the-badge" alt="Domain Uber Trips" />
  <img src="https://img.shields.io/badge/Status-Portfolio%20Project-12B886?style=for-the-badge" alt="Status Portfolio Project" />
</p>

A data-driven dashboard exploration of Uber trip patterns designed to uncover **prime driving hours, preferred service categories, and high-earning location clusters**.

## Tech Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=python" alt="Python" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/Git-GitHub%20Workflow-181717?style=for-the-badge&logo=github&logoColor=white" alt="Git and GitHub" />
</p>

## What's included

- **Interactive Tableau dashboard** for exploring revenue trends, demand patterns, category breakdowns, and route performance
- **Static chart exports** (PNG) enabling repository review without Tableau access
- **Key metrics summary** with actionable insights for strategic decision-making

## Quick overview

<img width="1260" alt="Dashboard preview" src="./charts/Uber_Dashboard.png" />

## Data highlights

From the `REAL ROUTES` sheet in `UBER_RAW.xlsx` (721 analyzed trips after data cleaning):

- **Total revenue**: `R$11,535.34`
- **Average fare / trip**: `R$16.00`
- **Average distance**: `5.14 km`
- **Average duration**: `12.53 min`

## Core findings

- **Peak demand windows** occur during daytime and early evening, showing sustained high trip volumes.
- **`Comfort` category dominates** in both trip frequency and revenue contribution.
- **Revenue concentrates on repeat routes**, indicating strong neighborhood demand patterns.
- **Fast review**: chart exports enable complete repository assessment in under 2 minutes.

## Visual analytics

### 1) Hourly revenue vs. trip volume

<img width="1000" alt="Hourly revenue and trips" src="./charts/Uber_Dashboard2.png" />

### 2) Revenue by ride category

<img width="900" alt="Revenue by ride category" src="./charts/Distribution_By_Fareamount.png" />

### 3) Top routes by revenue

<img width="1000" alt="Top routes by revenue" src="./charts/CityMap.png" />

## Strategic questions addressed

- **Optimal timing**: which hours deliver the best revenue-to-trip ratio?
- **Service preferences**: which ride categories drive the highest earnings?
- **High-value routes**: which pickup → dropoff pairs generate maximum returns?
- **Pattern stability**: how consistent are trends across seasons and areas?
- **Operational efficiency**: where can time and distance be optimized while maintaining revenue?

## Approach

- **Currency normalization** from formatted strings (e.g., `R$47.81`)
- **Time and distance conversion** to numeric formats for aggregation
- **Location label standardization** for reliable route grouping
- **Data filtering** to remove duplicates and incomplete entries before analysis

## Technology stack

- **Tableau**: dashboard creation + interactive analysis (`Uber.twbx`)
- **CSV**: dataset containing trip data (`uber_trips_dataset_50k.csv`)
- **Python**: automated chart generation for static exports in `charts/`

## Project structure

- `README.md`: project documentation
- `Uber.twbx`: Tableau workbook with interactive dashboard
- `uber_trips_dataset_50k.csv`: dataset containing raw trip data
- `charts/`: dashboard screenshots and static chart exports

## Review guide

1. **Start here**: browse the dashboard preview and 3 key charts.
2. **Interactive exploration**: open `Uber.twbx` to use filters and drill-down features.
3. **Data validation**: examine `uber_trips_dataset_50k.csv` for data quality.

