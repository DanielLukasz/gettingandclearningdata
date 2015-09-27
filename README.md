# gettingandclearningdata
Coursera
This file describes how run_analysis.R script works.

GOAL

The aim of the project is to clean and extract usable data from the above zip file. R script called run_analysis.R that does the following:

    1. Merges the training and the test sets to create one data set.
    2. Extracts only the measurements on the mean and standard deviation for each measurement.
    3. Uses descriptive activity names to name the activities in the data set
    4. Appropriately labels the data set with descriptive variable names.
    5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

PREAPARING THE WORKS

1. The R code in run_analysis.R proceeds under the assumption that the zip file available at 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
is downloaded and extracted in the R Home Directory.
2. Libraries Used: 
- library(data.table)
- library(dplyr)

HOW IT WORKS?

  1. Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
    Run_analysis.R script in the current working directory.
  2. Use source("run_analysis.R") command in RStudio.
  3. You will find two output files are generated in the current working directory:
    #   merged_data.txt
    #    data_with_means.txt
4.  Finally, use data <- read.table("data_with_means.txt") command in RStudio to read the file. 
 
