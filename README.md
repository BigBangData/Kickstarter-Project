## Repository Contents:

1. REAMDE file 
2. Rmd Files (R Markdown)
3. PDF Outputs 

===============================================================================
	
# 1 - README  

The 'Kickstarter Project' is a repository of projects associated with Kickstarter data.

This repository started as partial credit for the University of Colorado Boulder [Master's of Science in Business Analytics](https://www.colorado.edu/business/ms-programs/masters-program-business-analytics) class 'Fundamendals of Data Analytics', taught by [Professor Nicholas Reinholtz](http://www.reinholtzresearch.com/).

**Kaggle Dataset Description**

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


## Project 1 - Logistic Regression / Categories

This project aims to generate simple predictions based on logistic regression models for the probability of project success using project duration and goal amount, grouped according to main project categories.

A better description of project limitations and scope is found in the .Rmd and PDF documents themselves.

## Project 2 - Logistic Regression / Seasons

This project piggy-backs on Project 1 and aims to answer whether there are seasonal effects on probability of success. 


===============================================================================

# 2 - RMD FILES 

The R Markdown files (.Rmd) were written in Notepad++ and loaded into RStudio. The files can be found in this repository. The .Rmd files were used to generate the PDF outputs in RStudio using MikTeX and the knitr package.

 
===============================================================================

# 3 - PDF Outputs

The resulting outputs of the .Rmd files are PDFs of the projects, found in this repository. These PDFs describe the data cleaning and analyses unencumbered by R code, which can be found in a code appendix. Enjoy!


---




