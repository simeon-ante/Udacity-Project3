# Ford Gobike Analysis

Author: Simeon Ante

## Description

The Ford Gobike dataset for February 2019 was analyzed to gain insights on the bike sharing behavior of users in the greater San Francisco Bay area. This readme file explains the analysis carried out, the libraries used, the files included and how to reproduce the analysis.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Files Included

- Ford_Gobike_Analysis.ipynb (Jupyter Notebook containing the analysis)
- Ford_Gobike_Analysis.html (HTML version of the notebook)
- 201902-fordgobike-tripdata.csv (the original dataset used for the analysis)

## Analysis

The analysis started by importing the necessary libraries and the dataset. The data was then cleaned by handling missing values and creating new columns to aid the analysis.

Exploratory Data Analysis (EDA) was carried out to understand the distribution of the variables and how they relate to each other. The EDA was followed by data visualization using different plots such as bar charts, heatmaps, and scatter plots.

The analysis showed that users ride more during the weekdays than the weekends, which may be attributed to commuting to and from workplaces. The most popular ride periods were at 8am and 5pm during the weekdays. During the weekends, customers took more rides than subscribers, and the most popular ride period was during the afternoons. Age and duration of rides had no correlation, but customers took longer rides on average than subscribers.

## Presentation

The analysis was summarized into a presentation by focusing on describing the users and showing the behavior of the different groups of users based on their age, gender, and type. The presentation included the popular ride days, the distribution of users based on gender, age, and user type, and the behavior of the two user types. Different palettes were used for each categorical variable to clearly show their difference.

## Reproducing the Analysis

To reproduce the analysis, download the Ford_Gobike_Analysis.ipynb and 201902-fordgobike-tripdata.csv files. Open the notebook in Jupyter and run the cells in order. The libraries used must be installed in the environment where the analysis is being run.
