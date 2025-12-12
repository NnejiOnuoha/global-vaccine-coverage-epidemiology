# global-vaccine-coverage-epidemiology
Applied epidemiology project analyzing global COVID-19 vaccination coverage and disparities using Python, with emphasis on reproducible methods and public health interpretation.
Global COVID-19 Vaccination Coverage: An Applied Epidemiology Analysis

This project analyzes global COVID-19 vaccination coverage using publicly available datasets from Our World in Data (OWID). It focuses on temporal trends, cross-country comparisons, and disparities across continents. The goal is to demonstrate applied epidemiologic reasoning using real-world data, reproducible workflows, and clear public health interpretation.

📌 Research Question

How did COVID-19 vaccination coverage evolve globally, and what disparities existed across countries and continents?

📂 Dataset

Source: Our World in Data (OWID) – COVID-19 Vaccinations
Includes:

Total vaccinations

People vaccinated (one dose)

People fully vaccinated

Daily vaccinations

Vaccinations per 100 people

Country-level metadata

The analysis uses the country-level vaccination dataset only.

🧹 Methods
1. Data Cleaning

Selected relevant columns

Handled missing values

Converted dates to datetime format

Extracted the latest vaccination record per country

Merged continent information for comparisons

2. Exploratory Data Analysis

Summary statistics

Identification of vaccination coverage disparities

Cross-continental comparison

Time-series visualization for selected countries

3. Visualization

Built using Python, Pandas, and Seaborn:

Bar chart comparing continents (vaccinations per 100 people)

Line plots showing vaccination trends over time for multiple countries

📊 Key Findings

Europe and South America achieved the highest vaccination coverage per 100 people.

Africa had the lowest vaccination coverage, highlighting global inequities.

Time-series trends reveal early rapid uptake in high-income countries and delayed or slow uptake in several low- and middle-income countries.

🔍 Epidemiological Significance

This project demonstrates core applied epidemiology skills:

Working with open public health data

Cleaning and transforming real-world datasets

Producing clear, reproducible analyses

Interpreting trends in a population-health context

Communicating findings concisely and effectively

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Jupyter Notebook

📄 Project Structure
/notebooks
    └── covid_vaccination_analysis.ipynb
/data
    └── vaccinations.csv
README.md

📘 How to Use

Clone the repo

Install required libraries

Open the notebook

Run the analysis or modify it for your own exploration

📢 About

This analysis is part of my growing portfolio in Applied Epidemiology, Public Health Data Science, and Global Health Analytics.
