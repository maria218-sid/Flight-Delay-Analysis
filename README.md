#Flight Delay Analysis – Avoiding Flight Delays from NYC Airports
Project Overview

This project analyzes flight delay patterns across major New York City airports to identify strategies travelers can use to reduce the risk of delays. Using real flight data, the analysis explores how delays vary by airport and time of day.

#Project Objective

The goal of this project is to apply data analysis techniques to uncover trends in flight delays and provide actionable insights for selecting flights that are less likely to be delayed.

#Dataset
Source: nycflights13 R package - flights dataset
Contains data on all commercial flights departing in 2013 from:
JFK (John F. Kennedy International Airport)
LGA (LaGuardia Airport)
EWR (Newark Liberty International Airport)

#The dataset includes:

Departure times and delays
Airlines and destinations
Flight schedules and metadata

Tools & Technologies
R
tidyverse (data manipulation)
ggplot2 (data visualization)

#Analysis Process

1. Data Cleaning & Preparation
Removed missing values (e.g., NA delays)
Filtered and grouped data by airport and hour
Calculated average departure delays
2. Exploratory Data Analysis (EDA)
Analyzed how delays change throughout the day
Compared delay patterns across airports
Investigated trends using grouped summaries
3. Data Visualization
Created line plots showing delay trends by hour
Built comparisons across airports (JFK, LGA, EWR)
Used visualizations to highlight key patterns

#Key Insights

Delays increase throughout the day
Early-morning flights have the lowest delays, while evening flights are the most delayed.
Airport performance varies
LGA has the lowest average delays (most reliable)
EWR has the highest delays
JFK falls in between
Delay accumulation effect
Delays build up over the day as earlier flights run late, impacting later departures.

💡 Recommendations

Based on the analysis:

Choose early-morning flights to minimize delays
Prefer LaGuardia (LGA) when possible
Avoid late-day departures, especially from EWR
