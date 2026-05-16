# Statcast Pitch Performance Analysis

## Overview
This project analyzes Clayton Kershaw’s pitch-level Statcast data from 2015 to 2019 to evaluate how his pitching profile changed over time. The analysis focuses on velocity, pitch movement, release position, contact quality, and batter outcomes.

## Business / Analytical Question
How did Clayton Kershaw’s pitching profile evolve from 2015 to 2019, and which changes were associated with shifts in opponent contact quality and performance outcomes?

## Key Findings
- Average release speed declined from 89.5 mph in 2015 to 86.4 mph in 2019.
- Opposing exit velocity increased from 85.2 mph to 88.1 mph, suggesting harder contact allowed over time.
- Launch angle increased in 2019, indicating more elevated contact from opposing hitters.
- Pitch movement and release position shifted across seasons, suggesting mechanical or strategic adjustments.

## Tools Used
- R
- dplyr
- ggplot2
- plotly
- baseballr
- Statcast data

## Methods
- Pulled pitch-level Statcast data using `baseballr`
- Cleaned and combined seasonal datasets from 2015–2019
- Aggregated pitch metrics by game and season
- Visualized year-over-year trends in velocity, movement, launch angle, exit velocity, and pitch outcomes
- Compared changes in pitching profile against contact quality and batter result trends
