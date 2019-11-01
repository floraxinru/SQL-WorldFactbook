# SQL-WorldFactbook
Practice the Python SQLite workflow using CIA World Factbook data

This is a short and simple project. My goal is to practice writing queries and subqueries (nested queries) with SQLite in a JupyterNotebook. SQL is a popular tool required in most data analyst job postings. 

## Main tools used:

Python, SQLite, Pandas, Matplotlib(for histograms), JupyterNotebook


## Overview
In this project, I work with data from the CIA World Factbook database. It contains statistics about all of the countries on Earth. The Factbook contains demographic information such as population (as of 2015), population_growth, and area.

I explore aspects such as population density (population divided by land area), and ratios of water area to land area. I also visualize data by plotting histograms using Pandas and Matplotlib. I used Pandas to run SQL queries to display the results neatly as a DataFrame object in the JupyterNotebook environment. 


## Data
I have uploaded the SQLite database, factbook.db. You can also download it from this GitHub repo: https://github.com/factbook/factbook.sql/releases. 


## Installation and Usage

Install the requirements for this project using pip install -r requirements.txt. This will install the exact version of the libraries that I had when doing this project.

## Findings
It was surprising to me that Bosnia and Herzegovina has the highest ratio of water to land in the world. Also I was surprised to find Macao has over three times the population density of Hong Kong (which has an extremely high population density already), while their area ratio is 1 to 40.


## References:
This project is from the DataQuest Data Scientist Path - SQL Fundamentals course.

