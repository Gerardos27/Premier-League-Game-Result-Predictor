# Premier-League-Game-Result-Predictor

**Author:** Gerardo Sandoval  
**Language:** Python  

---

## Overview

This project is a data-driven tool designed to predict the outcome of Premier League football matches using **Python, Pandas, Matplotlib, and API data**. The model analyzes match commentary and statistics to identify features that influence game results.  

Key factors include:  
- **Referee officiating the game** (primary factor)  
- **Team formation** (secondary factor)  
- **Key players’ frequency in commentary** using a **word cloud** (tertiary factor)  

By analyzing which players are most frequently mentioned in commentary, the project identifies impactful players and their influence on match outcomes.

---

## Features

- **Data Retrieval:** Pulls match data and commentary using APIs.  
- **Data Analysis:** Uses Pandas to clean and process datasets.  
- **Visualization:** Matplotlib and WordCloud for exploring key player mentions and match insights.  
- **Outcome Prediction:** Determines likely match results based on referee, formation, and player commentary frequency.  
- **Feature Prioritization:** Weights referee influence first, formation second, and player commentary last.

---

## How to Use

1. Open the Jupyter Notebook
   ```bash
   jupyter notebook Premier_League_Project.ipynb

---

## Skills Demonstrated

- Python programming and data manipulation with Pandas
- API usage for real-time data retrieval
- Data visualization with Matplotlib and WordCloud
- Feature engineering and predictive modeling
- Analysis of textual commentary to extract meaningful features
