Introduction
The script run_analysis.R performs the 5 steps described in the course project's definition.
Below are the 5 steps performed for reference :
	Merges the training and the test sets to create one data set.
	Extracts only the measurements on the mean and standard deviation for each measurement.
	Uses descriptive activity names to name the activities in the data set
	Appropriately labels the data set with descriptive variable names.
	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Details

First, Merges the training and the test sets to create one data set. Similar data is merged using the rbind() function. By similar, we address those files having the same number of columns and referring to the same entities.

The next step is Setting Names to Variables and Building a data frame by merging all the data sets. Then it Extracts only the measurements on the mean and standard deviation for each measurement. 

Then uses the Uses descriptive activity names to name the activities in the data set.Appropriately next step is to labels the data set with descriptive variable names

From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.Finally My_Final_Tidy_Data.txt is produced.


Steps to reproduce this project

Open Rstudio to open R Markdown file run_analysis.Rmd to build the Project , then run_analysis.md , codebook.md and tidydata.txt will be produced.

Alterativley the R script run_analysis.r can be used to build the Project, but it only produces the final tidy dataset in tidydata.txt

