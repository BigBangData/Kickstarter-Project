## Repository Contents:

1. REAMDE file 
2. Raw Data Descriptions
3. Rmd File (R Markdown)
4. PDF File (.Rmd output)

===============================================================================
	
# 1 - README  

The 'Kickstarter Project' is a repository of projects associated with Kickstarter data.

This repository started as partial credit for the University of Colorado Boulder [Master's of Science in Business Analytics](https://www.colorado.edu/business/ms-programs/masters-program-business-analytics) class 'Fundamendals of Data Analytics', taught by [Professor Nicholas Reinholtz](http://www.reinholtzresearch.com/).

## Project 1 - Logistic Regression using Kickstarter data from Kaggle

Generate simple predictions based on logistic regression models for project success probabilities using project duration and goal amount, grouped according to main project categories.


===============================================================================

# 2 - RAW DATA DESCRIPTION

## Kaggle Dataset 

The dataset is just over the GitHub recommended 50 MB limit and can be downloaded from Kaggle [here](https://www.kaggle.com/kemical/kickstarter-projects). Since the 2016 dataset exhibits some unexplainable data incongruencies, the 2018 dataset is used.

Variables in the 2018 dataset are:

- ID: internal kickstarter id
- name: name of project 
- category: category of a project (159 categories)
- main_category: category of campaign (15 total)
- currency: currency used to support project (14 total)
- deadline: deadline for crowdfunding
- goal: fundraising goal 
- launched: date launched
- pledged: amount pledged by crowd
- state: final (or current) condition of the project 
- backers: final (or current) number of backers
- country: country pledged from (23 total)
- usd.pledged: conversion in US dollars of the pledged column (conversion done by kickstarter)
- usd_pledged_real: conversion in US dollars of the pledged column (conversion from Fixer.io API)
- usd_goal_real: conversion in US dollars of the goal column (conversion from Fixer.io API)



===============================================================================

# 3 - RMD FILE 

The R Markdown file (.Rmd) was written in Notepad++ and loaded into RStudio. The file can be found in this repository. The .Rmd file is used to generate the PDF output in RStudio using MikTeX and the knitr package.

 
===============================================================================

# 4 - PDF Output

The resulting outputof the .Rmd file, a PDF of the project, is found in this repository. It describes the data cleanup process and analysis unencumbered by R code, which can be found in the appendix. Enjoy!


---




