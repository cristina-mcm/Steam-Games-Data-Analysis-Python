# Steam Games Data Analysis

This project analyzes a large Steam games dataset using Python and Pandas. The goal was to practice working with a realistic dataset through data cleaning, preparation, API data integration, and exploratory analysis, while creating a dataset that can also support future visualization work in Power BI or Tableau.

The project:

1. Loads and reviews the original Steam games dataset.

2. Cleans and standardizes selected columns, including genres, categories, and tags.

3. Retrieves additional game information from the Gamalytic API.

4. Merges the two datasets using Steam application IDs.

5. Filters and prepares the matched records for analysis.

6. Explores the data using descriptive statistics, correlations, group comparisons, and visualizations.

## Repository Contents

- `Steam_2026_Data_Cleaning.ipynb` – Data cleaning, standardization, merging, and preparation
- `Retrieving_Gamalytic_API.ipynb` – API retrieval, pagination, and data extraction
- `Steam_2026_EDA.ipynb` – Exploratory analysis and visualizations
- `steam_games`.csv – Original Steam games dataset from Kaggle

README.md – Project documentation

### Data Cleaning and Preparation

* Removes unnecessary columns from the original Steam dataset.

* Cleans and standardizes genres, categories, and tags.

* Corrects inconsistent values and data types.

* Merges the Steam dataset with the Gamalytic data using Steam application IDs.

* Filters matched records and prepares the final dataset for analysis.

### API Data Retrieval

* Retrieves additional game-level information from the Gamalytic API.

* Uses pagination to collect available records across multiple API pages.

* Extracts fields such as estimated copies sold, publisher class, and review score.

* Saves the retrieved data for later integration with the original dataset.

### Exploratory Data Analysis

* Examines the structure, descriptive statistics, and missing values in the prepared dataset.

* Investigates correlations between numeric variables.

* Compares game performance across publisher classes and price categories.

* Examines distributions, extreme values, common genres, and release trends.

* Uses visualizations to explore patterns in the data.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Requests
- Jupyter Notebook

## Data Sources

The original Steam games dataset was obtained from Kaggle and is provided under the MIT License:

Steam Games Dataset: Daily Updates \
Dataset author: Hubert Sidorowicz \
Source: Kaggle

Additional game-level information was retrieved through the Gamalytic API. Gamalytic-derived data is used for analysis but is not included as a standalone or merged dataset in this repository.
