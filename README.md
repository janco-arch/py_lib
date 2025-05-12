# COVID-19 Data Analysis

This project uses Python and Pandas to analyze COVID-19 data from a CSV file. It includes data cleaning, handling missing values, and visualizing the data using graphs.

## Features

1. **Inspecting the Data**
   - Display the columns in the dataset.
   - Display the first 10 rows of the dataset using `head(10)`.

2. **Handling Missing Values**
   - Check the number of null values in each column using `isnull().sum()`.
   - Drop rows where the `date` column is missing.
   - Fill remaining null values with `0`.

3. **Data Visualization**
   - Plot a graph comparing `location` data against `total cases`.
   - Plot a graph comparing `location` data against `total deaths`.
   - Plot a bar graph comparing `location` data against `new cases`.

## Requirements

- Python 3.x
- Pandas
- Matplotlib

## How to Run

1. Install the required libraries:
   ```bash
   pip install pandas matplotlib
