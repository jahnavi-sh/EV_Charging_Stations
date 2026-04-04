## EV Charging Network Analysis

## Project Executive Summary
As the adoption of electric vehicles (EVs) accelerates, the limiting factor remains the availability and reliability of charging infrastructure. This project performs a comprehensive analysis of the EV charging network across the United States and Canada. By analyzing geographic density, operational status, and proximity to major transit corridors, this study identifies critical gaps in the current network and proposes a strategic roadmap for future station development to support long-distance travel and urban accessibility.

## Technical Workflow & Architecture

### 1. Data Acquisition & Structural Integrity
* **Multi-National Dataset**: Leveraged a large-scale public dataset from Kaggle containing detailed attributes for thousands of charging stations across North America.
* **Feature Set**: Processed 17+ attributes, including high-granularity location data (Latitude/Longitude), connector types (Level 1, Level 2, DC Fast Charging), and ownership status (Public vs. Private).
* **Data Cleansing**: Performed normalization on state and city identifiers to ensure accurate cross-border geospatial mapping between the US and Canada.

### 2. Geospatial & Quantitative Analysis
* **Density Mapping**: Developed an interactive map visualization to identify high-concentration hubs (Midwest, East Coast, and Western Canada) and under-served "charging deserts".
* **Urban-Rural Comparative Study**: Segmented the data to analyze the disparity in infrastructure, revealing a significant concentration in metropolitan areas and a strategic need for more rural Level 3 (DC Fast) stations to enable interstate travel.
* **Operational Analytics**: Evaluated annual usage rates and operational status to determine which station types and locations yield the highest efficiency.

### 3. Business Intelligence Dashboard
I designed an executive-level Power BI dashboard featuring a three-tier information architecture:
* **Level 1: Key Metrics (KPIs)**: High-level summaries of total stations, growth rates, and station-to-state ratios.
* **Level 2: Geographic Interface**: A middle-tier interactive map allowing users to filter by city, state, or fuel type.
* **Level 3: Strategic Insights**: Bottom-tier bar and trend charts visualizing capacity trends and regional comparisons.

## Key Technologies
* **Analysis Tool**: Microsoft Power BI
* **Data Manipulation**: Power Query (ETL)
* **Visualization Techniques**: Geospatial Mapping, Heatmaps, and Time-Series Trend Analysis
* **Domain Focus**: Infrastructure Planning, Sustainability, and Operational Strategy

## Recommendations
* **Infrastructure Optimization**: Identified that stations near highways see the highest usage, suggesting that future private and public investment should prioritize high-traffic corridors.
* **Market Expansion**: Provides a data-driven blueprint for energy companies to target "rural deserts," essential for reducing range anxiety and supporting long-distance EV adoption.
* **Policy Support**: Offers local governments a clear view of their regional standing, assisting in the allocation of subsidies for Level 2 and DC Fast Charging development.

---
**Prepared by:** [Jahnavi Sharma](https://www.linkedin.com/in/jahnavi-sh/)
