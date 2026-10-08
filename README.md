# E-commerce Cohort & 7-Day Retention Analysis

## Project Overview

This project analyzes customer retention using real e-commerce event data from a cosmetics shop.

The goal is to perform cohort analysis and measure how many users return after their first visit, with a focus on 7-day retention.

## Dataset

The dataset contains e-commerce events from October 2019 to February 2020.

For this analysis, we used:

- `event_time`
- `user_id`

## Methodology

1. Load the e-commerce event data.
2. Convert event timestamps to dates.
3. Create unique user-day records.
4. Identify each user's first visit as their cohort date.
5. Calculate days since the first visit.
6. Count unique users by cohort and day.
7. Create the cohort retention matrix.
8. Calculate retention percentages.
9. Analyze 7-day retention.
10. Visualize the results.

## Key Results

- Average 7-Day Retention: **1.65%**
- Best 7-Day Retention: **5.12%**
- Worst 7-Day Retention: **0.65%**

## Business Insight

On average, **1.65% of users returned exactly 7 days after their first visit**.

This indicates relatively low short-term customer retention and highlights an opportunity to improve customer engagement and repeat visits.

## Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- KaggleHub

## Skills Demonstrated

- Data Cleaning
- Cohort Analysis
- Customer Retention Analysis
- Data Transformation
- Data Visualization
- Pandas GroupBy
- Pivot Tables
- Business Analytics
