
This is the code book for the Coursera Data Science Getting and Cleaning Data course assignment to describe the variables and data and required steps to clean the data. 

## The data
This dataset included the following files needed for the course project:

1: README.txt
2: features_info.txt
3: features.txt
4: activity_labels.txt
5: train/X_train.txt
6: train/y_train.txt
7: test/X_test.txt
8: test/y_test.txt

The following files were for the train and test data:

1: train/subject_train.txt
2: train/Inertial Signals/total_acc_x_train.txt
3: train/Inertial Signals/body_acc_x_train.txt
4: train/Inertial Signals/body_gyro_x_train.txt

## Transformation 

1: Merge training data set with test data set to create a single comprehensive data set.
2: Extract mean and standard deviation of each measurement.
3: Namea the activities in the data set using descriptive activity names and appropriately labels them as such.
4: Create a second, independent tidy data set showing the average of each variable for each activity and each subject.

## Using ```run_analysis.R``` to implement steps:

1. Require ```reshapre2``` and ```data.table```.
2. Load both test and train data
3. Load the features and activity labels.
4. Extract the mean and standard deviation column names and data.
5: Process the data. There are two parts processing test and train data respectively.
6: Merge data set.
