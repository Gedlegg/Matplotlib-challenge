# Matplotlib-challenge

# Overview of the analysis performed
- The datasets were merged into a single DataFrame 
- Duplicate entries with the same mouse ID and timepoint were identified and removed to ensure data integrity.
- Summary statistics were calculated for each drug regimen, including mean, median, variance, standard deviation, and standard error of the mean of the tumor volume.
- Bar charts were generated to visualize the total number of timepoints for all mice tested for each drug regimen. Both Pandas and Matplotlib methods were used to create identical charts.
- Pie charts were created to illustrate the distribution of female versus male mice. Again both Pandas and Matplotlib methods were used to create identical charts.
- The final tumor volume of each mouse was calculated for the four most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Quartiles and the interquartile range (IQR) were determined for each treatment regimen, and potential outliers were identified using upper and lower bounds.
- A box plot was generated to visualize the distribution of the final tumor volume for mice in each treatment group.
- A line plot was created to display the tumor volume over time for a single mouse treated with Capomulin.
- A scatter plot was generated to examine the relationship between mouse weight and the average observed tumor volume for the entire Capomulin regimen
- The correlation coefficient between mouse weight and average observed tumor volume for the Capomulin regimen was calculated
- Additionally, a linear regression model was fitted to the data to estimate the relationship between mouse weight and tumor volume