#What is this?
This is a repository with the code for the peer assesment required on the Coursera course Getting and Cleaning Data

#The data

The data used on this script can be found [here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
).

The data is on a folder called **UCI HAR Dataset**, we will only need the following files:

* activity_labels.txt
* features.txt
* subject_test.txt
* subject_train.txt
* X_test.txt
* X_train.txt
* y_test.txt
* y_train.txt

**Put all these files on your R working directory at the same level.**


#The code

This project has only one script **run_analysis.R**. This code turns all the files above on two tidy datasets, by doing the following:

1. Merges the training and the test sets to create one data set.
2. **Extracts only the measurements on the mean and standard deviation (dataset1.csv)** for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent **tidy data set with the average of each variable (dataset2.csv)** for each activity and each subject. 

Detailed information about generated datasets can be found on the CodeBook.

