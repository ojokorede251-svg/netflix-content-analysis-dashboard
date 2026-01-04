# Netflix Content Analysis Dashboard

## Description
An interactive Power BI dashboard exploring a dataset of ~8,800 Netflix movies and TV shows (up to 2021). Analyzes trends in content addition over time, ratings distribution, top genres, global country availability, and per-title details like cast, directors, and descriptions.

## Tools Used
- Power BI Desktop for data import (from Excel), modeling, DAX calculations, and visualizations.
- Excel dataset with normalized sheets (titles, descriptions, cast, genres, directors, countries).

## Key Insights
- Content growth: Additions peaked in 2018-2020, with movies outpacing TV shows.
- Ratings: TV-MA is the most common (over 3,000 titles), followed by TV-14 and R.
- Top genres: International Movies (~2.7K), Dramas (~1.6K), Comedies (~1.2K).
- Geography: US leads with thousands of titles, followed by India, UK, and others—visualized on a world map.
- Interactive features: Filters for rating/release year, drill-down to title specifics (e.g., "Apollo 18" details shown).

## Files
- netflix_titles_NEW.xls: Source dataset (or sample; full from Kaggle if needed).
- Netflix+Dashboard Analysis.pdf: Exported report (2 pages).
- main-dashboard.png: Screenshot of overview (trends, ratings, genres, map).
- single-title-view.png: Alternate view (release year, rating, description, mao).
- title-details.png: Screenshot of title details in excel sheet (dste added, duration, etc.).
- netflix-dashboard.pbix: Power BI file (open in Power BI Desktop to interact).

## How to Run/View
1. Download .pbix.
2. Open in Power BI Desktop (free from Microsoft).
3. Refresh data/connect to dataset if needed; explore slicers and filters.

This project demonstrates ETL from Excel, data normalization, and business insights for content strategy.
