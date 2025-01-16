# Pymaceuticals

Pymaceuticals, Inc.

Overview

Pymaceuticals, Inc. is a pharmaceutical company focused on anti-cancer medications. This project analyzes data from a recent animal study where 249 mice with squamous cell carcinoma (SCC) tumors were treated with various drug regimens. The study's objective was to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

Purpose

As a senior data analyst, the goal of this analysis is to generate the tables, figures, and insights necessary for a technical report. Additionally, a summary of the study results will be provided to assist the executive team in evaluating the drug regimens.

Files and Structure

Mouse_metadata.csv: Contains information about the mice used in the study.

Study_results.csv: Contains results from the tumor measurement study.

Jupyter Notebook: A notebook for data preparation, analysis, and visualization.

Analysis Workflow

1. Data Preparation

Merge the Mouse_metadata and Study_results datasets into a single DataFrame.

Identify and remove duplicate data entries.

Verify the number of unique mice in the cleaned dataset.

2. Summary Statistics

Compute summary statistics (mean, median, variance, standard deviation, SEM) for tumor volume across each drug regimen.

Present the results in a structured DataFrame.

3. Data Visualizations

Bar Charts

Display the total number of timepoints for each drug regimen using Pandas and Matplotlib.

Pie Charts

Visualize the gender distribution of the mice using Pandas and Matplotlib.

Box Plots

Analyze the final tumor volume distribution for four key treatments: Capomulin, Ramicane, Infubinol, and Ceftamin.

Highlight potential outliers.

Line Plot

Show tumor volume changes over time for a single mouse treated with Capomulin.

Scatter Plot

Plot the relationship between mouse weight and average tumor volume for mice treated with Capomulin.

4. Correlation and Regression

Calculate the correlation coefficient and perform linear regression between mouse weight and average tumor volume for the Capomulin regimen.

Overlay the regression line on the scatter plot.

Key Findings

Drug Efficacy: Capomulin and Ramicane demonstrated the most significant tumor volume reductions.

Mouse Weight vs. Tumor Volume: A positive correlation was observed, indicating that heavier mice tended to have higher tumor volumes.

Data Integrity: Duplicate entries were removed, and outliers were identified and highlighted in the box plots.

Tools and Libraries

Python Libraries: Pandas, Matplotlib, Scipy

Environment: Jupyter Notebook

Instructions

Clone this repository to your local machine.

Place the Mouse_metadata.csv and Study_results.csv files in the data folder.

Open the Jupyter Notebook to execute the analysis step by step.

Future Work

Investigate other potential predictors of tumor volume reduction.

Perform advanced statistical analyses to refine drug efficacy insights.

Expand the dataset to include additional drug regimens and species.