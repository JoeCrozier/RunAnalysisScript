---
title: "codebook"
author: "joe"
date: "Sunday, July 27, 2014"
output: html_document
---

Codebook for "final.txt", output of run_analysis.R

Activity
  Six different activities that could be performed by the test subjects
    Walking
    Walkingupstairs
    walkingdownstairs
    sitting
    standing
    laying
    
Subject
  Subjects, labelled # 1-30
  
These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.  Each of these variables are normalized [-1,1] and are actually the means of the original variables with the same names.  In other words, for subject 20, walking, under the "tBodyAccmean..X" variable, that is actually the mean of all of the "tBodyAccmean..X" observations for when subject 20 was walking.

The set of variables that were estimated from these signals are: 

mean(): Mean value
std(): Standard deviation

  tBodyAccmean..X 
  tBodyAccmean..Y
  tBodyAccmean..Z
  tBodyAccstd..X	
  tBodyAccstd..Y	
  tBodyAccstd..Z
  tGravityAccmean..X
  tGravityAccmean..Y
  tGravityAccmean..Z
  tGravityAccstd..X	
  tGravityAccstd..Y	
  tGravityAccstd..Z	
  tBodyAccJerkmean..X	
  tBodyAccJerkmean..Y	
  tBodyAccJerkmean..Z	
  tBodyAccJerkstd..X	
  tBodyAccJerkstd..Y	
  tBodyAccJerkstd..Z	
  tBodyGyromean..X	
  tBodyGyromean..Y	
  tBodyGyromean..Z	
  tBodyGyrostd..X	
  tBodyGyrostd..Y	
  tBodyGyrostd..Z	
  tBodyGyroJerkmean..X
  tBodyGyroJerkmean..Y	
  tBodyGyroJerkmean..Z	
  tBodyGyroJerkstd..X	
  tBodyGyroJerkstd..Y
  tBodyGyroJerkstd..Z	
  tBodyAccMagmean..	
  tBodyAccMagstd..	
  tGravityAccMagmean..
  tGravityAccMagstd..	
  tBodyAccJerkMagmean..
  tBodyAccJerkMagstd..
  tBodyGyroMagmean..	
  tBodyGyroMagstd..	
  tBodyGyroJerkMagmean..	
  tBodyGyroJerkMagstd..	
  fBodyAccmean..X	
  fBodyAccmean..Y	
  fBodyAccmean..Z	
  fBodyAccstd..X	
  fBodyAccstd..Y
  fBodyAccstd..Z
  fBodyAccmeanFreq..X	
  fBodyAccmeanFreq..Y	
  fBodyAccmeanFreq..Z	
  fBodyAccJerkmean..X	
  fBodyAccJerkmean..Y	
  fBodyAccJerkmean..Z	
  fBodyAccJerkstd..X	
  fBodyAccJerkstd..Y	
  fBodyAccJerkstd..Z	
  fBodyAccJerkmeanFreq..X
  fBodyAccJerkmeanFreq..Y
  fBodyAccJerkmeanFreq..Z	
  fBodyGyromean..X	
  fBodyGyromean..Y	
  fBodyGyromean..Z	
  fBodyGyrostd..X	
  fBodyGyrostd..Y	
  fBodyGyrostd..Z	
  fBodyGyromeanFreq..X	
  fBodyGyromeanFreq..Y	
  fBodyGyromeanFreq..Z
  fBodyAccMagmean..	
  fBodyAccMagstd..	
  fBodyAccMagmeanFreq..	
  fBodyBodyAccJerkMagmean..	
  fBodyBodyAccJerkMagstd..
  fBodyBodyAccJerkMagmeanFreq..	
  fBodyBodyGyroMagmean..	
  fBodyBodyGyroMagstd..	
  fBodyBodyGyroMagmeanFreq..	
  fBodyBodyGyroJerkMagmean..	
  fBodyBodyGyroJerkMagstd..	
  fBodyBodyGyroJerkMagmeanFreq..

