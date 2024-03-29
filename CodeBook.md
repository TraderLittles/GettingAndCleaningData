## Getting and Cleaning Data - Course Project Codebook 
#### This file describes the variables, the data, and relevant transformations that was performed to clean up the data
* This code book summarizes the resulting data fields in TidyDataSet.txt. 

#### Identifiers (these were added as headers replacing the generic column names of V1..Vn)
* SubjectId - The # of the test subject of the data collection process
* ActivityName - The type of activity performed by the test subject when corresponding measurements were taken

#### Measurements (these were tranformed with the gsub function to be more readable)
* SubjectId
* ActivityName
* timeBodyAccelerometer_mean_X
* timeBodyAccelerometer_mean_Y
* timeBodyAccelerometer_mean_Z
* timeBodyAccelerometer_std_X
* timeBodyAccelerometer_std_Y
* timeBodyAccelerometer_std_Z
* timeGravityAccelerometer_mean_X
* timeGravityAccelerometer_mean_Y
* timeGravityAccelerometer_mean_Z
* timeGravityAccelerometer_std_X
* timeGravityAccelerometer_std_Y
* timeGravityAccelerometer_std_Z
* timeBodyAccelerometerJerk_mean_X
* timeBodyAccelerometerJerk_mean_Y
* timeBodyAccelerometerJerk_mean_Z
* timeBodyAccelerometerJerk_std_X
* timeBodyAccelerometerJerk_std_Y
* timeBodyAccelerometerJerk_std_Z
* timeBodyGyroscope_mean_X
* timeBodyGyroscope_mean_Y
* timeBodyGyroscope_mean_Z
* timeBodyGyroscope_std_X
* timeBodyGyroscope_std_Y
* timeBodyGyroscope_std_Z
* timeBodyGyroscopeJerk_mean_X
* timeBodyGyroscopeJerk_mean_Y
* timeBodyGyroscopeJerk_mean_Z
* timeBodyGyroscopeJerk_std_X
* timeBodyGyroscopeJerk_std_Y
* timeBodyGyroscopeJerk_std_Z
* timeBodyAccelerometerMagnitude_mean
* timeBodyAccelerometerMagnitude_std
* timeGravityAccelerometerMagnitude_mean
* timeGravityAccelerometerMagnitude_std
* timeBodyAccelerometerJerkMagnitude_mean
* timeBodyAccelerometerJerkMagnitude_std
* timeBodyGyroscopeMagnitude_mean
* timeBodyGyroscopeMagnitude_std
* timeBodyGyroscopeJerkMagnitude_mean
* timeBodyGyroscopeJerkMagnitude_std
* frequencyBodyAccelerometer_mean_X
* frequencyBodyAccelerometer_mean_Y
* frequencyBodyAccelerometer_mean_Z
* frequencyBodyAccelerometer_std_X
* frequencyBodyAccelerometer_std_Y
* frequencyBodyAccelerometer_std_Z
* frequencyBodyAccelerometer_meanFreq_X
* frequencyBodyAccelerometer_meanFreq_Y
* frequencyBodyAccelerometer_meanFreq_Z
* frequencyBodyAccelerometerJerk_mean_X
* frequencyBodyAccelerometerJerk_mean_Y
* frequencyBodyAccelerometerJerk_mean_Z
* frequencyBodyAccelerometerJerk_std_X
* frequencyBodyAccelerometerJerk_std_Y
* frequencyBodyAccelerometerJerk_std_Z
* frequencyBodyAccelerometerJerk_meanFreq_X
* frequencyBodyAccelerometerJerk_meanFreq_Y
* frequencyBodyAccelerometerJerk_meanFreq_Z
* frequencyBodyGyroscope_mean_X
* frequencyBodyGyroscope_mean_Y
* frequencyBodyGyroscope_mean_Z
* frequencyBodyGyroscope_std_X
* frequencyBodyGyroscope_std_Y
* frequencyBodyGyroscope_std_Z
* frequencyBodyGyroscope_meanFreq_X
* frequencyBodyGyroscope_meanFreq_Y
* frequencyBodyGyroscope_meanFreq_Z
* frequencyBodyAccelerometerMagnitude_mean
* frequencyBodyAccelerometerMagnitude_std
* frequencyBodyAccelerometerMagnitude_meanFreq
* frequencyBodyAccelerometerJerkMagnitude_mean
* frequencyBodyAccelerometerJerkMagnitude_std
* frequencyBodyAccelerometerJerkMagnitude_meanFreq
* frequencyBodyGyroscopeMagnitude_mean
* frequencyBodyGyroscopeMagnitude_std
* frequencyBodyGyroscopeMagnitude_meanFreq
* frequencyBodyGyroscopeJerkMagnitude_mean
* frequencyBodyGyroscopeJerkMagnitude_std
* frequencyBodyGyroscopeJerkMagnitude_meanFreq


### Activity Names / Labels
* WALKING (value 1): subject was walking during the measurement
* WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the measurement
* WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the measurement
* SITTING (value 4): subject was sitting during the measurement
* STANDING (value 5): subject was standing during the measurement
* LAYING (value 6): subject was laying down during the measurement