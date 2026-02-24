<h1 align="center">
Mobile Phones Sales Performance Dashboard</h1>

<!-- <h1 align="left">
Contents
## Project Overview
## Key Features
## Data Insight
## Technical Highlights
## Tools Used
## Visualisations
   -->
## Project Overview
This Power BI dashboard provides a compehensive analysis of global mobile phone sales data from 2018 to 2021. It is designed to track sales performance, monitor market trends across different brands and evaluate distributor efficiency across multiple international territories. 

[File Link](https://github.com/mustafafakhar/Mobile-Phone-Data/edit/main/ReadMe.txt#:~:text=IMG-,Mobile,-Phone%20Data%20Dashboard)
## Key Features
Following are some key features this dashboard entails:
**Dynamic Sales Tracking:** Visualizes total sales volume and revenue trends over a four-year period.

**Brand and Regional Analysis:** Interactive slicing by Brand (Apple, Samsung etc.) and Country to drill down into specific market performance. 

**Time-Intelligence Metrics:** Includes Year-Over-Year (YoY) Growth calculations and monthly seasonality trends.

**Distributor Insights:** Identifies top-performing retail partners and distributors (e.g. Tottus, Oeschle)

## Data Insight
**Peak Performance:** The year 2021 saw significant surge in sales volume, nearly doubling the performance of previous years. 

**Seasonality:** Sales data shws high volatility throughout the year, with consistent peaks in Februrary and September. The September surge could be due to the release of the new Apple devices. 

## Technical Highlights
To ensure a professional user interface, I implemented a custom DAX measure to handle data gaps. For example, YOY Sales % measure was optimized to return "Select a Year" value instead of a -100% when no prior year data is available (e.g. for the start year of 2018)

**Measure Example:**
![Alt text](IMG/YOY % Measure.png)
*Note: The DIVIDE function is used here to handle null denominators, resulting in a cleaner visualisation*

## Tools Used ##
The following tools have been used for this dashboard:

**1- _Power BI_**

**2- _Excel_**

**3- _DAX(Data Analysis Expressions)_**

**4- _Power Query(M)_: Data Cleaning and Transformation**


## Visualizations
![Alt text](IMG/Overview) 

<img src ="IMG/Region Wise Distribution">




