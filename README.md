# 2025 Wrapped — Personal Media Analytics Platform

How do my digital habits reflect how I spend my life, energy, and attention?

A multi-platform personal analytics project built in Power BI, inspired by Spotify Wrapped. This report analyzes my real 2025 media consumption data across Netflix, Spotify, YouTube, and TikTok to uncover patterns in how I spend my time, attention, and energy on digital entertainment.

## Project Status
Platform                       Status 
Netflix                        Complete
Spotify                        In Progress
YouTube                        In Progress
TikTok                         In Progress
Cross-Platform Comparison      In Progress

## Objective
Analyze personal media consumption patterns to understand how digital entertainment shapes daily routines, energy levels, and time allocation — while demonstrating professional analytics practices in behavioral data analysis.

## Key Questions
Where did my attention go in 2025, and how much time was spent on each platform?
Which platform retained me best, and how frequently did I return?
How did my behavior change over time — which months were highest and lowest?
Were certain days of the week higher than others?
What does my "ideal" media consumption day look like, laid out by hour?
Which platforms are substitutes vs. complements? Does TikTok reduce Netflix usage? Does Spotify spike after YouTube discovery?


## Tools & Skills
Power BI Desktop — data modeling, report design, and visualization
DAX — calculated columns, measures, and KPI logic
Power Query — data transformation and cleaning
Star Schema Modeling — fact table with DateTable dimension
Data Storytelling — narrative-driven report design


## Data Sources
All data was exported directly from each platform's personal data download feature. Raw data files are not included in this repository to protect personal privacy.

## Netflix — Report Pages
1. Main KPI Overview
A billboard-style summary page covering total hours watched, unique titles, completion rate, movies vs. shows breakdown, and viewing trend by season.
2. Movies vs. TV Shows
A side-by-side comparison of movie and show viewing behavior including hours watched, completion rates, average duration, top titles, and viewing patterns by month and time of day.
3. Timings
A deep dive into when I watch — peak hour, day of week, month, and season. Features a day-of-week vs. hour-of-day heatmap built using a Matrix visual with conditional formatting.
7. Netflix Summary
A narrative closing page with key findings, hypothesis results, and a written interpretation of what the data says about my viewing habits.

## Hypotheses Going In
Short-form content (TikTok) dominates total attention time
YouTube shows the highest platform loyalty and retention
Spotify shows the widest variety of genres
Late nights are peak Netflix time — movies and shows to wind down
Noon is peak TikTok time

## Results and findings will be documented here as each platform is completed.

## Repository Structure
2025-Wrapped/
│
├── README.md
├── 2025_Wrapped.pbix
│
├── screenshots/
│   ├── netflix/
│   ├── spotify/
│   ├── youtube/
│   └── tiktok/
│
└── docs/
    └── project_summary.md

## Privacy Note
All data used in this project is sourced from my own personal platform exports. No raw data files are included in this repository. 

## About
Built by Zoe — Grants Administrator turned aspiring data analyst. This project is part of an ongoing portfolio demonstrating skills in Power BI, DAX, data modeling, and analytics storytelling.
