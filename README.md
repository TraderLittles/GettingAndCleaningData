## Getting and Cleaning Data - Course Project ReadMe
### This file describes the basic process of running the run_analysis.r script 
 
 *Run_analysis.r is summarized below:	
	1. X test and training data was extracted and binded together and stored in X_data
	2. Y test and training data was extracted and binded together and stored in Y_data
	3. Subject data was extracted and binded together and stored in Subject_data
	4. Features and activity data was extracted and binded together and stored in features and activityNames
	5. Specific columns containing std or mean were extracted from the X data
	6. The X data was then adjusted to exclude all columns that were not extracted in the previous step
	7. Headers were then renamed and formatted to be more readable ('-' was converted to '_', 'freq' was converted to frequency, etc.)
	8. Then the activity labels were extracted and applied to the Y data set
	9. The subject, x and y data sets were then combined into one data set called df
	10. The data frame df was then simultaneously aggregated by subject and activity and averaged to create final data set called Tidy_DataSet
	11. Tidy_DataSet was then ordered and written as a table to a txt file named 'TidyDataSet.txt'