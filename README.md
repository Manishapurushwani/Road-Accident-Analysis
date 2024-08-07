# ROAD ACCIDENT DASHBOARD DATA ANALYSIS REPORT

## Table of Contents

##### [Project Title](#1-project-title)

##### [Introduction](#2-introduction)

##### [Data Collection](#3-data-collection)

##### [Client Requirement](#4-client-requirement)

##### [Data Preparation](#5-data-preparation)

##### [Data Analysis](#6-data-analysis)

##### [Findings](#7-findings)

##### [Conclusion](#8-conclusion)

##### [Appendices](#9-appendices)

##### [References](#10-references)

## Project Overview

## 1. Project Title

-   **Title:** Road Accident Dashboard Analysis for 2021 and 2022
-   **Date:** June 22, 2024
-   **Author:** Manisha Purushwani

## 2. Introduction

-   **Objective:** To analyze and visualize road accident data for the years 2021 and 2022 to provide insights into various aspects of road accidents.
-   **Background:** This project aims to help clients understand the trends and key performance indicators (KPIs) related to road accidents, such as the total number of casualties, types of casualties, and the impact of different factors like vehicle type, road type, and light conditions.
-   **Scope:** The analysis covers road accident data from January 2021 to December 2022, focusing on total casualties, accident severity, vehicle types, and other relevant factors.

## 3. Data Collection

-   **Data Sources:** The data is sourced from Reported Road Casualties Great Britain (RRCGB), which is the official statistical publication of the UK Department for Transport (DfT) on traffic casualties, fatalities and related road safety data. You can [**download the data in excel format here**](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbExkWEVwQlFSTnNhZXpWMVVMcWhxMVM1VHhyZ3xBQ3Jtc0ttT3NFQWFnbElLZWtVOG9iY0c1NmowalM4ZE1hQXNMWDZZOWd2a0J2TEh2MHFYdXNfUFNLUU5DYUtaTTdoMlRWd1E1bWgwanYtU2o5RTBvSURpRmUwSmQ2ZDM0MUx3SVBCQTRja3FIc2VtZmx4eXZEYw&q=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1R_uaoZL18nRbqC_MULVne90h3SdRbAyn%2Fedit%3Fusp%3Dsharing%26ouid%3D116890999875311477003%26rtpof%3Dtrue%26sd%3Dtrue&v=XeWfLNe3moM)
-   **Data Description:**
    -   Number of rows: 307,974
    -   Number of Columns: 23, which includes Accident_Index, Date, Accident Severity, Number of Casualties, Road types etc.
      

## 4. Client Requirement

![Client Requirement](https://github.com/profJays/road-accident-project/assets/30321855/1be5de67-18f9-4ad8-9790-635ebb8c158d)


## 5. Data Preparation

-   **Cleaning Process:**
    -   Ensured completeness of records for the two years.
    -   Standardized data formats for dates and categorical variables.
    -   Replaced some wrong entries (Eg. “Fetal” instead of “Fatal”).
-   **Data Formatting:** Converted data into Excel tables for ease of analysis and applied consistent naming conventions for columns.

## 6. Data Analysis

-   **Methodology:**
    -   Used pivot tables to summarize casualties by year, month, and other dimensions.
    -   Created line charts to visualize monthly trends.
    -   Used pie and bar charts for distribution analysis.
    -   Applied conditional formatting to highlight key metrics.


![Screenshot (219)](https://github.com/Manishapurushwani/Road-Accident-Analysis/assets/124506860/41d07d9d-95d2-4036-8dc4-d55df1c1c9e2)



-   **Tools Used:**
    -   Pivot Tables
    -   Charts (line, bar, pie)
    -   Conditional Formatting
    -   Filters for interactive analysis
    -   Slicers

## 7. Findings

-   **Summary of Results:** The total number of casualties over the two years is 2,22,146. A significant proportion of these casualties were related to cars.
-   **Detailed Analysis:**
    -   **Casualties by Severity:**
        -   Fatal: 7135(1.7%)
        -   Serious: 59,312 (14.2%)
        -   Slight: 3,51,436 (84.1%)
    -   **Casualties by Vehicle Type:**
        -   Cars: 3,33,485 (79.8%)
        -   Bus: 12,798
        -   Bike: 33,672
        -   Vans: 33,472
        -   Tractors: 1,032
        -   Others: 3424
    -   **Monthly Trend:**
        -   The monthly trend shows a relatively stable number of casualties with slight peaks and troughs, and a noticeable decline in December 2022.
    -   **Casualties by Road Type:**
        -   Single carriageway: 309.7K
        -   Dual carriageway: 67.4K
        -   Roundabout: 26.8K
        -   One-way street: 7.4K
        -   Slip road: 4.7K
    -   **Casualties by Road Surface:**
        -   Wet: 1,15,261
        -   Snow/Ice: 22,781
        -   Dry: 2,79,445
    -   **Casualties by Location/Area:**
        -   Rural: 162.0K
        -   Urban: 255.9K
    -   **Casualties by Light Condition:**
        -   Daylight: 305.0K
        -   Dark: 112.9K
       
![Screenshot (218)](https://github.com/Manishapurushwani/Road-Accident-Analysis/assets/124506860/c53a8c98-1514-46c0-8eeb-27551ae06451)

## 8. Conclusion

-   **Summary:** The analysis provides a comprehensive view of road accidents, highlighting the predominance of car-related casualties, significant seasonal variations, and the impact of road and surface types on accident severity.
-   **Implications:** These insights can guide targeted interventions, such as improving road safety measures in high-risk areas and during high-risk conditions.
-   **Recommendations:**
    -   Implement safety campaigns focusing on car drivers.
    -   Enhance road maintenance to mitigate the impact of adverse surface conditions.
    -   Improve lighting and signage in rural and high-risk areas.
-   **Limitations:** The analysis is limited to the provided data for 2021 and 2022. Additional data and longer time periods could provide more robust trends and insights.
