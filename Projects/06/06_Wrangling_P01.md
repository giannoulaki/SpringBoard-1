# **Capstone Project 01:  Insights into hospital readmission using medicare's public data bases**
# _Data Cleaning_
####  by: Julio Cárdenas-Rodríguez
![medi](Medicare.png)
## Steps
1. _Find dataset and become familiar with the data._      
I had to read the data dictionary from medicare to understand the meaning of each variable and the available tables. The dictionary is located ![here](./Hospital.pdf)
2. _Gather all ```readmission reduction.csv``` files for each year._  
I used the unix shell to get all files and rename then accordingly:
- READMISSION_REDUCTION_2016.csv
- READMISSION_REDUCTION_2015.csv
- READMISSION_REDUCTION_2014.csv
- READMISSION_REDUCTION_2013.csv
- READMISSION_REDUCTION_2012.csv

Now that you have a basic ideas of the various data wrangling steps and techniques available, let's apply it to your Capstone Project! By now, you probably have a data set in mind for your project (If you don't have a data set yet, come back to this assignment once you have one). Apply some of the data wrangling techniques you have learned to this data set.

Submission: Create a short document (1-2 pages) in your github describing the data wrangling steps that you undertook to clean your capstone project data set. What kind of cleaning steps did you perform? How did you deal with missing values, if any? Were there outliers, and how did you decide to handle them? This document will eventually become part of your milestone report.