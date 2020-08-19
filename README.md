# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Downloads the dataset if it does not already exist in the working directory
2. Loads the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset
5. Merges the training and the test sets to create one data set.
6. Extracts only the measurements on the mean and standard deviation for each measurement.
7. Uses descriptive activity names to name the activities in the data set
8. Appropriately labels the data set with descriptive variable names.
9. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
