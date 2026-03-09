# Story Feature Linear Regression Analysis. Assignment-2_Analyzing-Data1
## Introduction
This project analyzes whether specific storytelling features can predict the story_score of posts and comments from the ChangeMyView dataset. The analysis is performed using simple linear regression in Python.
The dataset used in this project contains storytelling features extracted from posts and comments on ChangeMyView. Each feature is scored on a scale from 1 to 5, while the story_score ranges from 0 to 1. It also includes six storytelling features: agency_score, event_score, world_score, curiosity_score, surprise_score, and suspense_score.

The goal of the analysis is to determine whether any of these features can predict the story score.

## Files in this Repository

Assignment 2-Analyzing Data1.ipynb – Jupyter notebook containing the analysis
data_full_story.csv – dataset used in the analysis
report.pdf – written discussion of the results

Open the notebook in Jupyter Notebook and run the cells from top to bottom. The notebook will load the dataset and perform the analysis automatically.

## Analysis Steps

To run the notebook, the dataset must be placed in the same folder as the notebook file.
The folder structure should look like this:
Assignment 2-Analyzing Data1.ipynb
data_full_story.csv

The notebook performs the following steps:

Load the dataset
Define dependent and independent variables
Generate scatterplots for visual inspection
Perform simple linear regression for each storytelling feature
Plot regression lines
Calculate the R² score for each model
Plot residuals
Perform the Shapiro-Wilk test on residuals
Compare results across the variables

## Results Summary

The analysis shows that none of the individual storytelling features strongly predict the story_score on their own. While some variables display slight positive relationships with the story score, the R² values remain relatively low, indicating weak predictive power.

This suggests that storytelling strength may be influenced by multiple narrative features combined, or by additional factors not captured in the dataset.

## Author
Christina Maliariti
University of Groningen –Digital Humanities Master's Program
