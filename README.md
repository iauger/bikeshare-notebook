# Bikeshare Trip Demand Prediction

## Project Overview

This project involves analyzing bikeshare data to predict trip demand and provide insights for operational decision-making. By leveraging data from various sources, including historical trip data and weather conditions, this analysis aims to optimize bikeshare fleet management and improve service availability for riders.

## Key Features

- **SQL Analysis:** Queries used to extract and aggregate bikeshare data for deeper insights.
- **Data Cleaning and Preparation:** Preprocessing steps to handle missing values, outliers, and feature engineering to enhance model performance.
- **Predictive Modeling:** Implementation of a Random Forest Regressor to forecast daily trip demand.
- **Operational Insights:** Strategies for dynamic rebalancing based on model predictions, including buffer recommendations to meet demand.

## Notebooks in the Repository

- **[Bikeshare Notebook.ipynb]([./Bikeshare%20Notebook.ipynb](https://github.com/iauger/bikeshare-notebook/blob/master/Portfolio%20Projects/Bikeshare%20Notebook.ipynb)):** The main analysis notebook containing the full data processing, modeling, and insights.

## Data Sources

- **Trip Data:** Historical bikeshare trip data, including timestamps, station information, and rider activity.
- **Weather Data:** Weather conditions corresponding to the dates of the trips, including temperature, precipitation, and wind speed.

## How to Run the Notebooks

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/iauger/bikeshare-notebook.git
    ```
2. Open the notebooks in Jupyter or VSCode and run the cells to reproduce the analysis.

## Results and Insights

The project achieved an R-squared value of 0.81 using a Random Forest Regressor, indicating strong predictive performance. The analysis provides actionable insights for bikeshare fleet management, including buffer recommendations to meet daily demand effectively.

## Future Work

- Explore additional features (e.g., time of day, special events) to improve model accuracy.
- Scale the analysis to include real-time data for dynamic fleet management.
- Integrate insights into a real-time decision support system for operational use.

## Author

- **Ian Auger** - Data Analyst with expertise in SQL, Python, and data visualization.
