# EDA-on-IPL-Matches
Exploratory Data Analysis (EDA) on IPL dataset using Python to uncover team and player performance trends.

[![Python](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview  
This project performs EDA on IPL matches and deliveries data from 2008 to 2023 (or whatever years you used). The goal is to discover patterns, trends, and insights about player performance, team strategies, match outcomes, and toss influence.

## Motivation  
Why IPL? Because it’s data-rich, sports analytics is a growing field, and it’s fun to get insights people care about (e.g. “Does winning toss help?”).

## Dataset  
- `matches.csv` — metadata about each match (team, season, venue, winner, toss)  
- `deliveries.csv` — ball-by-ball data (runs, extras, batsman, bowler)  
Data source: [Kaggle – IPL dataset](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020?select=matches.csv)  

## Key Findings / Highlights  
- Team A has highest win rate over seasons  
- Toss winning gives ~X% advantage  
- Batsman Y shows consistently high strike rate in death overs

## Recommendations

- Teams should focus on improving death over strategies.
- Players with high batting averages should be promoted in the batting order.

## Tools & Libraries  
- Python, Pandas, NumPy  
- Seaborn, Matplotlib, Plotly  
- Jupyter Notebook  
