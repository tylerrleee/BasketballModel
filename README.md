# 🏀 NBA MVP Predictor – Fall 2023 MAD2502 Capstone Project

This project was developed as the final capstone for the University of Florida's Introduction to Computational Math (MAD2502) course in Fall 2023. The goal was to analyze NBA player statistics, determine the most influential metrics for winning the MVP award, and build a predictive model to evaluate current players’ chances of becoming MVP.
[YOUTUBE VIDEO](<https://www.youtube.com/watch?v=XnuaGsIK2gU>)
## 🔍 Overview

We scraped real-time data from [Basketball-Reference.com](https://www.basketball-reference.com/), processed and cleaned it, and built both a statistical regression model and a user-friendly GUI to:

- Predict potential future MVPs based on their performance
- Analyze which stats are most significant for MVP selection
- Compare player-to-player performance and efficiency

## 🛠️ Features

### 📦 1. Web Scraper (`Capstone Indexing Code.ipynb`)
- Automatically collects player stats from Basketball Reference.
- Targets key performance metrics across multiple seasons.
- Outputs structured data for analysis and modeling.

### 🧹 2. Data Cleaning & Filtering (`BB_filter.ipynb`)
- Filters out incomplete or irrelevant data.
- Converts text-based stats into numeric values.
- Organizes data for regression and visualization.

### 📊 3. MVP Regression Model
- Uses linear regression to analyze trends among previous MVPs.
- Identifies which stats (e.g., PPG, APG, Efficiency) are most predictive.
- Applies the model to current players for future MVP predictions.

### 🖥️ 4. GUI Interface (`Basketball Stats GUI.ipynb`)
- Allows users to interactively compare two NBA players.
- Provides a clean interface for filtering and visualizing data.
- Displays predictions based on selected stats.

## 📈 Tools & Libraries
- `pandas` – data cleaning and manipulation
- `numpy` – mathematical modeling
- `matplotlib` / `seaborn` – data visualization
- `sklearn` – regression modeling
- `tkinter` – graphical user interface (GUI)
- `BeautifulSoup` – web scraping

## 📊 Example Use Cases
- Compare LeBron James and Nikola Jokić based on MVP-worthy stats
- Analyze how Player Efficiency Rating (PER) affects MVP likelihood
- Predict which current players are most likely to win MVP next season

## 👨‍💻 Team
- Tien Tyler Le
- Gaston D.
- Thorin Groth
- Filipe

## 🎓 Course Information
This project was developed for:
**MAD2502: Introduction to Computational Mathematics**  
University of Florida, Fall 2023  
Instructor: [Instructor Name]

## 📝 License
This project is for academic use only. Data sourced from [Basketball-Reference.com](https://www.basketball-reference.com/).
