Getting-and-Cleaning-Data-Course-Project

Course Project You should create one R script called run_analysis.R that does the following.

1.Merges the training and the test sets to create one data set. 
2.Extracts only the measurements on the mean and standard deviation for each measurement. 
3.Uses descriptive activity names to name the activities in the data setAppropriately labels the data set with descriptive variable names. 
4.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Project purpose 

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

Steps to work 

Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
