# MOBILITY MODELLING PROJECT

# Comparative Bike-Share Analysis: NYC vs. Helsinki

A data-driven exploration of bike-share usage patterns in New York City (Citi Bike) and Helsinki (City Bike), including trip characteristics, temporal trends, spatial distributions, and environmental drivers. We also build an interactive map to visualize station demand against urban POIs.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Data](#data)  
3. [Environment & Installation](#environment--installation)  
4. [Workflow & Notebooks](#workflow--notebooks)  
5. [Key Analyses & Findings](#key-analyses--findings)  
6. [Interactive Map](#interactive-map)  
7. [Future Work](#future-work)  
8. [License](#license)  

---

## Project Overview

Bike-sharing programs play a vital role in urban mobility. This study compares two mature systems—Citi Bike in NYC and City Bike in Helsinki—to uncover:

- **Trip characteristics**: Distances & speeds  
- **Temporal patterns**: Hourly & weekday usage  
- **Spatial patterns**: Top stations & proximity to parks, residential areas, transit  
- **Environmental factors**: How daily temperature drives daily demand  
- **Interactive exploration**: Folium map of station usage overlaid on street network and POIs  

---

## Data

- **Citi Bike (NYC)**  
  - containing:  
    `ride_id, rideable_type, started_at, ended_at, start_station_id, start_station_name, start_lat, start_lng, end_station_id, end_station_name, end_lat, end_lng, member_casual, duration_s, distance_km, speed_kmh, hour, weekday`

- **City Bike (Helsinki)**  
  - containing:  
    `departure, return, departure_id, departure_name, return_id, return_name, distance (m), duration (sec.), avg_speed (km/h), departure_latitude, departure_longitude, Air temperature (degC), speed_kmh, hour, weekday`

- **Open-Meteo**  
  - Daily mean temperature fetched via API for correlation analysis.

---
