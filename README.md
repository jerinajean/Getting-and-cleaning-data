# Getting-and-cleaning-data
The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set.

The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected. 

One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

You should create one R script called run_analysis.R that does the following. 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average 
   of each variable for each activity and each subject.

##Tools used to produce this project
- This project is built by `knirt` package instllled on RStudio with RMD (R Markdown) format.

- The  `run_analysis.md` and `codebook.md` files will be  automatically  produced by `run_analysis.Rmd` 

## The following are the steps to produce this project

1, Please see the details in `run_analysis.md` and `codebook.md`.

2. Those files  contain the instructions and steps with R code embedded  to produce this project.

3. The final tidy data is in `tidydata.txt`. It can be loaded by `Data<-read.table("tidydata.txt", sep=" ", head=TRUE)`

4. The codebok is in `codebook.md` . It gives the descriptions of the variables in the data frame prouduced by this project.

## The following are the steps to reproduce this project

1. Open Rstudio to open R script `run_analysis.r` can be used  to build the Project, but it only produces the final tidy dataset in `tidydata.txt`

 
