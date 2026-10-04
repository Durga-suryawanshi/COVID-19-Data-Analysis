# COVID-19 Data Analysis

### Data Science Internship Project — Task 1

## Project Overview

This project analyzes COVID-19 data to understand the trends in confirmed cases, recoveries, and deaths over time.

The project focuses on data loading, data cleaning, statistical analysis, and data visualization using Python.

## Objective

The main objectives of this project are:

- Analyze daily confirmed COVID-19 cases
- Analyze daily recoveries
- Analyze daily deaths
- Identify peak values and their dates
- Visualize COVID-19 trends over time
- Perform basic statistical analysis

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset Information

The dataset contains COVID-19 time-series information including:

- Date
- Daily Confirmed
- Total Confirmed
- Daily Recovered
- Total Recovered
- Daily Deceased
- Total Deceased

The dataset contains **474 records and 8 columns**.

## Data Cleaning

The dataset was checked for missing values and data types.

- No missing values were found.
- The `Date_YMD` column was converted into datetime format for time-based analysis.

## Data Analysis

The following analysis was performed:

- Total confirmed cases
- Total recoveries
- Total deaths
- Average daily confirmed cases
- Average daily recoveries
- Average daily deaths
- Peak confirmed cases and date
- Peak recoveries and date
- Peak deaths and date

## Visualizations

The project includes line charts showing:

- Daily confirmed COVID-19 cases
- Daily recoveries
- Daily deaths
- Combined trend of confirmed cases, recoveries, and deaths

## Key Insights

- Daily confirmed cases show the changing trend of COVID-19 infections over time.
- Daily recoveries show how the number of recovered patients changed during the study period.
- Daily deaths show the variation in COVID-19 fatalities.
- Peak values of confirmed cases, recoveries, and deaths were identified using Pandas.
- Date-time conversion helped in performing time-based analysis.
- No missing values were found in the dataset.

## Project Files

- `COVID_19_Analysis.ipynb` — Jupyter Notebook containing the complete analysis
- `India_Covid_TimeSeries.csv` — Dataset used for the analysis

## How to Run

1. Download or clone this repository.
2. Open `COVID_19_Analysis.ipynb` in Jupyter Notebook.
3. Make sure `India_Covid_TimeSeries.csv` is available.
4. Run the notebook cells sequentially.

## Internship Task

This project was completed as part of the **Data Science Internship — Task 1**.

The task requires analyzing a COVID-19 dataset using Pandas and Matplotlib/Seaborn and creating visualizations for daily cases, deaths, and recovery trends. 0
