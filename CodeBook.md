# Downloading the dataset
The dataset wa downloaded from the url:https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

#Data transformation
The dataset was transformed in the following steps;
1.Merging the training and the test sets to create one data set.
2.Extracting only the measurements on the mean and standard deviation for each measurement.
3.Using descriptive activity names to name the activities in the data set
4.Appropriately labeling the data set with descriptive variable names.
5.From the data set in step 4, creating a second, independent tidy data set with the average of each variable for each activity and each subject.

#R Script
The file "run_analysis.R" contains the R code with the outlined steps.
