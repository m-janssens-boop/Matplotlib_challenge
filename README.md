# Matplotlib_challenge

Background
--------
A pharmaceual company, Pymaceuticals, has begun screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

This company has completed its most recent animal study and needs to visualize the results. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

This repository is teh tables, figures, and visualizations as well as the analysis of them for technical report of the clinical study.

## Objective ##

Prepare the data:
* Merge the mouse_metadata and study_results DataFrames into a single DataFrame
* Remove any duplicate data

Generate a summary statistics dataframe:
* Indeces for each drug regimen
* A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume

Create bar charts and pie charts:
* A bar chart that shows total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study
* A pie chart that shows  the distribution of female versus male mice in the study

Calculate quartiles, find outliers, and create a box plot:
* A box plot that shows the distribution of the final tumor volume for all the mice in each treatment group. Highlighting any potential outliers in the plot by changing their color and style.

Create a line plot and a scatter plot:
* Generate a line plot of tumor volume versus time point for a single mouse that was treated with Capomulin
* Generate a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen

Calculate correlation and regression:
* Calculate the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen
* Plot the linear regression model on top of the previous scatter plot

A final analyses of the data can be found in the jupyter notebook.

