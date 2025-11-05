<!-- Banner Typing Animation -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=6C5CE7&center=true&vCenter=true&width=900&lines=📊+Data+Preparation;🧹+Data+Cleaning+%26+Processing;💻+Python+Pandas;📋+Jupyter+Notebooks" alt="Typing SVG" />
</p>

---

# 🚀 Data Preparation: Cleaning & Processing

This module covers **preparing and cleaning data** in Python using **Pandas**. Topics include handling missing values, duplicate removal, mapping/replacing data, grouping, working with datetime, and useful functions for practical data preparation. Exercises are included in **Jupyter Notebooks** and Kaggle.

---

## 🧩 Module Structure

| Section | Description |
|---------|-------------|
| Introduction | Overview of data preparation concepts |
| .dropna() – Removing NaN values | Learn to drop missing values from DataFrames |
| 📋 Jupyter Notebook: df.dropna() | Hands-on exercises using df.dropna() |
| .fillna() – Filling NaN values | Learn to fill missing values with defaults or statistics |
| 📋 Jupyter Notebook: df.fillna() | Hands-on exercises using df.fillna() |
| Removing duplicates | Drop repeated rows from a DataFrame |
| .map() – Mapping values | Transform data using map() |
| .replace() & .rename() | Replace or rename column values |
| 📋 Jupyter Notebook: drop_duplicates(), map(), replace(), rename() | Exercises combining multiple cleaning functions |
| .cut() & .qcut() for binning | Group numeric data into intervals |
| 📋 Jupyter Notebook: Binning with cut() & qcut() | Hands-on binning exercises |
| .groupby() | Aggregate and group data for analysis |
| 📋 Jupyter Notebook: Grouping with df.groupby() | Grouping exercises |
| Handling outliers | Detect and handle unusual data points |
| Random sampling from a table | Learn how to sample random rows |
| 📋 Jupyter Notebook: Useful functions | Practice functions for data cleaning |
| Kaggle Introduction | Overview of Kaggle datasets and workflow |
| Python datetime | Working with datetime objects in Python |
| Convert text to datetime | Parsing text columns to datetime format |
| Working with datetime | Perform operations on datetime columns |
| 📋 Kaggle: Datetime | Exercises using datetime on Kaggle datasets |
| 📋 Jupyter Notebook: Datetime | Local exercises with datetime in Jupyter |
| 🔗TEST 1: dropna() | Interactive test for dropna() |
| 🔗TEST 2: fillna() | Interactive test for fillna() |
| Practical Exercise: Data Preparation | Hands-on full data cleaning workflow |
| TEST 1: dropna() | Assessment test |
| TEST 2: fillna() | Assessment test |
| Final Practical Exercise | End-of-module comprehensive data preparation task |

---

## 🛠 Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BehruzMaxmudov1203&show_icons=true&theme=tokyonight" alt="GitHub Stats" /> 
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=BehruzMaxmudov1203&theme=tokyonight" alt="GitHub Streak" /> 
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=BehruzMaxmudov1203&theme=react-dark" alt="GitHub Activity Graph" /> 
</p>

---

## 📌 Example: Handling Missing Data

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=FF6F61&center=true&vCenter=true&width=800&lines=dropna()+fillna();Clean+your+data;Pandas+practical" alt="Typing SVG" />
</p>

```python
import pandas as pd

# Drop rows with missing values
df_clean = df.dropna()

# Fill missing values with a default or statistic
df['salary'] = df['salary'].fillna(df['salary'].mean())

# Remove duplicate rows
df = df.drop_duplicates()

# Map or replace values
df['department'] = df['department'].map({'HR':'Human Resources', 'IT':'Information Tech'})

# Grouping example
grouped = df.groupby('department')['salary'].mean()
