# ENSANUT-Data-Analysis

## Exploring the Relationship Between Depression, High Blood Pressure, and Heart Conditions

This repository contains a Jupyter Notebook that explores the relationship between depression, high blood pressure, and heart conditions using data from the ENSANUT (Encuesta Nacional de Salud y Nutrición) polls in Mexico. The analysis includes statistical tests, correlation matrices, creation of a general "Score" for each condition, imputation for missing data, and visualizations of the results.

### Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Analysis](#analysis)

## Overview

This project aims to analyze the relationship between depression and high blood pressure and heart conditions using ENSANUT data. The analysis includes:

1. **Chi-Squared Test**: To examine the independence between categorical variables.
2. **Correlation Matrices**: To identify the strength and direction of relationships between variables.
3. **Score Creation**: To create a general "Score" for each condition based on relevant factors.
4. **Data Imputation**: To handle missing data in the dataset.
5. **Visualizations**: To present the results of the methodologies in an intuitive manner.

## Repository Structure

- `notebooks/`: Contains the Jupyter Notebook for the analysis.
- `data/`: Contains the ENSANUT data files (not included, see [Data](#data) section).
- `results/`: Directory where output and visualizations will be stored.
- `README.md`: This readme file.

## Prerequisites

To run this analysis, you will need:

- Python 3.x
- Jupyter Notebook
- The following Python libraries:
  - pandas
  - numpy
  - scipy
  - matplotlib
  - seaborn
  - scikit-learn

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/health-relationship-analysis.git
   cd health-relationship-analysis
   ```

2. Install the required Python libraries:
   ```bash
   pip install pandas numpy scipy matplotlib seaborn scikit-learn
   ```

## Usage

1. Navigate to the `notebooks/` directory:
   ```bash
   cd notebooks
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open the `analysis.ipynb` notebook and run the cells to perform the analysis.

## Data

The ENSANUT data files are required to run the analysis. These data files are not included in the repository due to their size and privacy considerations. You can obtain the data from the official ENSANUT website or other authorized sources.

1. Download the ENSANUT data files.
2. Place the data files in the `data/` directory.

## Analysis

The Jupyter Notebook performs the following steps:

1. **Data Loading**: Load the ENSANUT data into pandas DataFrames.
2. **Data Cleaning and Preprocessing**: Handle missing values, encode categorical variables, and preprocess the data for analysis.
3. **Chi-Squared Test**: Perform chi-squared tests to examine the independence between depression, high blood pressure, and heart conditions.
4. **Correlation Matrices**: Compute and visualize correlation matrices to identify relationships between variables.
5. **Score Creation**: Create a general "Score" for each condition based on relevant factors using a weighted sum or other appropriate methods.
6. **Data Imputation**: Use techniques like mean/mode imputation or more advanced methods to handle missing data.
7. **Visualizations**: Generate visualizations such as heatmaps, bar charts, and scatter plots to present the results.

---

Feel free to reach out if you have any questions or issues regarding the analysis. Happy coding!
