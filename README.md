# Datasciencecoursera_Specialisation

##Getting and Cleaning Data Project

The purpose of this project is to test one's ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

The data for the project can be downloaded from the link below: 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

To perform the task above, an R script called run_analysis.R is created by following the procedures below: 
* Merges the training and the test sets to create one data set. The zip files must be unzipped and tables are created by applying cols. Train and test data are merged by using id. 
* Te merged data set are processed by extracting the relevant variables, adding descriptive activity names, etc. "dataset1" is saved.
* Only  the mean and standard deviation for each measurement are extracted. 
* A second, independent tidy data set "dataset2" is created with the average of each variable for each activity and each subject.

