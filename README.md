# 720_regex_mmp
 
## Group Members
Mara Alexeev
Parker Bannister
Mitchell Flagg

## Assignment Details

Briefing

It is still early in the pandemic. You have deployed your symptoms screening tool to help screen for patients for COVID-19, but testing is still scarce. You have been asked to help do syndromic surveillance based on chief complaint data, gathered from either your app or the EHR, to help determine the current burden of COVID-19 and help forecast clinical need for resources. Your task is two-fold, 1) identify which patients likely have covid based on their chief complaint, 2) predict how many patients have covid. A synthetic dataset was generated from real EHR data on covid patients. This synthetic dataset has the same distribution of chief complaints of patients tested for covid and is as close to real-world data as possible without an IRB.

Learning Objectives
Examine the standard use of regular expressions in Python (or R, JMP, Stata, etc. or whatever language/software of choice)*.
Discuss the pros and cons of using regular expressions for working with and manipulating strings to cohort patients

Assignment
Use the provided .csv file (on Piazza under Labs in the Resource Tab) to explore the synthetic dataset (derived from real EHR data) of “Chief Complaints” & build a RegEx ‘parser’ to screen patients for whether they have COVID-19 or not.
Columns are separated by a pipe delimiter “|”
Patients with multiple chief complaints will have those complaints separated with a comma delimiter.
Header for the file is “patientID|chief complaints”
Deliverables:
Model output 
Output column with either of the following: 
0   (for unlikely COVID-19)
1   (for likely COVID-19)
Note: Must preserve the original structure of the provided .csv file (in order for us to easily compare rows/IDs to ground truth).
Total count of patients with COVID-19

Teams’ approaches will be compared against each other for accuracy (compared to “ground truth”). No pressure :)

Reading material
Choose one (or find your own if using different software*):
(Python) https://www.w3schools.com/python/python_regex.asp 
(Python) https://realpython.com/regex-python/
(R) https://stringr.tidyverse.org/ 
* - Ensure you & your team tries to identify the most familiar/comfortable language or software tool on average across the team as we will be building off of this exercise moving forward (e.g. NLP, machine learning).
