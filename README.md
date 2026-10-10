# Divvy Bike-Share Case Study — Casual vs Member Analysis

Google Data Analytics capstone: how do annual members and casual riders use Divvy bikes differently?

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Pdrsmth/divvy-bike-share-capstone/blob/main/divvy_bike_share_analysis.ipynb)

## Dataset
13 months of Divvy trip data (Sep 2024 – Sep 2025) — 6,360,797 trips raw, **6,354,438** after cleaning.

## Cleaning
- Removed 43 impossible trips (ride_length ≤ 0)
- Removed 6,316 trips longer than 24 hours (system errors)
- Station nulls kept (valid dockless e-bike trips)

## Key Findings
- ⏱️ **Casual riders** ride longer: **19.3 min** avg vs **11.8 min** for members
- 🔢 **Members** take 2x more trips: **4.0M** vs 2.3M casual
- 📅 **Casual** peaks on **weekends** (leisure); **members** peak on **weekdays** (commuting)

## Recommendation
Convert weekend casual riders with targeted membership promos (e.g. discounted annual plans marketed at high-traffic weekend stations).

## Tech
Python, pandas, matplotlib — analysis in Google Colab.
