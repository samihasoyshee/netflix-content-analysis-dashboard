# Netflix Content Dashboard

An interactive Power BI dashboard analyzing Netflix's global content library — exploring the split between movies and TV shows, genre trends, ratings distribution, and content growth over time.

## Project Overview

This project takes the Netflix Titles dataset (8,800 movies and TV shows) through a full data cleaning and analysis workflow, then visualizes it in an interactive Power BI dashboard to surface trends in Netflix's content catalog.

## Objective

- Clean and prepare raw Netflix catalog data for analysis
- Handle missing values and inconsistent formatting
- Build measures to track content volume and duration
- Design an interactive dashboard to explore content trends by year, country, genre, and rating

## Dataset

- **Source:** Netflix Titles dataset (Kaggle)
- **Size:** ~8,800 rows
- **Fields:** title, type (Movie/TV Show), director, cast, country, date added, release year, rating, duration, genres (listed_in), description

## Data Cleaning

- Verified and corrected data types across all columns
- Checked for and removed duplicate records (0 found)
- Identified and handled missing values:
  - Director (315 missing)
  - Cast (97 missing)
  - Country (306 missing)
- Split multi-value fields (genres) for accurate categorical analysis

## Dashboard Features

- **KPI Cards:** Total Movies, Total TV Shows, Total Shows, Average Duration
- **Movies vs. TV Shows** breakdown (pie chart)
- **Content Trend by Year** — line chart of movies vs. TV shows added over time
- **Content by Country** — interactive map
- **Top Genres** — clustered column chart
- **Rating Distribution** — clustered bar chart
- **Shows by Director** — pie chart
- **Show Type Slicer** for interactive filtering

## Tools Used

- **Power Query** — data cleaning and preparation
- **Power BI** — data modeling (DAX measures) and dashboard design

## Key Insights

- Movies make up the majority of Netflix's catalog compared to TV shows
- Europe contributes the largest share of titles
- Content additions peaked around 2019
- Documentary is the most common genre across the catalog



## How to View

Download `Netflix Content Analysis Dashboard.pbix` and open it in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) 

## Screenshot

<img width="1276" height="716" alt="Screenshot 2026-08-16 224055" src="https://github.com/user-attachments/assets/a62fd8d4-7bd4-4e3e-a7cd-e8005b3807f5" />


