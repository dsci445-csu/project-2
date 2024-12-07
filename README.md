# project-2
Group 2 project for DSCI445 @ CSU

This Project will be working with the NFL's "Big Data Bowl - 2025". That data can be found here: https://www.kaggle.com/competitions/nfl-big-data-bowl-2025

A sign up may be required in order to pull the data.

Our project will primarily be focused on predicting play patterns for an Offense. A run or pass prediction will be made

These predicitions will be made using provided data from the NFL, including player substitution data, down and distance situations, field location, and other factors deemed significant through our analysis.

Steps to Reproduce the Rusults from our project:
- Go to the kaggle link above and download the data
- Extract the zip file into a folder called "data" in the repo. This folder named in the .gitignore file because these csv's are too large to commit
- Run the "NFL Data Cleaning.Rmd" file from top to bottom
- Run the "Reproduce Logistic Model (LASSO).Rmd" file from top to bottom
- NOTE: The following two steps produce large .rds files that will be provided as model runtimes exceeded 4 Hours total
- Run the [insert RF Model file name here] file from top to bottom
- Run the "Rreproduce SVM Model.Rmd" file from top to bottom
- NOTE: The above produces two tables as .html files. The .png versions of these were made with a screen grab and will be provided
These steps will reproduce our results and allow a kniting of the Final Paper.

