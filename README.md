**Project Title :** Uber Trip Analysis - Dashboard

Dashboard Link : https://app.powerbi.com/links/DyqeDOg1o_?ctid=4e736b85-ff12-4b02-81e6-1c7428d14652&pbi_source=linkShare


**Problem Statement: Uber Trip Analysis**

**Uber needs to understand its trip patterns, revenue, and operational efficiency to make data-driven decisions. Challenges include identifying peak hours, high-demand locations, vehicle utilization, and revenue trends while handling large volumes of trip data. The goal of this project is to build interactive dashboards that provide insights into bookings, trip distances, durations, and payment types, enabling stakeholders to optimize driver allocation, pricing, and overall service quality.**

**Steps followed**
This project demonstrates an end-to-end data analytics workflow for Uber trip data:

***1. Prerequisites & Setup :** Configured AWS S3 for raw data storage, integrated Snowflake as a scalable data warehouse, and established Power BI–Snowflake connection via Power BI Service for seamless reporting.

**2. Data Cleaning & Preparation:** Performed data cleaning (handling missing values, standardizing formats, removing duplicates) to ensure dataset accuracy and consistency.

**3. Data Modeling:** Built a robust data model with relationships, calendar tables, and measure tables for accurate time intelligence and KPI tracking.

**4. Reporting & Dashboards:** Designed 3 interactive dashboards (Overview, Time Analysis, and Details) with KPIs including total trips, revenue, customer insights, and regional trends.

**5. Advanced Interactivity:** Implemented drill-through, bookmarks, and toggle features for enhanced user exploration and self-service analytics.

**6. Deployment & Automation:** Published the report to Power BI Service and scheduled data refreshes to keep dashboards updated with the latest data.

**7. Documentation & Collaboration:** Published full project documentation and reports on GitHub, including datasets, DAX measures, and development process for reproducibility.



Overall Insights: Uber Trip Analysis

**Total Activity:**  Uber completed 103.7K bookings, generating $1.6M in revenue, covering 349K miles, with an average trip of 3 miles and 16 minutes.

**Vehicle Trends:** UberX had the most bookings (38K), and brought in the highest revenue (~$5.8M) and covered the longest distance (131K miles). Average fare across all types is around $15.

**Payments & Trip Type:** Most trips were paid via Uber Pay, with bookings almost evenly split between day and night trips.

**Peak Time & Day:** Most trips occur in the late afternoon/early evening (3–6 PM). Weekends see the highest bookings, with Fridays being the lowest.

**Location Hotspots:** Penn Station/Madison Square West is the most common pickup point, and Upper East Side North is the most frequent drop-off, highlighting busy commuter and residential areas.
