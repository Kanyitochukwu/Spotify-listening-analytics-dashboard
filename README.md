# Spotify-listening-analytics-dashboard
Analysis of my Spotify listening habits using Power BI.

Project Overview

This project analyzes my personal Spotify streaming data to uncover patterns in my music listening habits. Using Spotify’s exported account data in JSON format, I cleaned, transformed, and visualized the data to generate insights about my listening behavior over time using Power BI.

Tool Used:

Power BI – Data cleaning, transformation, data modeling, analysis, and interactive dashboard creation.

Data Source:

The dataset was obtained from my personal Spotify account data export. The primary files used were the streaming history datasets, which contain information such as timestamps, artists, tracks, and milliseconds played.

Data Preparation:

The raw JSON files were imported into Power BI and transformed into a structured format for analysis. Key preparation steps included:

Combining multiple streaming history files into a single dataset

Converting milliseconds played into minutes

Cleaning unknown or missing artist and track names

Splitting timestamps into separate date and time fields

Creating a date table for time-based analysis

Key Metrics Created:

Using DAX measures in Power BI, the following metrics were developed:

Total Listening Time

Average Listening Time per Day

Most Played Artists

Most Played Tracks

Daily Listening Duration

Longest Listening Streak

Listening time was formatted into hours and minutes for better readability across visuals and tooltips.

Dashboard Features:

The dashboard provides an interactive view of my Spotify listening behavior, including:

Total listening time overview

Top 10 most played artists

Top 5 most played tracks

Monthly listening trends

Listening streak analysis

Custom tooltips and formatted measures were used to display listening time clearly in hours and minutes.

Insights

The analysis reveals patterns in my music consumption such as:

Which artists and tracks I listen to the most

How my listening time varies across days

Consistency in listening habits over time

Outcome

This project demonstrates practical data analytics skills including data cleaning in Power Query, data transformation, DAX calculations, and dashboard design using Power BI.

It also highlights how personal datasets can be used to practice real-world analytics and generate meaningful insights.
