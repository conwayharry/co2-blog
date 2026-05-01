# Economic Growth and CO2 Emissions

## Overview

This project investigates the relationship between economic growth and carbon dioxide (CO2) emissions across countries at different stages of development. The analysis focuses on China, India, Germany, and the United States, comparing how emissions change alongside income, efficiency, and over time.

The aim is to determine whether economic growth inevitably leads to higher emissions, or whether more developed economies are able to decouple growth from environmental impact.

---

## Data

The data is sourced from the Our World in Data CO2 dataset.

A cleaned dataset (`data_clean.csv`) is included in this repository. This contains only the variables, countries, and years used in the analysis (China, India, United States, Germany, from 2000 onwards).

---

## How to Run

1. Download or clone this repository
2. Open `blog.ipynb` in Jupyter Notebook
3. Run all cells:

   * Kernel → Restart & Run All

All figures and tables will be reproduced automatically.

---

## Project Structure

* `blog.ipynb` — main notebook containing analysis, graphs, and written discussion
* `data_clean.csv` — cleaned dataset used for all analysis

---

## Methods

The analysis uses:

* Data cleaning and filtering in Python (pandas)
* Data visualisation (matplotlib)
* Correlation analysis
* Regression modelling (log-log OLS) to estimate elasticities

---

## Key Findings

* Developing economies (China and India) show a strong positive relationship between income and emissions
* Developed economies (Germany and the United States) show evidence of decoupling, with emissions stabilising or declining as income rises
* All countries improve in efficiency over time, but only developed economies achieve absolute reductions in emissions

---

## Requirements

* Python 3
* pandas
* numpy
* matplotlib
* statsmodels

---

## Notes

The notebook is fully reproducible and does not rely on any local file paths.
