# Time Series Anomaly Detection and Root Cause Analysis

## Overview
This repository contains Python code for performing time series anomaly detection and root cause analysis. The code is designed to read multivariate time series data from CSV files and their corresponding anomaly labels, visualize the time series plots with annotated anomaly regions, perform exploratory data analysis (EDA), and identify the variables that are the root cause for the anomalies.

## Files
- `test.csv`: Contains the multivariate time series data.
- `test_labels.csv`: Contains the timestamps of anomaly regions corresponding to the time series data.
- `smap_test.csv`, `msl_test.csv`, `psm_test.csv`: Additional test CSV files with similar data and labels.
- `smap_test_labels.csv`, `msl_test_labels.csv`, `psm_test_labels.csv`: Corresponding label files for the additional test CSVs.
- `time_series_anomaly_analysis.py`: Python script containing code for reading data, visualizing time series plots, performing EDA, and identifying root causes of anomalies.

## Tasks
The Python script (`time_series_anomaly_analysis.py`) performs the following tasks:
1. Reads the test and label files.
2. Draws time series plots with annotated anomaly regions.
3. Conducts exploratory data analysis to understand the characteristics of the data.
4. Identifies the variables that are the root cause for the anomalies.

## Dependencies
- Python 3.x
- Required Python libraries (e.g., Pandas, Matplotlib)

## Usage
1. Ensure that Python and the required libraries are installed.
2. Place the CSV files (`test.csv`, `test_labels.csv`, etc.) in the same directory as the Python script.
3. Run the Python script `time_series_anomaly_analysis.py`.
4. Follow the prompts or instructions provided within the script to execute specific tasks.

## Acknowledgements
This code is developed as part of an assignment/project and may include references to external resources or methodologies.

## Disclaimer
This code is provided as-is, without warranty or support. Use at your own risk.

---

Feel free to customize this README file according to your specific requirements and additional information you may want to include!
