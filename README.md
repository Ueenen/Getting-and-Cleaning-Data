# Getting-and-Cleaning-Data

1. Download the dataset from web.
2. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.
3. Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). Also, modify column names to descriptive.  
4. Extract data by selected columns, and merge x, y(activity) and subject data. Also, replace y(activity) column to it's name by refering activity label.
5. Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity. The result is shown in the file tidy_dataset.txt.
