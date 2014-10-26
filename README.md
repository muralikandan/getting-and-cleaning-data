getting-and-cleaning-data
=========================

The cleanup script (run_analysis.R) does the following:
1. Reads content from activity and feature list
2. Extracts only the measurements labels from feature list
3. Loads and process test content
4. Finally prepares test content based on extracts from step2
5. step3 and step4 executed for train content
6. Merge test and train contents
7. Finally it creates a second, independent tidy data set with the average of each variable for each activity and each subject.
8. Generated tidy data set placed under working directory
