# Football Analysis - 2025 Matches

This repository contains a Jupyter notebook analyzing football match data from the 2025 season of **Premier League, Serie A, and La Liga**. The analysis focuses on match statistics, team performance, and general trends using Python data analysis libraries.

## Dataset

- **File:** `football_matches.csv`  
- **Scope:** Matches from 2025
- **Columns include:**  
  - `ID`, `Date`, `League`, `Home_Team`, `Away_Team`  
  - Scores: `Home_Team_Score`, `Away_Team_Score`  
  - Cards: `Home_Team_Yellowcard`, `Away_Team_Yellowcard`, `Home_Team_Redcard`, `Away_Team_Redcard`  
  - Shots & possession: `Home_Team_Shots`, `Away_Team_Shots`, `Home_Team_ShotsonTarget`, `Away_Team_ShotsonTarget`, `Home_Team_Possession`, `Away_Team_Possession`  
  - Passes, fouls, offsides, corners: `Home_Team_Passes`, `Away_Team_Passes`, `Home_Team_Fouls`, `Away_Team_Fouls`, `Home_Team_Offside`, `Away_Team_Offside`, `Home_Team_Corner`, `Away_Team_Corner`  

> **Note:** The dataset in this repository is a **snapshot** and may differ from the live dataset on Kaggle, which updates daily.

## Notebook

- **File:** `your_notebook.ipynb`  
- The notebook performs:  
  - Data exploration (`head()`, `info()`, `describe()`)  
  - Summary statistics  
  - Visualizations such as team performance, goals, cards, win percentage, and clean sheets

## How to Run

1. Download or clone this repository.  
2. Make sure `football_matches.csv` is in the same folder as the notebook.  
3. Open `your_notebook.ipynb` in **Jupyter Notebook** or **Google Colab**.  
4. Run all cells to reproduce the analysis.

## Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  

## Optional Notes
 
- Outputs in GitHub are static snapshots; to see live results, run the notebook locally or on Colab.
