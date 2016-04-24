# Getting and Cleaning Data - Course Project

This is the Data science project work for the Getting and Cleaning Data from Coursera.
The R script, run_analysis.R, does the following:

1. Set the working directory
2. Load the packages data.table and reshape2
3. Load the activity and feature info
4. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
5. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
6. Merges the two datasets
7. Converts the activity and subject columns into factors
8. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The out put of this code is tidy.txt.
