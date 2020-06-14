`{r setup, include=FALSE} knitr::opts_chunk$set(echo = FALSE)`

### **DESCRIPTION**

The following files from the initial dataset is used:

- **features.txt** includes the descriptions for features measured.
\
\
- **X_train.txt** includes the measurements of the features in train set (one row - 1 measurement of 561 features).
\
\
- **X_test.txt** includes the measurements of the features in test set.
\
\
- **subject_train.txt** - subject for each measurement from the train set. 
\
\
- **subject_test.txt** subject for each measurement from the test.
\
\
- **y_train.txt** activity (from 1 to 6) for each measurement from the train set.
\
\
- **y_test.txt** activity (from 1 to 6) for each measurement from the test set.


### **HOW SCRIPT WORKS**

-Merges the training and the test sets to create one data set.
\
\
-Extracts only the measurements on the mean and standard deviation for each measurement.
\
\
-Uses descriptive activity names to name the activities in the data set.
\
\
-Appropriately labels the data set with descriptive variable names.
\
\
-From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.