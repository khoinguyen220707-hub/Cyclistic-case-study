# SQL files for data cleaning and analysis
This folder contains an uncleand file with 5.5 million rows and a cleaned file with 5.3 million rows of data, which are divided into different files for in-depth analysis.

## Execution Order:
1. **'01_trips_2025_uncleaned':** Combines 12 monthly tables (CSV imports) into a single unit table.
2. **'02_trips_2025_cleaned':** Removes duplicates and filters out trips shorter than 1 minute and longer than 24 hours.
3. **'03_trips_2025_Time_Period':** Aggregates ride volume by month to find usage patterns
4. **'04_trips_2025_Weekly_Rhythm':** Aggregates ride volume by day of the week to determine usage patterns
5. **'05_trips_2025_Hourly_Peaks':** Aggregates ride volume by hour of a day to reveal usage patterns
6. **'06_trips_2025_User_frequency':** Calculates mean, max, min, and sum of ride lengths to understand the usage intensity
7. **'07_trips_2025_Types_of_bikes':** Determine which one between **classic bikes** and **electric bikes** is the preference for both customers
8. **'02_trips_2025_Geographic_distribution':** Identifies top 10 stations with the highest distribution
## Environment Setup:
* **Platform:** Google BigQuery
* **Language:** SQL
