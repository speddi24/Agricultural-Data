# Agricultural-Data
Classification of grid cells to determine the yield rate. Required csv files for years 2013,2015,2016,2017 and 2018 were added to the repository.

Project Statement
This project is to determine the classification of grid cells within a plot (400x600 meters) and determine if these grids have a low, average, or high yield rate. 
In addition, we determine if these grid cells have stable, average, or unstable yields. This will be done by normalizing the estimates based on a ranking methodology.
The optimal grid cells have been predetermined to have 6 columns due to the harvester size, and 20 rows has been determined by optimation analysis in the Grid Cell Size
section (120 grid cells total). We will plot the results over each yeart’s harvest formation for the merged data as well as each years data to see how each plot yielded
and how stable those yield values are.

Refer the .RMD file for detailed statistical analysis.

The field was divided into 6 columns and 20 rows. The selected grid size was validated by calculating the number of required replicates and CV. The number of observations
per grid were more than 30 bushels and the plot of log minimum samples clearly illustrates the same. The data was screened to check if all the crops were harvested within
a week.And the plot indicates that all the crops were harvested within a week for all the years.Then the boundaries of the fields were verified for all the years.The 
yield was then normalized by ranking them and mean of yield was calculated per grid.Finally,mean rank and standard deviation were calculated for the ranks of all years to
indicate the performance of the field per grid over 5 years.The field was classified as High,Low and Average Yielding based on the normalized rank and as Stable, Unstable
and Average Yielding based on the Standard deviation of the normalized rank. Graphs were plotted to show the same.Further, additional graphs were plotted for the mean 
rank for original data for individual years and their yield classes.

