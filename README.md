# Spatiotemporal Analytics of Air Pollution (PM2.5 & PM10) in Bogotá

An end-to-end data science portfolio dedicated to processing, visualizing, and modeling fine particulate matter ($PM_{2.5}$ and $PM_{10}$) dynamics across Bogotá's air quality monitoring network, leveraging official data from IDEAM and local environmental secretariats.

## Project Overview
Air pollution is a critical public health and environmental challenge in Bogotá. This repository unifies four interconnected analytical modules that span from historical evolutionary tracking to geospatial pattern detection and cross-pollutant correlations. It serves as a comprehensive toolset for understanding how particulate matter behaves across different urban sectors, industrial corridors, and temporal scales.

---

## Repository Structure & Modules

The project is consolidated into four specialized modules:

### 1. PM2.5 Evolution Tracking (Bogotá 2024)
* **Focus:** Analyzes the behavior, critical peaks, and seasonal trends of $PM_{2.5}$ concentration throughout the year 2024. 
* **Key Metrics:** Daily averages, exceedance days based on WHO guidelines, and temporal anomaly detection.

### 2. General PM2.5 Comprehensive Analysis
* **Focus:** Explores long-term historical records of $PM_{2.5}$ across the capital, building robust data pipelines for cleaning missing environmental telemetry data and computing descriptive macro-statistics.

### 3. IDEAM Monitoring Stations: Top & Bottom Performers
* **Focus:** Ranks and benchmarks IDEAM network stations based on pollution loads. Identifies the most critical hot spots (Top Polluted) vs. sectors with optimal air quality index baselines (Bottom Polluted) using advanced data aggregation.

### 4. Cross-Pollutant Dynamics: PM2.5 vs. PM10
* **Focus:** Statistical evaluation of the ratio and correlation between $PM_{2.5}$ (fine respiratory particles) and $PM_{10}$ (coarser particles). Includes statistical distribution fitting and scatter-profile modeling to understand common emission sources.

---

## Tech Stack & Tools
* **Language:** Python 3.x
* **Data Wrangling:** `pandas`, `numpy`
* **Exploratory Data Analysis & Visualization:** `seaborn`, `matplotlib`, `plotly`
* **Geospatial Reference (Extensions):** `geopandas` / `folium`

---

## Getting Started

### Prerequisites
Ensure you have Python installed along with the required libraries. You can install all dependencies at once:

```bash
pip install pandas numpy matplotlib seaborn plotly
