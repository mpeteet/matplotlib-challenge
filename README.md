# matplotlib-challenge
Matplotlib Homework - The Power of Plots


This assignment simulated data analysis for a pharmaceutical company that specializes in anti-cancer pharmaceuticals.  The ask was analyze the data of a recent animal study and generate all of the tables and figures needed for a top-level summary of the study results.

- The analysis was started by checking the data for anomolies/duplicate data and cleaning that up.
- With the cleaned up data I generated the following:
  - a summary statistics table containing the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regiment
  - a bar plot (in pandas dataframe plot and pyplot) that show the total number of measurements taken for each treatment regimen
  - a pie plot (in pandas dataframe plot and pyplot) that shows the distribution of female and male mice
  - a calculation of the final tumor volume for each mouse across the four most promising treatment regimens; the quartiles and IQR were calculated so that potential outliers could be determined
  - box and whisker plot of the final tumor volume for all four treatment regimens with potential outliers identified (by color and style)
  - a plot for an individual mouse treated with a specific drug showing the tumor volume versus time point.
  - a scatter plot of mouse weight versus average tumor volume for a specified drug regimen
  - a calculation of the correlation coefficient and a linear regression model between moue weight and average tumor volume for a specified drug regimen
  
Conclusions and observations: 
The population of mice in the study are equally distributed between males and females.

The drug regimens with highest number of observations are Capomulin and Ramicane and both proved to be most effective at tumor reduction.

There is a strong correlation between mouse weight and tumor volume.
