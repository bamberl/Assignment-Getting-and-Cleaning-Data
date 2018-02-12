# Assignment-Getting-and-Cleaning-Data


Explanation of script
==================================================================

Introduction 
This project will take raw data from a scientific study and transform it into tidy data according to the course guidelines.

1.Merge the training and the test sets to create one data set.

1.1 Download raw experiment data from url

1.2 Unzip the raw data and list the files in the directory

1.3 Read the raw data into RStudio  

1.4 Summarise the raw data 
As can be seen from the summaries, TrainSubject and TestSubject data frames contain the person who performed the activities. There were 30 subjects, 21 in the training group and 9 in the test group.
Set contains a vector of 561 readings or calculations for each subject as they performed one of the six activities.There were 7352 observations in the training set and 2947 obervations in the test set.

1.5 Tidy the data frames by renaming the columns

1.6 Merge the training and the test data sets
By combining each of the 3 test files into a test dataframe and each of the 3 training files into a training data frame, then combine the test and training data frames

2.Extracts only the measurements on the mean and standard deviation for each measurement. 
Of the 561 measures has a description that includes "mean" or "std".We need to identify those columns and then extract only those columns.

3.Uses descriptive activity names to name the activities in the data set

4.Appropriately labels the data set with descriptive variable names. 
According to the course guidelines, names of variables should be:

4.1 All lower case were possible

4.2 Descriptive

4.3 Not have underscores or dots or white spaces

5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

