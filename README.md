# Portuguese League Match Outcome Prediction

This repository contains a data science project focused on predicting football match outcomes in the **2024/25 Portuguese Primeira Liga**, with a particular focus on **Santa Clara**. The project combines **data extraction, preprocessing, exploratory data analysis, dashboarding, and predictive modelling** to understand whether match statistics can help predict the result of a football game. :contentReference[oaicite:0]{index=0}

## Project Goal

The main objective of this project was to evaluate whether the outcome of a football match in the Portuguese league could be predicted using match-level statistical data from the **2024/25 Primeira Liga** season. A specific focus was placed on **Santa Clara**, with the goal of building a model capable of predicting the outcome of Santa Clara matches. :contentReference[oaicite:1]{index=1}

## Project Workflow

The project was structured into four main stages:

1. **Data Extraction**  
   Match data was collected from an API providing detailed statistics for each game of the 2024/25 Primeira Liga season. The raw data was then inspected and converted into CSV format for analysis. :contentReference[oaicite:2]{index=2}

2. **Data Preprocessing**  
   Variables were grouped by type and organised into analytical categories such as offensive strength and ball possession. Missing values were handled using methods such as 50/50 imputation and team median replacement. :contentReference[oaicite:3]{index=3}

3. **Exploratory Data Analysis**  
   The analysis explored relationships between team statistics and league performance, focusing on offensive, defensive, possession, and fair play metrics. A dedicated analysis was also carried out for Santa Clara. :contentReference[oaicite:4]{index=4}

4. **Predictive Modelling**  
   Features were selected and transformed to support model development. The final model was designed to predict the outcome of Santa Clara matches. :contentReference[oaicite:5]{index=5}

## Main Insights

The project generated several relevant insights:

- teams with stronger offensive indicators such as shots, corners, and possession tended to finish higher in the league table
- defensive indicators also appeared to be associated with league position
- discipline-related statistics seemed less correlated with final standings
- Santa Clara ranked below league average in several offensive metrics despite finishing **5th**
- Santa Clara’s defensive indicators were closer to league averages
- Santa Clara showed meaningful differences between home and away performance. :contentReference[oaicite:6]{index=6}

## Model Results

The final predictive model achieved an **accuracy of 58%** when predicting Santa Clara match outcomes. Although this result is still far from perfect, it performed better than random guessing and showed that match statistics already contain useful predictive information. The project also concluded that incorporating additional features, such as player-level data, could further improve performance. :contentReference[oaicite:7]{index=7}

## Dashboard

As part of the project, a dashboard was developed to allow team-by-team exploration of the key metrics analysed.

Streamlit app: `https://primeira-liga-2024-app.streamlit.app` :contentReference[oaicite:8]{index=8}

## Tech Stack

- **Python**
- **Pandas**
- **Jupyter Notebook**
- **Machine Learning**
- **Data Preprocessing**
- **Exploratory Data Analysis**
- **Streamlit**
- **CSV / API-based data collection**

## Repository Structure

```text
portuguese-league-match-outcome-prediction/
├── notebooks/
│   └── primeira_liga_match_outcome_prediction.ipynb
├── data/
│   └── primeira_liga_2024_2025_raw_data.csv
├── docs/
│   └── primeira_liga_project_presentation.pptx
├── README.md
└── .gitignore
