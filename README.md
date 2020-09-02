# Getting-and-Cleaning-Data---Course-Project

This is the course project for the Getting and Cleaning Data Coursera course.


# Assignment criteria:

1. A code book that modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information.

2. The submitted data set is tidy.

3. The Github repo contains the required scripts.

4. The README that explains the analysis files is clear and understandable.




# The included R script, run_analysis.R, conducts the following:

1. Download the dataset from web if it does not already exist in the working directory.

2. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.

3. Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). Also, modify column names to descriptive. (-mean to Mean, -std to Std, and remove symbols like -, (, ))

4. Extract data by selected columns(from step 3), and merge x, y(activity) and subject data. Also, replace y(activity) column to it's name by refering activity label (loaded step 3).

5. Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity. The result is shown in the file tidy_dataset.txt.


Other supplementary information: 

The data set of this project can be downloaded here:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

A full description can be found here:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
