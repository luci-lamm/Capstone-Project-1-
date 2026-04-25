# Capstone Project 1- Mapping the Danger Zone: A Multi-Factor Statistical Analysis of Geography, Weather, and Infrastructure on Road Safety

## Overview
This project conducts a multi-factor statistical analysis of U.S. traffic accident data (2016–2023) to understand how geography, weather conditions, and road infrastructure influence accident frequency and severity.

## Key Findings
* Traffic accidents are heavily concentrated in urban areas and peak commuting hours (45.14% of incidents occur during the 6-hour rush window).
* Weather and visibility conditions act as significant risk multipliers for accident severity.
* Infrastructure features like junctions and crossings show a high correlation with incident frequency.

## Repository Contents
* **[`DS_Capstone_Notebook.ipynb`](DS_Capstone_Notebook.ipynb)**: Full data cleaning, EDA, and preprocessing pipeline.
* **[Cleaned_Accident_Data.csv](https://drive.google.com/file/d/1qxGFaU2Cwv-EOtFHkdZQKWFZCQ4iX4cT/view?usp=sharing)**: Hosted on Google Drive (157MB).
* **[Interactive Tableau Dashboard](https://public.tableau.com/views/CapstoneProjectTableau_17770959960700/Overview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**: Live interactive analysis.

## Visuals
![Main Dashboard](Home.jpg)
![Weather Analysis](Weather%20.jpg)
![Infrastructure Analysis](Stop%20Sign.jpg)
![Technical Analysis](Screenshot%202026-04-24%20at%2011.09.31 PM.png)

## Data Preprocessing
* **Missing Values:** Handled nulls in weather and visibility coordinates.
* **Feature Engineering:** Extracted hour/day/month to identify peak windows.
* **Filtering:** Segmented data into Urban vs. Rural categories.

