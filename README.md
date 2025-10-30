# SpaceX Falcon 9 Launch Data Analysis

This repository contains the work completed for the IBM Data Science Professional Certificate Capstone Project.
The goal of the project is to analyze SpaceX Falcon 9 rocket launch data to identify factors that influence launch success and to predict future outcomes.

Project Overview

SpaceX aims to reduce the cost of space travel by developing reusable rockets.
In this project, Falcon 9 launch data was collected, cleaned, and analyzed to explore the relationship between launch success, payload mass, orbit type, and booster version.
The project also includes interactive visualizations and a classification model to predict launch outcomes.

Notebooks and Descriptions

- jupyter-labs-spacex-data-collection-api.ipynb
Collected launch data from the SpaceX REST API and created a structured DataFrame for analysis.

- jupyter-labs-webscraping.ipynb
Scraped additional launch details from Wikipedia to complement the API dataset.

- labs-jupyter-spacex-Data-wrangling.ipynb
Performed data wrangling, handled missing values, and merged datasets into a clean, consistent format.

- edadataviz.ipynb
Conducted exploratory data analysis (EDA) using Python visualization libraries such as Matplotlib and Seaborn to identify patterns and trends.

- jupyter-labs-eda-sql-coursera_sqllite.ipynb
Performed SQL-based EDA using SQLite to query and analyze the launch data.

Tools and Technologies

- Python, Pandas, NumPy, Matplotlib, Seaborn

- SQLite for SQL analysis

- Requests and BeautifulSoup for data collection

- Folium and Plotly Dash for interactive visualizations

- Scikit-learn for machine learning classification

Key Insights

- Cape Canaveral had the highest number of successful launches.

- Payloads between 2000 and 6000 kg showed the highest success rates.

- Booster version FT had the best performance.

- The Decision Tree model achieved the highest prediction accuracy.

Repository Contents

- All Jupyter Notebooks used during the project

- Supporting datasets (loaded from public URLs)

- Final project presentation in PDF format

Author: Esra Çınar
IBM Data Science Professional Certificate – Capstone Project
