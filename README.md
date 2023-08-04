![Python](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg) Python

![Pandas](https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg) Pandas

![Tableau](https://upload.wikimedia.org/wikipedia/commons/4/4b/Tableau_Logo.png) Tableau

# Football Analytics

## Summary:
This project aims to analyze football transfers across the top seven leagues (Premier League, La Liga, Ligue 1, Bundesliga, Serie A, Liga Portugal, and Eredivisie) using an interactive dashboard.

## 1 - Data Mining:
- I utilized an existing repository as the basis for transfer data.
- Locations of each club were scraped from Wikipedia.

## 2 - Data Cleaning:
- Duplicate transfers were removed.
- Clubs with missing location data were removed from the club table.
- Club names were standardized and corrected.

## 3 - Data Preparation:
- Various tables were merged to consolidate data.
- Longitude and latitude columns were added using the 'Geo' library in Python.

## 4 - Visualization:
I created two interactive dashboards using Tableau. 
- The first one contains an interactive flow map that displays transfers made by selected clubs within a specified year. 
- The second one is an interactive dashboard that displays the spending of each league, highlights the top spending and selling clubs, and showcases the top transfer players.
