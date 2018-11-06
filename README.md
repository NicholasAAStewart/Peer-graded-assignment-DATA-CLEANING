# Peer-graded-assignment-DATA-CLEANING

The objective in this peer-graded assignment is to take disparate data components and to combine them into data frame(s) suitable for input and analysis by R.

The first task was to combine the X_train and X_test files into one file with column headings, labels for activities, and the data itself. The data is recorded by subject and activity level and I will call it frame 1.

For the final data frame which I produced, I used the dplyr (by Hadley Wickham) package to summarize (aggregate) the first data frame 1 to produce averages of all columns except the grouping variables. The result is referred to as frame 2.

Objectives:

(1) frames 1 and 2 must be "tidy data."
(2) R scripts are included in a script book.
(3) A codebook explains the data cleaning and meta data in a clear and concise manner.
