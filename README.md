# Netflix Movies and TV Shows: EDA Report

## About
This project explores the Netflix catalogue. I cleaned the data, asked five questions and answered each one with a chart.

## Dataset
- Netflix Movies and TV Shows (Kaggle, by shivamb): https://www.kaggle.com/datasets/shivamb/netflix-shows
- 8807 rows and 12 columns. Each row is one title.
- The data file is not in this repo. Download `netflix_titles.csv` and put it in a folder named `data`.

## Questions and findings
1. **Movies vs TV Shows:** Movies are 6131 titles (69.6%) and TV Shows are 2676 titles (30.4%).
2. **Top 10 countries:** The United States has the most titles. 831 titles (9.4%) have no country and are not counted.
3. **Titles added per year:** Additions grew quickly after 2015 and peaked in 2019. 10 titles have no date.
4. **Movies and TV Shows per year:** Movies were added more than TV Shows in almost every year.
5. **Release years:** Most titles were released recently. The median release year is around 2017.

## Tools
Python, Pandas, Seaborn, Matplotlib, Jupyter Notebook

## How to run
1. Download the dataset and place it in `data/netflix_titles.csv`.
2. Open `eda_report.ipynb` and click Run All.