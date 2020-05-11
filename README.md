[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kurt-gilby/DSDP/master)
# DSDP
This repository will be used to store the work being done for the DSDP projects and artifacts associated with the project.
# Task Tracker
  ### Objective:
    Given is the nutritional value data of the Mcdonalds Menu in the United States.
    Using the said data the following objectives are to be archived:
        1. Identify a business question to be answered
        2. Identify a target variable to be predicted.
        2. Identify the features to be used to best predict the target variable.
        3. Implement a model to predict the target variable
  #### High Level Tasks:
    1. Import and read data--Done
    2. Clean data and treat for any missing/non consistant values-WIP
        1.No Missing Values Found
        2 Got the Magnitude and Unit for each serving.
        3.Added a Cnt Column equal to 1 for each record
        4.Made all the Countinous data the proper data types
            4.1 set all values to the same scale.
        5.aligned all the catigorical to the left and continous to the right
        6.Saved the dataset as csv as a check point.   
    3. Explore data using discrete statistic to understand the data bettter--WIP
    4. Send the project to the Team for review.
# File Index
1. McDonald_Menu.csv
2. McdonaldMenuDataAnalytics.ipynb
3. Cleaned.CSV
4. Nval.csv
5. dNval.csv
### McDonald_Menu.csv
  Input data for the project, has nutrition data from the McDonalds menus (United States).
### McdonaldMenuDataAnalytics.ipynb
  The Jupyter notebook with the python codes run on the data.
### Cleaned.CSV
  Ouput post the changes:
    1. Changed the column names.
    2. Changed split serving in magnitude and unit.
    3. Converted floz to ml and mg to g.
### Nval.csv
  Data set with the overall Nutrition values
### dNval.csv
  Data set with the Daily Nutrition values
  
  
