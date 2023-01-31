# Matplotlib-challenge
This is an assignment that I completed for the George Washington University Data Analytics Bootcamp, focused on analysis and visualization in Python using Jupyter Notebook and displaying my understanding of Pandas & Matplotlib.


## Organization
Within "Matplotlib-challenge" you will find this "README.md" file which provides an explanation of my analysis. You will also 
find the folder, "PyMaceuticals" which contains my Python code in a Jupyter Notebook file, as well as a "Data" folder. The "Data"
folder contains two documents "Mouse_metadata.csv" and "Study_results.csv" which are used in this analysis.

## Background

For this assignment, I will be analyzing data which relates to a pharmaceutical company testing a variety of drug regimens
on lab mice. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

This project is broken down into the following parts:

Prepare the data.

Generate summary statistics.

Create bar charts and pie charts.

Calculate quartiles, find outliers, and create a box plot.

Create a line plot and a scatter plot.

Calculate correlation and regression.

Submit final analysis.


## Insights

This dataset included more timepoints for mice with the Capomulin and Ramicane regimens.

Capomulin and Ramicane both showed notably smaller final tumor volumes compared to Infubinol and Ceftamin.

Mouse weight was correlated with average tumor volume with a correlation coefficient of .84.

Capomulin seems to have become effective at decreasing tumor volume after about 19 days of administration, at which point
tumor size stopped increasing and began to decrease dramatically until it measured about 41mm3. After this point, it did increase
again until the conclusion of the measurement period.

We would recommend conducting another longer-duration trial of Capomulin in order to better understand its long-term effects
on tumor volume, before proceeding to higher order animal testing.

