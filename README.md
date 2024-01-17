# CS210Project
In this project I wanted to analyze my step count and basal energy data I got from the Apple Health App.

First of all, I created a dataframe for total step counts for months each year by scraping the data from the xml file I got from Apple Health App.
Then I checked if there are any missing values in the dataframe and filled in those values with the average values.
Then I updated the dataframe to see average monthly step counts for each year.

After I created these two dataframes I plotted multiple graphs to see the relationship between months and step counts each year. I also plotted the graph to see average step counts each year.

I also created a basal energy dataframe by scraping data from the xml file. However there did not exist that much data for basal energy so the dataframe included only 1 year.

After the creation of the basal energy dataframe I plotted the step counts and basal energy for each month in a single graph to see if there is any relation between them.

To see if my observations from the graphs are true, I used T-test method from scikit library.

Finally, I used Decision Tree Regresser from scikit library to predict 2024 step counts and I also used Linear Regression from scikit library to predict December 2023 step count which is already in the dataframe.

The techniques used in this project are:
-Data manipulation, cleaning and formatting
-Data visualization: line charts and bar charts
-Hypothesis testing: T-test
-Machine learning: Decision Tree Regressor and Linear Regression

The link for the presentation for my project:
https://drive.google.com/file/d/1y0GkvTTxdto39hu82Fm2J1TZL2P9hrYo/view?usp=sharing 
