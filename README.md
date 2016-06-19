# coursera-getting-and-cleaning-data

This file describes how run_analysis.R script works.

First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".

Make sure the folder "data" and the run_analysis.R script are both in the current working directory.

Second, use source("run_analysis.R") command in RStudio.

Third, you will find two output files are generated in the current working directory:

merged_data.txt (7.9 Mb): it contains a data frame. Merges the training and the test sets to create one data set.

data_with_means.txt (220 Kb): it contains a data frame. Extracts only the measurements on the mean and standard deviation for each measurement.

Uses descriptive activity names to name the activities in the data set

Appropriately labels the data set with descriptive activity names.

Creates a second, independent tidy data set with the average of each variable for each activity and each subject using data <- read.table("data_with_means.txt") command in RStudio.
