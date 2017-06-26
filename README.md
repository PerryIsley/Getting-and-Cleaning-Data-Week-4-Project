# Getting-and-Cleaning-Data-Week-4-Project
Course Project for Getting and Cleaning Data Course 
For this project, the R script, run_analysis.R, does the following:

Dataset is downloaded if it does not already exist in the working directory
Loads activity & feature info
Keeping only columns which show a mean or standard deviation, loads the Training and Test datasets
Merges the columns with the dataset: Activity and SUbjecct Data for each sheet
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset with the average value of each variable for each subject and activity pair.
Final result is shown in the file tidy.txt.
