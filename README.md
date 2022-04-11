# OlympicDatabase

## Overview 
This repo contains the code used to create a project for my business systems and analytics class on Olympic Trends. The data was originally collected by Kaggle user RGRIFFEN, which you can find [here](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results). 

## Data Cleaning File

Creating and populating a MS SQL Server was part of the project. Our team designed/reverse engineered a database based on athlete event data from kaggle. The jupyter notebook on data cleaning was used to create 5 different csv files that could be directly imported into the 5 tables we created in our database. 

## Data visualization File

This file was used to answer several questions reguarding age in the olympics. To answer these questions, we first ran queries on the database and exported them as json files. This file uses these json files and the seaborn library to create some nice visuals of the results. 


