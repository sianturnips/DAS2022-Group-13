# DAS2022-Group-13
## About the Project
This repository contains the group project for Data Analysis Skills 2022.

The key file is `Group_13_Analysis.Rmd`, this contains the core code for our analysis of the given dataset. The data set is contained within the `dataset13.csv` file.
The output of the code execution is stored within the `Group_13_Analysis.html` file, this can be then saved to other formats as required.

## Built With
The analysis was produced using an R markdown file. The packages used are:
 - tidyverse
 - moderndive
 - gapminder
 - sjPlot
 - stats
 - jtools
 - dplyr
 - zoo
 - kableExtra
 - scales
 - gridExtra
 - janitor

The loading of these packages is included at the beginning of the R markdown file.

## Getting Started
The `Group_13_Analysis.Rmd` file can be opened in R studio and an output can be created by knitting the document.

## Dataset
The `dataset13.csv` file contains the data used in the analysis. 
The dataset was provided to us for analysis and contains information on furniture from Ikea in Saudi Arabia.

## What does it Produce
When knitted, the `Group_13_Analysis.Rmd` file produces the analysis on the dataset included in this repository. 

The aim was to fit a Generalised Linear Model (GLM) to the data and find out which variables are most important in determining if an item of furniture costs more than 1000 Riyals. 

The output contains exploratory analysis of the relationship between different variables and price through plots and graphs. Then a GLM is fitted with whether the price is greater than 1000 Riyals as the response variable using the `logit`, `probit` then `loglog` [link functions](https://www.rdocumentation.org/packages/stats/versions/3.6.2/topics/family).

---
#### Contributers
This project was created by Sian Turner, Ajay Sreekumar, Jingxuan Peng, Hancheng Lu and Ningqi Zhang. (2022)
