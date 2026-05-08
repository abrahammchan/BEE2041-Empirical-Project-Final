# BEE2041 Empirical Project 

## Project Overview
This project aims to be a further analysis of the world happiness report (WHR) with their data from 2019 to 2025.
The WHR combines wellbeing data from over 140 countries in order to try and understand why people feel happy and the knowledge on how to improve it.

---

## The Data
The dataset ('world_happiness_report_2005_2025.csv') comes from the annual report (2025) by the University of Oxford's Wellbeing Research Centre in partnership with Gallup, the UN Sustainable Development Solutions Network, and their Editorial Board. It is in csv format and read through pandas python library.

| Variable | Description |
|---|---|
| year | Calendar year the responses cover |
| rank_in_year | Rank within that year (1 is happiest) |
| country | Country name |
| happiness_score | 3-year rolling Cantril Ladder average, 0 to 10 |
| lower whisker | Lower bound of the 95% CI on the score |
| upper whisker | Upper bound of the 95% CI on the score |
| explained_log_gdp_per_capita | Contribution of log GDP per capita |
| explained_social_support | Contribution of social support |
| explained_healthy_life_expectancy | Contribution of healthy life expectancy |
| explained_freedom | Contribution of freedom to make life choices |
| explained_generosity | Contribution of generosity |
| explained_corruption | Contribution of low perceptions of corruption |
| dystopia_plus_residual | Dystopia baseline plus the regression residual |

## Repository Structure

Final Project Data and Code: Original csv file of the World Happiness Report (downloaded from kaggle) and python code used to clean, sort and arrange data
docs: github pages runs website through these files
README.md

