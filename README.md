## Getting and Cleaning Data Project
* Unzip the source
  ( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )
  into a folder on your local drive, say "/Users/yourName/Documents/datasciencecoursera/UCI HAR Dataset"

* Put run_analysis.R to the path:  "/Users/yourName/Documents/datasciencecoursera/UCI HAR Dataset"

* in RStudio: set current working dir to the path

  and then: source("run_analysis.R")

* The latter will run the R script, it will read the dataset and write these files:
  a. merged_clean_data.txt
  b. data_set_with_the_averages.txt

* Use data <- read.table("data_set_with_the_averages.txt") to read the latter.
  
