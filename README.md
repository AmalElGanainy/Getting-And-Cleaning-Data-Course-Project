**Getting-And-Cleaning-Data-Course-Project**

In this project, data collected from the accelerometer and gyroscope of the Samsung Galaxy S smartphone was retrieved, worked with, and cleaned, to prepare a tidy data that can be used for later analysis.

This repository contains the following files:

1.README.md, this file, which provides an overview of the data set and how it was created.

2.tidy_data.txt, which contains the data set.

3.CodeBook.md, the code book, which describes the contents of the data set (data, variables and transformations used to generate the data).

4.run_analysis.R, the R script that was used to create the data set (see the Creating the data set section below)

**Cleaning The Data Set**

The R script run_analysis.R can be used to create the data set. It retrieves the source data set and transforms it to produce the final data set by implementing the following steps (see the Code book for details, as well as the comments in the script itself):

**Download and Getting the data into R.**

1.Read data.

2.Merge the training and the test sets to create one data set.

3.Extract only the measurements on the mean and standard deviation for each measurement.

4.Use descriptive activity names to name the activities in the data set.

5.Appropriately label the data set with descriptive variable names.

6.Create a second, independent tidy set with the average of each variable for each activity and each subject.

7.Write the data set to the tidy_data.txt file.

8.The tidy_data.txt in this repository was created by running the run_analysis.R script using R version 3.4.3 (2018-05-21) on Windows 
10 - 64-bit edition.


This script requires the dplyr package.
