As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. 
In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 
45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' 
drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all 
of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary 
of the study results.

## Instructions 

The following tasks are carried out:

* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with 
that mouse ID.

* Use the cleaned data for the remaining steps.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume 
for each drug regimen.

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of timepoints 
for all mice tested for each drug regimen throughout the course of the study.

    **NOTE:** These plots should look identical.

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or 
male mice in the study. 
