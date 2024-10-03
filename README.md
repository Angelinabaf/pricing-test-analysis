# **Pricing Test Analysis**

## Project Overview
This project involves a comprehensive analysis of a pricing test conducted by Company XYZ, where the price of software was tested at two different points: $39 and $59. The primary goal was to determine which price maximizes revenue without significantly impacting conversion rates.

## Objective
The analysis aims to:

- Assess the revenue impact and conversion rates at different price points.
- Identify user behavior patterns across various segments such as device type, operating systems, and marketing channels.
- Evaluate the test duration to ensure statistical significance and stability of the results.

## Key Findings
***Higher Revenue at $59:*** Despite a reduction in conversion rates, increasing the price to $59 results in higher average revenue per user.

***Segment Sensitivity:*** Different user segments exhibited varying sensitivity to the price increase, with particularly adverse effects noted among Linux users.

***Optimal Test Duration:*** Statistical tests suggest that a minimum duration of two weeks is recommended to account for weekly variations and ensure robust findings.

## Recommendations
***Implement the $59 Price Point:*** Based on the increased revenue observed, it is recommended to adopt the $59 price point.

***Segmented Pricing Strategies:*** Consider maintaining the $39 price or providing targeted discounts for segments showing high price sensitivity.

***Further Analysis and Monitoring:*** Continuous monitoring and further segmented tests are suggested to optimize pricing strategies.

## Data
The analysis utilizes two main datasets:

- test_results.csv:* Contains user test results including user ID, source, device, operating system, pricing group, and conversion status.
- user_table.csv:* Includes user demographic information such as city, country, latitude, and longitude.

## Tools Used
***Python:*** For data manipulation and analysis.

***Pandas & NumPy:*** For handling dataframes and numerical calculations.

***Matplotlib & Seaborn:*** For visualizing data insights.

***SciPy & StatsModels:*** For conducting statistical tests.

## How to Run the Project
- Clone this repository.
- Ensure Python 3 and all dependencies (listed in requirements.txt) are installed.
- Run the Jupyter Notebook AB_testing_practice.ipynb to view the analysis.

### Conclusions
This analysis confirms the potential for a higher price point to enhance revenue, guided by data-driven insights into user preferences and behaviors. The findings support strategic decisions in pricing that could lead to significant gains in profitability for Company XYZ.


