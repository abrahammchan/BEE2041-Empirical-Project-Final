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
Website Link: url for the website output

--- 

## Requirements 
Jupyter Notebook (to run python locally
Quarto (version: 1.9.37, mac OS)

---

## Creating Website (through Quarto on terminal)
- 1. Quarto create project blog 'myblog'
- 2. Quarto preview myblog (opens internally)
- 3. Manually edited _quarto.yml file, underneath type: website, change the output directories (output-dir: docs)
- 4. Manually upload quarto created folder 'myblog'
- 5. Drag _sites / docs out of my blog into main.
- 6. (Optional) delete myblog folder as unnecessary to run the website through github pages
- 7. Go to settings on github --> Pages --> Build and Deployment choose main and /docs and the website should run through github pages

---

## Creating the Python Tables and Figures (through jupyter notebook and terminal)
- 1. Download data from kaggle(https://www.kaggle.com/datasets/elvisbui/world-happiness-report-2005-2025-panel/data)
  2. Make directory (mkdir <name>)
  3. Move the csv file (after opening the downloaded zip file) into the new directory (can drag the data manually or use mv through terminal)
  4. Change directory 

