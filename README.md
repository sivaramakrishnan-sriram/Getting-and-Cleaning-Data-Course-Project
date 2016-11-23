##Getting and Cleaning Data
##Course Project

You should create one R script called run_analysis.R that does the following.

1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement.
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive activity names.
5.Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##Steps to work 
1. download the data from "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"\
2. save the "run_analysis.R" in the same folder where you have created the data from step1
3.run the program in R. and it will produce a file named "tidy_data.txt" in the same working directory.

##Libraries:
1.data.table
2.reshape2