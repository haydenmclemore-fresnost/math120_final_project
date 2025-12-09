# California Water Quality Analysis

This project analyzes California water quality data from the California Department of Water Resources (DWR).  
The purpose of this rough draft is to show a clear plan, working code, a reproducible repository, and meaningful progress toward the final project.

## Research Focus
The analysis focuses on three common water quality parameters:
- pH
- Dissolved Oxygen
- Electrical Conductance

Main questions include how these parameters vary across stations, how they change over time, how frequently stations are sampled, and whether any parameters are correlated.

## Data Source
Data is taken from the California Open Data Portal (DWR):
- Stations dataset (station metadata)
- Lab/Field Results dataset (individual water quality measurements)

The notebook loads the full dataset directly from the web using CSV URLs, so no manual downloads are required.

## Current Status
- Data loads successfully without Google Drive
- Cleaning and merging steps are complete
- Core analyses (averages, trends, sampling effort, correlations) are implemented
- Notebook runs end-to-end for peer review

## How to Run
Open `MATH120_Final_Project.ipynb` in Colab or Jupyter and run all cells.  
The data will download automatically.

