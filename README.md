# Smart Home Energy Consumption Prediction

### Predicting Household Appliance Energy Consumption Using Machine Learning

![Smart Home Energy Prediction Animation](figure/smart_home_energy_prediction_3d_animation.gif)

## Project Overview

This project explores smart home energy consumption using environmental sensor measurements, weather conditions, and time-related information.

The goal is to analyze household electricity usage patterns and develop machine learning models capable of predicting appliance energy consumption.

The project combines exploratory data analysis, feature engineering, and predictive modeling to better understand the factors influencing household energy demand.

## Project Objectives

- Explore household appliance energy consumption patterns.
- Analyze variations in energy usage across different hours and days.
- Investigate relationships between energy consumption, indoor environmental conditions, and outdoor weather variables.
- Develop and evaluate machine learning models for appliance energy prediction.
- Visualize findings and identify opportunities for improved energy management.

## Dataset

**Source:** [UCI Machine Learning Repository — Appliances Energy Prediction](https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction)

The dataset contains **19,735 observations and 29 columns**, including:

- Appliance energy consumption (Wh)
- Indoor temperature and humidity measurements
- Outdoor weather conditions
- Lighting energy consumption
- Date and time information

Measurements were recorded at **10-minute intervals** between January and May 2016.

The raw dataset is excluded from this GitHub repository and can be obtained from the original source.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Git and GitHub

## Current Progress

**Completed**
- Dataset loading and initial inspection
- Data quality and timestamp continuity checks
- Descriptive statistical analysis
- Appliance energy consumption distribution
- Daily energy consumption trends
- Hourly appliance energy consumption patterns

**Upcoming**
- Further exploratory analysis
- Feature engineering
- Machine learning model development
- Model evaluation and comparison

## Repository Structure

```text
Smart_Home_Energy_Consumption_Prediction/
├── notebook/
│   └── Smart_Home_Energy_Consumption_Prediction.ipynb
├── figure/
│   ├── appliance_energy_distribution.png
│   ├── daily_appliance_energy_trends.png
│   ├── hourly_appliance_energy_profile.png
│   └── smart_home_energy_prediction_3d_animation.gif
├── .gitignore
├── README.md
└── requirements.txt
```

## Getting Started

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

Download the dataset from the UCI Machine Learning Repository, place it in a local `data/` folder, and open the notebook in Jupyter.

## Project Status

**In Progress — Exploratory Data Analysis**

The README will be updated as feature engineering, predictive modeling, and model evaluation are completed.