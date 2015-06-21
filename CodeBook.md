# CodeBook

This is a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data
## The data sources

*  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
*  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## data files


- 'README.txt'

- 'train/y_train.txt': Training labels.
- 'features_info.txt': Shows information about the variables used on the feature vector.
- 'activity_labels.txt': Links the class labels with their activity name.
- 'features.txt': List of all features.
- 'test/y_test.txt': Test labels.
- 'train/X_train.txt': Training set.
- 'test/X_test.txt': Test set.

 files available for  train and test data.
 
- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration.
- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.
- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.
- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis.


## How run_analysis.R implements assignment:

* Require reshapre2 & data.table librareis.
* Load both test & train data
* Load  features & activity labels.
* Extract the mean & standard deviation column names and data.
* Process the data. 
* Merge data set.
