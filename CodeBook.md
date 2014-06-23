Getting and Cleaning Data : CodeBook
====================================

This codebook describes the processes carried out to on the "Human Activity Recognition Using Smartphones Dataset Version 1.0" through the 'run_analysis.R' script.


Project Objectives
------------------
You should create one R script called `run_analysis.R` that does the following: 
-Merges the training and the test sets to create one data set.
-Extracts only the measurements on the mean and standard deviation for each measurement. 
-Uses descriptive activity names to name the activities in the data set
-Appropriately labels the data set with descriptive variable names. 
-Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 


The script
----------

The script `run_analysis.R`
- downloads the data from this
  [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
- merges the training and test sets
- uses descriptive activity names
- extracts the the mean and standard deviation for each measurement
- labels the columns with descriptive names
- creates a second, independent tidy dataset with an average of each measurement
- exports two versions of the the processed data set (a tidy data set and a tidy+averaged data set). These files are also both exported in the txt and csv file format.

The final dataset is output per the requirements set out for this course project.

The `run_analysis.R` file is appropriately commented and follows the logicial steps set out in the course project requirements.


More Information
----------------

Details on the layout of the raw data can be found in the "Readme" markdown file within the UCI dataset folder.