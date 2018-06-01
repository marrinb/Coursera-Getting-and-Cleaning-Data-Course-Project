# Coursera-Getting-and-Cleaning-Data-Course-Project

This is my submission for the Coursera Data Science Getting and Cleaning Data Course Project.

## Data Source
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. Link to the the data were provided in the project instructions and the data was collected from the accelerometers from the Samsung Galaxy S smartphone. The description of this data set can be found at [http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones]

The data used in this project was found at [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip]

## Analysis File 
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist in the working directory
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
5. Merges the two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.
