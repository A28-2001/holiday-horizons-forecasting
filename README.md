Holiday Horizons: Travel & Air Quality Forecasting
Tools: Python · SQL · Power BI
Context: Northeastern University | Data Analytics Engineering
Portfolio: mehtaakash.com

Project Summary
Analyzed the impact of U.S. public holidays on four key domains: domestic airfare, hotel bookings, public transit ridership, and air quality (PM2.5 particulate matter). Built Power BI forecasting dashboards to visualize trends and surface actionable insights across holiday windows.
Key findings:

Identified a 370% spike in PM2.5 levels on Independence Day and New Year's Day driven by fireworks emissions
Domestic airfare surged before Memorial Day 2019, with average fares at $355, then dropped post-holiday
Hotel prices spiked on Christmas Day despite a drop in same-day bookings, reflecting demand-driven premium pricing
Public transit ridership consistently dropped on weekends and holidays due to reduced commuter volume and modified agency schedules
Improved travel demand forecast accuracy by 40% by tuning Power BI predictive models against historical travel datasets


Datasets Used
DatasetSourceDescriptionDomestic AirfareBureau of Transportation Statistics (BTS)Average U.S. domestic ticket prices by airline and dateHotel BookingsPublic datasetBooking volume and nightly rates around holiday windowsPublic Transit RidershipPublic transit agenciesDaily ridership counts across U.S. metro systemsAir Quality (PM2.5)South Coast AQMD / EPAParticulate matter measurements around U.S. holidays

Methodology

Data ingestion — Ingested pollution and airfare datasets via SQL queries
ETL pipeline — Cleaned and integrated multi-source datasets using Python (Pandas)
EDA — Explored before/on/after holiday dynamics across all four factors
Forecasting — Built Power BI predictive models tuned against historical travel data
Visualization — Developed interactive Power BI dashboards for trend analysis and forecasting


Key Insights
Flights
Domestic airfare rises sharply before and during holidays due to peak demand. Post-holiday fares drop significantly, with airlines like American Airlines showing some of the lowest average prices after Memorial Day.
Hotels
Same-day bookings drop on Christmas Day as travelers secure accommodation in advance. Despite lower booking volume, nightly rates spike due to seasonal demand and limited availability, remaining elevated through the post-Christmas festive week.
Public Transit
Ridership drops consistently on public holidays. Contributing factors include reduced commuter volume, modified transit schedules, and maintenance windows scheduled during low-demand periods.
Air Quality (PM2.5)
Fireworks on Independence Day and New Year's Day cause sharp PM2.5 spikes, with levels rising as much as 370% above baseline. High PM2.5 exposure is linked to cardiovascular and respiratory health effects including asthma aggravation and decreased lung function.

Skills Demonstrated

SQL data extraction and transformation
Python (Pandas) for ETL and data cleaning
Power BI forecasting and dashboard development
Exploratory data analysis (EDA)
Data storytelling for technical and non-technical audiences
Cross-domain data integration (travel + environmental datasets)


Team
Built as part of a group project at Northeastern University.
Aakash J. Mehta · Nirmit Sachde · Ashmita Pal
