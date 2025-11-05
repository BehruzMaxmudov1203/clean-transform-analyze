<!-- Banner Typing Animation with Gradient Colors -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&pause=800&color=FF5733,33FF57,3357FF&center=true&vCenter=true&width=900&lines=📂+Data+Processing;📊+Data+Preparation;💻+Python+SQL+Pandas;📋+Jupyter+Notebooks" alt="Typing SVG" />
</p>

---

# 🚀 Data Processing & Preparation

This module covers **file handling, web data extraction, JSON/API processing, and data preparation** in Python.  
You will learn how to:  

- 📁 Read and write data from files  
- 🌐 Extract data from web pages, JSON, and APIs  
- 🗄 Work with SQL and SQLite databases  
- 🧹 Clean and prepare data for analysis  
- 📅 Handle datetime operations and work with Kaggle datasets  

<p align="center">
  <img src="https://media.giphy.com/media/3o6Zt481isNVuQI1l6/giphy.gif" width="500" alt="Data Animation" />
</p>

---

## 🧩 Module Structure

### Files & Databases

| Section | Description |
|--------|--------|
| 📄 Introduction | Overview of the module |
| 📂 Reading from files | File I/O (txt, csv, etc.) |
| ✍️ Writing to files | Writing data to files |
| 🗃 HDF5 format | Storing large datasets |
| 📝 HDF5 Practical | Reading & writing HDF5 files |
| 📋 Jupyter Notebook: Files | Practical exercises with files |
| 🌐 Reading from web pages | HTML, requests, BeautifulSoup |
| 🗄 JSON & API | Understanding JSON and working with APIs |
| 🏗 Web/JSON/API Practical | Hands-on exercises |
| 🏛 Databases Introduction | SQL and SQLite basics |
| 🔌 Connecting to SQLite | Setting up and connecting to SQLite |
| 📊 Reading table to DataFrame | Loading SQL tables into Pandas DataFrame |
| 📈 Sorting & DISTINCT | ORDER BY and DISTINCT examples |
| 🔍 Filtering (WHERE) | Filtering data using WHERE |
| 💾 DataFrame to SQL | Exporting DataFrame to SQL tables |
| 🛠 SQL Table Operations | Creating, updating, deleting tables |
| ⚡ SQL with f-strings | Dynamic SQL commands using f-strings |
| 📌 Useful SQL commands | BETWEEN, IN, LIKE, JOINS, GROUP BY |
| 🖥 Jupyter Notebook: SQLite | SQL practical exercises |

### Data Preparation

| Section | Description |
|--------|--------|
| 🧹 Dropping NaN values | `.dropna()` |
| 💧 Filling NaN values | `.fillna()` |
| ❌ Removing duplicates | `drop_duplicates()` |
| 🔄 Mapping values | `.map()` |
| 🔀 Replacing & Renaming | `.replace(), .rename()` |
| 🗂 Grouping | `.cut(), .qcut(), .groupby()` |
| ⚠️ Handling outliers | Working with abnormal values |
| 🎲 Random sampling | Selecting random rows |
| 📅 Datetime operations | Converting text to datetime and using datetime functions |
| 🏆 Kaggle exercises | Practical exercises with Kaggle datasets |
| 🎯 Final practical exercise | Final data cleaning & preparation project |

---

## 🛠 Technologies Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
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

## 📌 Example: Cleaning NaN Values & Data Preparation

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=800&color=FF6F61,61FF6F,6161FF&center=true&vCenter=true&width=900&lines=dropna()+fillna();Remove+duplicates;Data+Preparation+practice" alt="Typing SVG" />
</p>

```python
import pandas as pd

# Dropping NaN values
df_clean = df.dropna()

# Filling NaN values with mean
df['salary'] = df['salary'].fillna(df['salary'].mean())

# Removing duplicate rows
df = df.drop_duplicates()

# Mapping values
df['department'] = df['department'].map({'HR':'Human Resources', 'IT':'Information Technology'})

# Grouping example
grouped = df.groupby('department')['salary'].mean()
