---
title: "readme"
author: "joe"
date: "Sunday, July 27, 2014"
output: html_document
---

The script labelled "run_analysis.R" in this repository is an R script designed to download a zipped data file from UCI's machine learning Repository.  The data is from accelerometers inside of Samsung Galaxy S smartphones, obtained when subjects were performing various activities like walking, standing, laying, walking upstairs, downstairs, etc..  It will then unzip the data, open several different data files contained within, combine them and drop extraneous variables.  It is also designed to add variable names, and export a tidy data set that is much smaller in dimension than the original data.  

The script will first check whether or not you have a folder in your working directory titled "~/Coursera/GettingData".  It will then create that folder, and unzip all the machine learning data into it.

It then sets to work loading six different files and combining them into one data set.  These six files are from two sets of data.  There is x, y, and subject data from a "test" dataset, and there is x,y, and subject data from a "train" dataset.  The Y data explains what activity the subjects were doing, the subject data labels which subject it was, and the X data is accelerometer data for various activities.  The x data is complex, consisting of over 500 different variables which are initially unlabeled. 

The R script will then load a dataset entitled "Features" which has the names of the 500+ variables in it, it will then set those as the names of the appropriate columns for the overall dataset the script builds.

To simplify the dataset, we'll focus on just those variables pertaining to means and standard deviations.  Using Grepl, we'll drop any column that doesn't contain the words "Subject, std, mean, or Activity"

We'd then like to look at only the mean values of each activity, for each person.  The script uses the command "aggregate" to get the data set up where every row stands for one person doing one activity (with no other rows for that person doing that activity).  
Finally, the script creates an output file entitled "Final.txt" (that should be found within a folder in your working directory '~/Coursera/GettingData/UCI HAR Dataset' that should be a smaller, tidy dataset.