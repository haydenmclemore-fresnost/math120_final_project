California Water Quality Analysis
MATH 120 – Final Project
Project Overview
This project explores California’s statewide Discrete Water Quality dataset from the Department of Water Resources (DWR). The dataset has over 4.6 million measurements collected from monitoring stations across the state. My goal is to clean and analyze a usable subset of this massive dataset and create summaries and visualizations that highlight how different water-quality parameters vary across regions, stations, and water-year types. All methods come from the tools we learned this semester: Pandas, groupby, filtering, merging, and Plotly visualizations.
Project Structure
math120_final_project/
├── data_raw/                 # Raw/unfiltered data (optional subsets)
├── data/                     # Cleaned or reduced datasets created in the notebook
├── src/                      # Helper functions and modules (optional expansion)
│   ├── __init__.py
│   ├── cleaning.py           # Data cleaning utilities
│   └── analysis.py           # Summary + plotting code
├── notebook.ipynb            # Main analysis notebook
└── README.md                 # This file
Requirements
Python 3.10+
pandas
numpy
matplotlib and/or plotly
jupyter or Google Colab
(If using Colab, no installation is needed.)
Installation and Setup
Local Execution
Clone the repo:
git clone https://github.com/your-username/math120_final_project.git
cd math120_final_project
Install packages:
pip install pandas numpy matplotlib plotly
Open the notebook:
jupyter notebook notebook.ipynb
Google Colab Execution
Open Google Colab
Go to File → Open Notebook → GitHub
Paste the link to this repo
Run the first setup cell
Dataset
California Department of Water Resources – Discrete Water Quality Data
Link: https://data.cnra.ca.gov/dataset/water-quality-data
Size: 4.6M+ rows
Variables include:
Station ID, location info
Date/Time
Parameter names (pH, turbidity, temp, dissolved oxygen, etc.)
Units, method codes
Water year type
Not all parameters are measured at all stations
Requires filtering and cleaning before analysis
Features of My Analysis
Load and explore a subset of the large dataset
Clean parameter values and handle missing data
Create groupby summaries for:
Region comparisons
Water year type differences
Parameter trends over time
Visualizations (Plotly + Matplotlib):
Line plots
Boxplots
Histograms
Scatterplots
Optionally, a small “dashboard-style” text summary of key stats
Key Learning Objectives Demonstrated
Handling very large datasets
Data cleaning and filtering with Pandas
Groupby summaries and aggregation
Creating exploratory visualizations
Writing reproducible code in a notebook
Organizing a project in a repo
Usage
Open notebook.ipynb and run all cells in order.
The notebook will:
Load and filter the dataset
Clean column types and missing values
Create summary tables
Build plots for the final report
Save processed subsets to the data/ folder
Author
Hayden McLemore
MATH 120 – Python / Mathematical Programming
Fresno State – Fall 2025
