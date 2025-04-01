# Strava-Data-Analysis
This repository contains a data analysis project exploring Professor Chris Brooks' Strava exercise data collected during the summer of 2019. The dataset includes metrics from various fitness devices, such as heart rate, cadence, power output, speed, and altitude, recorded during cycling and running activities.
README: Analysis of Dr. Chris Brooks' Strava Exercise Data
Overview
This project analyzes exercise data collected from Dr. Chris Brooks' Strava account during the summer of 2019. The dataset includes detailed metrics from various activities such as cycling and running, with variables like heart rate, cadence, power output, speed, and altitude. The analysis focuses on understanding patterns in the data, handling missing values, and visualizing key metrics to derive insights.

Project Structure
Notebook: Assignment 4 (1).ipynb contains the complete analysis, including data preparation, visualization, and insights.

Data: The dataset is stored in assets/strava.csv.

Output: The cleaned dataset is saved as cleaned_strava.csv.

Key Features
Data Preparation:

Loads and inspects the dataset.

Handles missing values by dropping columns with more than 50% missing data and imputing the median for numerical columns.

Saves the cleaned dataset for further analysis.

Visualizations:

Histogram of Heart Rate: Shows the distribution of heart rate data, highlighting peaks at 117, 137, and 157 BPM, which correspond to different exercise intensities.

Boxplot Comparison: Compares heart rate and cadence across different activities, providing insights into performance metrics.

Insights:

The heart rate distribution reveals three main intensity zones: warm-up/recovery (117 BPM), steady-state aerobic exercise (137 BPM), and high-intensity anaerobic effort (157 BPM).

The analysis adheres to Rule et al.'s guidelines for computational narratives, ensuring clarity and reproducibility.

How to Use
Prerequisites:

Python 3.x

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, plotly, scipy

Steps:

Clone the repository.

Open the Jupyter Notebook Assignment 4 (1).ipynb.

Run the cells sequentially to reproduce the analysis.

Dependencies
pandas

numpy

matplotlib

seaborn

plotly

scipy

Author
[Your Name]

License
This project is open-source and available under the MIT License.

Acknowledgments
Dr. Chris Brooks for sharing the Strava data.

Rule et al. for their guidelines on computational narratives.
