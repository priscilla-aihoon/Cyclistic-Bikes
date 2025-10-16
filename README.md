# Cyclistic Bike-Share Dashboard Analysis

This repository presents a data analysis and dashboard project for Cyclistic, a Chicago-based bike-share company. The goal of this project is to analyze user behaviors and support Cyclistic’s business objective of increasing annual memberships by understanding how casual riders and members use the service differently.

## Business Objective

Cyclistic’s marketing team seeks to convert more casual riders into annual members. The dashboard and analysis identify usage patterns, visualize key metrics, and inform data-driven marketing recommendations.

## Data Sources

- Official public trip data for 12 consecutive months, provided by Motivate International Inc. and adapted for Cyclistic.
- Features: ride ID, start/end station, start/end time, user type (member/casual), and bike type.
- All personal user information has been removed to protect privacy.

## Data Cleaning and Preparation

- Merged monthly trip data into a single dataset.
- Calculated ride length and extracted additional fields (e.g., day of week, month).
- Cleaned data by removing errors, handling missing fields, and filtering outliers.
- Standardized station names and types for aggregation and visualization.

## Analysis and Visualizations

The analysis focused on:
- Comparing ride frequency and duration by user type.
- Identifying weekly and seasonal trends in usage.
- Mapping starting/ending station popularity.
- Visualizing member vs. casual ratios and ride patterns.

Visualizations were created in Power BI (or indicate your tool), including:
- Bar charts for user type distribution and ride duration.
- Line charts for monthly and week-by-day trends.
- Pie charts for proportion visuals.
- Station activity maps.

## Key Findings

- Members made up approximately 64% of all rides; casuals 36%.
- Casual riders favor weekends and take longer trips, while members ride more consistently during weekdays.
- Seasonality drives increased busy periods in summer.
- Popular stations are clustered in central and high-traffic locations.

## Recommendations

1. Launch targeted marketing campaigns to attract casual riders during peak seasons.
2. Offer membership incentives and bundles based on observed usage trends.
3. Enhance member-exclusive features to drive conversions from casual riders.

## Getting Started

Clone the repository and open the Power BI dashboard file (`Cyclistic-Bikes-Dashboard.pbix`) to interact with the visuals.

## License

This repository is for educational and portfolio purposes. Data is provided under applicable terms from Motivate International Inc.
