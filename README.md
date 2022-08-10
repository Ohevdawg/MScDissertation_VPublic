# Dissertation## MSc Economics (Econometrics) Dissertation: Code/Data Submission

## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies)
* [Description of Subfolders](#description-of-subfolders)
* [Setup](#setup)
* [Sources](#sources)
* [Student Information](#student-information)

## General Information
Description: Code, data, logs, and output for the Dissertation of Student Exam Number B149547 in fulfillment of the requirements for the degree of MSc Economics (Econometrics). 

Motivation: This folder contains all of the components of the coded portion of the Dissertation of Student Exam Number B149547.  These components will act as a part of the Dissertation in fulfillment of the requirements for the degree of MSc Economics (Econometrics). 

## Technologies
The coded portion of this dissertation was created with:

* SPSS version 28.0.1.1: used to navigate and clean the initial large Matched CSS Data Set, which is given in .dta form by HERI.

* Stata version 16.1

  * External Stata packeges used: diff, asdoc (available via ssc install command)

* LaTeX version 2e

* Github Desktop: used as a PRIVATE AND CONFIDENTIAL code repository and to facilitate in the creation of this README file.

  * NOTE: While this README file will be made public, any data uploaded to Github is private to the student and those who will grade this dissertation, and will not be shared with the public.

* R version 4.2.0 & RStudio version 2022.02.3+492
  
  * NOTE:  These technologies are only used to initially create the README.md and README.html files.  Since this README.html was included in the submission folder, these technologies are not required.

## Description of Subfolders
The components of this Dissertation are organized into the following subfolders:

* Data: This subfolder contains all of the data used throughout the data task.

  * raw: This subsub folder includes all data sets that were provided by the HERI Data Archives.
  
  * temp: This subsub folder includes all data sets created by the applicant.
  
* dofile: This subfolder contains all of the .do files that were written by the student in order to perform the analysis required for this dissertation.

  * NOTE: For descriptions of each .do file's purpose, please see the .do file, which includes a description of its purpose in this dissertation.
  
* logs: This subfolder contains any logs created by the student (none).

* output: This subfolder contains all output created by the student.

## Setup
To set up this project, define a local working directory and run the following code (also available in the .do file 0.1_Setup):
```
global file C:[YOUR WORKING FILE GOES HERE]
global dofile $file/dofiles
global temp $file/Data/temp
global logs $file/log
global output $file/output
```

## Sources
Raw data required to complete this Research & Evaluation Performance Task were provided by the Higher Education Research Institute & Cooperative INstitutional Research Program at the University of California, Los Angeles ([https://heri.ucla.edu/heri-data-archive/]).


## Student Information
This Dissertation and its output are the original work of:

Student Exam Number B149547

Under the supervision of:

Dr. Colm Harmon,

Vice Principal of Students & Professor of Applied Economics

University of Edinburgh
