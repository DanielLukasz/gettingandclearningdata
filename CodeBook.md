Description of  the variables, the data, and transformations used to clean up the data.

    The data comes from:
    source: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
   In this project I used such data:
    source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
    Analyse was done with following seps:
    Step 1. :
    Read X_train.txt, y_train.txt and subject_train.txt from the "./data/train" folder and store them in trainData, trainLabel and trainSubject variables respectively.
    Step 2.:
    Read X_test.txt, y_test.txt and subject_test.txt from the "./data/test" folder and store them in testData, testLabel and testsubject variables respectively.
    Step 3.: 
    Tide testData to trainData  joinData; tide testLabel to trainLabel , joinLabel; tide testSubject to trainSubject , joinSubject.
    Step 4.: 
    Read the features.txt file from the "/data" folder and store the data in a variable called features. 
    Step 5:
    Clean the column names of the subset. (remove the "()" and "-" symbols in the names, as well as make the first letter
    Step 6:
    Read the activity_labels.txt file from the "./data"" folder and store the data in a variable called activity. of "mean" and "std" a capital letter "M" and "S" respectively.
    Step 7:
    Clean the activity names in the second column of activity. We first make all names to lower cases. 
    Step 8:
    Transform the values of joinLabel according to the activity data frame.
    Step 9: 
    Combine the joinSubject, joinLabel and joinData by column to get a new cleaned data frame, cleanedData. 
    Step 10:
    Write the cleanedData out to "merged_data.txt" file in current working directory.
    Step 11
    Generate a second independent tidy data set with the average of each measurement for each activity and each subject. 
    Step 12
    Write the result out to "data_with_means.txt" file in current working directory.
