# Airbnb Data Engineering Assignment

## Project Overview

This project was completed as part of a Data Engineering Internship assessment.

The project uses the Airbnb London dataset to demonstrate data exploration, data cleaning, data engineering, SQL analysis,\ and exploratory data analysis (EDA). The objective was to transform raw Airbnb data into a clean, structured dataset and generate meaningful business insights.

## Selected City

**London**

## Project Objectives

This project includes:

- Data exploration and quality assessment
- Data cleaning and validation
- Feature engineering
- SQLite database creation and SQL querying
- Data engineering pipeline design
- Exploratory Data Analysis (EDA)
- Business insight generation


## Notebook Description

### Notebook 1 – Dataset Exploration

- Explored the dataset structure
- Checked data types
- Examined missing values
- Identified duplicate records
- Performed initial data quality assessment


### Notebook 2 – Data Cleaning and Engineering

This notebook includes:

### Data Cleaning

- Missing value handling
- Duplicate removal
- Data type conversion
- Date formatting
- Data validation
- Feature engineering

### Data Engineering

- SQLite database creation
- SQL business queries
- Configurable pipeline design
- Logging
- Error handling
- Incremental processing logic
- Metadata management
- Data lineage documentation

### Notebook 3 – EDA

The EDA explores:

- Price distributions
- Room types
- Property types
- Host behaviour
- Review patterns
- Availability
- Geographic analysis
- Temporal trends
- Business insights

Each visualization includes a business interpretation explaining its practical significance.


## Technologies Used

- Python
- Pandas
- NumPy
- SQLite
- Matplotlib
- Seaborn
- Plotly
- Missingno
- Google Colab


## Dataset

The original Airbnb datasets are **not included** in this repository because they exceed GitHub's file size limits.

To run the notebooks:

1. Download the original Airbnb datasets provided with the assignment.
2. Update the file paths in the notebooks.


## How to Run

1. Clone the repository.

```
git clone https://github.com/<your-username>/airbnb-data-engineering-assignment.git
```

2. Install the required libraries.

```
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter Notebook, JupyterLab, VS Code or Google Colab.

4. Run the notebooks in the following order:

```
01_data_exploration
02_data_cleaning_and_engineering
03_EDA
```

---

## Key Findings

Some important findings from the analysis include:

- Entire homes/apartments generally have the highest prices.
- Listing prices vary considerably across neighbourhoods.
- Most hosts manage only one listing, while a small proportion operate multiple listings.
- Review scores are consistently high, indicating possible rating inflation.
- Listings in premium locations tend to command higher prices.
- Availability varies across listings, reflecting different hosting strategies.


## Limitations

- The analysis is limited to the London dataset.
- Some findings are based on the available snapshot and may not represent long-term trends.

## Author

**Sayuni Fernando**

Submitted as part of the Data Engineering Internship Assignment.
