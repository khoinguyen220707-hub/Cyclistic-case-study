# Cyclistic-case-study
### Google Data Analytics Capstone Project
## Project Overview
As a Junior Data Analyst at **Cyclistic**, a bike-share company in Chicago, I am tasked with analyzing historical trip data in 2025 to understand the different usage patterns between 2 types of customers: **Casual riders** and **Annual members**

The goal of this analysis is to provide data-driven insights to take advantage of the digital media and develop marketing strategies to convert casual riders into annual members for Cyclistic's future growth

## Tech Stack & Tools:
* **Data Processing:** SQL (Google BigQuery)
* **Visualization:** Tableau and Microsoft Excel
* **Documentation:** Google Docs and Github
* **Spreadsheets:** Microsoft Excel (Initial data exploration)
* **Presentation:** Microsoft PowerPoint

## Project structure:
├── SQL/
│   ├── 01
│   ├──
│    ├──
│    ├──
│    ├──
│    ├──
│    ├──
│    └──
├── Slides/
    └──
├── Docs/
    ├──
    ├──
    ├──
    └──
├── Data/
    ├──
    └── Raw
        ├──
        └──
└──
        
## Data Source:
The data set consists of historical trip data from Cyclistic, made by Motivate International Inc.
* **Data Integrity:** The data is public and authorized, ensuring no personally identifiable information (PII) is included
* **Scope:** 12 months of ride data in Year 2025

## The 6-Step Data Analysis Process

### 1. Ask
* **Business Question:**
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?
* **Objective:** Identify trends and patterns to convert casual riders into annual members
### 2.Prepare:
* Imported 12 months of CSV files into BigQuery
* Merged datasets into a single table ('trips_2025_uncleaned') consisting of over **5.5 million** rows
* Verified schema cosistency across all files
### 3.Process:
* **Cleaning:** Removed duplicates, null values, and test station entries.
* **Calculation:**
  * Extracted 'day_of_week"
  * Estimate the total rides
  * Group hours into 3 main categories
  * **Filtering:** Excluded trips shorter thatn 1 minute or longer than 24 hours to elminate outliers.
### 4. Analyze:
* **Data Aggregation:** Perform calculations for the duration intensity
* **Pivot Analysis:** Using pivot tables to search for overall insights through stastical numbers
* **Key Findings:**
  * **Annual members** are the majority in the distribution
  * **Members** shows a consistent pattern during weekdays, while **Casuals** show a peaking on weekends afternoons.
  * Both **casual riders** and **annual members** show a preference for electric bikes
  * **Casual riders** travel **2x longer** on average compared to members, but the frequency is lower
  * Top 3 stations for **casual riders** are all near **recreational areas**
### 5. Share
* **Visualization tool:** Developed simple and accesible charts through **Excel** and interactive dashboard using **Tableau**
* **Design Philosophy:** Applied "Data-to-Ink Ratio" principles to ensure clairty and focus on key trends
* **Visual storytelling:** Displayed all the findings and insights in a structural and logical way through **Microsoft PowerPoint**
* **Dashboard Link:**
### 6. Act
1. **Weekend Membership Plan:** Launch a "Weekend-Only" membership tier or a "Summer Pass" specifically targeting at casual riders who follow these patterns
2. **Strategic Trial Campaign:** Focus and promote digital marketing of  efforts especially near recreartional areas and tourist attraction most frequented by casual riders
3. **Gamification & Reward System:** Offer captivating and impressive rewards or discounts to casual riders who bike frequently
