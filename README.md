# Financial-Data-Analysis
This repository contains code and resources for conducting analysis on top 500 companies of India. The purpose of this project is to explore, analyse, and derive insights from companies financial data. The analysis encompasses various aspects &amp; factors influencing various orders.

## Project Overview

**I completed this analysis as part of my 1 month internship at Unified Mentor. I was tasked to analyse the competition for the management to provide better results.**

###  Data Sources

Companies Financial Data: The primary dataset used for this analysis is in "dataset-financial-analytics.csv" file, containing detailed information about market cap & quarterly sales.

  - This spreadsheet contains 4 columns:
    - S.No
    - Name of company
    - Market Capitalization
    - Quarterly Sales

### Tools

- Power pi: Data Processing, Data Cleaning, Data Analysis
- Microsoft Excel: Data Cleaning, Data Analysis
- Power bi: Data Visualization

## Approach for Data Analysis
1. **Ask**: ask questions & define problem
2. **Prepare**: prepare data by collecting & storing information
3. **Process**: process data by cleaning & checking information
4. **Analyse**: analyse data to find patterns & trends
5. **Share**: share data with audience
6. **Act**: act on data & use analysis results

### ASK
- Largest & smallest 10 companies by market cap?
- Largest & smallest 10 companies by quaterly sales?
- Sales Efficiency Ratio?
- Top 10 companies with highest sales efficiency ratio?
- Top 10 companies with smallest sales efficiency ratio?

### PREPARE
- We received our dataset from unified mentor management team

### PROCESS
- Renamed the columns
- Checked for null values from all the columns of the dataset
- After cleaning the dataset, updated missing market cap & quarterly sales records according to mean of the columns

### ANALYSE
- Sorted & filtered data
- Created histogram charts for better frequency overview of companies accross market cap & quarterly sales distribution
- Added Sales Efficiency Ratio column for understanding relationship between market cap & quarterly sales of the company
- Visualized largest & smallest companies according to market cap & quarterly sales using matplotlib & tableau

### SHARE
1. Reliance Industries (5,83,436 Cr) has the biggest market cap share
2. Natl. Fertilizers (3,017 Cr) has the smallest market share
5. IOCL (1,10,666 Cr) has most quaterly sales
6. Ujjivan Financial Services  (0 Cr) has least quaterly sales
7. SPARC (553.82) has the highest Sales Efficiency Ratio
8. Ujjivan Financial Services (0.0) has the lowest Sales Efficiency Ratio
9. Most of the companies market cap lies between between 0 - 1,50,000 Cr
10. Most of the companies quaterly sales lies between 0 - 27,500 Cr

### ACT
- Reliance Industries stands out with the largest market capitalization, while Ujjivan Financial Services appears to be struggling with both low quarterly sales and low sales efficiency
- The majority of companies fall within certain ranges of market capitalization and quarterly sales, indicating the typical distribution in the market
- Overall, these insights provide a snapshot of the market dynamics and the performance of different companies within it.
