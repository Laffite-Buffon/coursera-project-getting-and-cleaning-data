# Coursera project Getting-and-Cleaning-Data
This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R make the necessary to get a properly dataset.


    Load reshape2 packages (this package must be previously installed)
    Download dataset in the working directory (if it does not exist)
    Load the activity and feature info
    Loads training and test datasets. Only the columns which reflect a mean or standard deviation will be selected
    Loads the activity and subject data for each dataset.
    Merges activity and subject data with the main dataset
    Merges the two main datasets
    Make into factors both activity and subject columns 
    Creates the tidy dataset. In this file is recorded the average (mean) value of each variable for each subject and activity pair.


The end result is shown in the file Tidy_Dataset.txt.
