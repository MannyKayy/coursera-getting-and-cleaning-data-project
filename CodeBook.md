Getting and Cleaning Data : CodeBook
====================================

This codebook describes the processes carried out on the "Human Activity Recognition Using Smartphones Dataset Version 1.0" through the 'run_analysis.R' script.


Project Objectives
------------------
You should create one R script called `run_analysis.R` that does the following: 
- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement. 
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names. 
- Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

Requirements
-----------
This script can be run step by step to reproduce the 'tidy' dataset. The primary requirement is that the working directory must be set by the user. Line 3 in the `run_analysis.R` file sets the working directory, every user must set a working directory (or comment this line out).

**NOTE :** The script assumes that the `plyr` library is installed.


The script
----------

In chronological order, the script `run_analysis.R`
- downloads the data from this
  [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)
- merges the training and test sets
- extracts the the mean and standard deviation for each measurement
- sets and uses descriptive activity names
- labels the columns with descriptive names
- creates a tidy data set. (`merged.clean`)
- creates a second, independent tidy dataset with an average of each measurement. (`merged.avg`)
- exports two versions of the the processed data set (a tidy data set and a tidy+averaged data set). These files are also both exported in the txt and csv file format (clean_dataset.txt, clean_dataset.csv, averaged_dataset.txt, averaged_dataset.csv).

The final dataset is output per the requirements set out for this course project.

The `run_analysis.R` file is appropriately commented and follows the logicial steps set out in the course project requirements.


More Information
----------------


Details on the layout and structure of the raw data can be found in the `Readme.txt` file within the downloaded UCI dataset folder.

