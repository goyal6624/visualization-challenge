# Pymaceuticals Data Visualization Challenge

This repository hosts a Jupyter Notebook file named `pymaceuticals.ipynb`, where I conducted data visualizations on a mice study analyzing the effects of various drugs on tumor size.

## Methodology
1. I had to clean, sort, and summarize the data into a dataframe with `pandas`.
2. I plotted box plots, line graphs, and bar graphs with `DataFrame.plot()` and `matplotlib.pyplot`.
3. I conducted linear regression and a line of best fit with `scipy`.
4. I wrote my own analysis on the data set by looking at the visualizations and summary dataframe I had created.

## Dataset 

The analysis was performed using two datasets:

1. `Mouse_metadata.csv`: This CSV file contains information on the mice present in the study. It includes their ID, drug regimen, sex, age (months), and weight (grams).

2. `Study_results.csv`: This CSV file includes data on the results of the study, including the timepoint, tumor volume, mouse ID, and metastatic sites.

Both datasets can be found in the `data` folder.

## Jupyter Notebook

The main analysis was conducted in the Jupyter Notebook file `pymaceuticals.ipynb`. In this notebook, I utilized Python, along with the `pandas`, `matplotlib`, and `scipy` libraries, to perform data manipulation, visualizations, analysis, and calculations.

The notebook contains step-by-step code blocks explaining how I performed the analysis, visualizations, summarization, and the corresponding observations and insights.