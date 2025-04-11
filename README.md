This project analyzes the effectiveness of various drug regimens on reducing tumor volume in mice. By cleaning and merging datasets, then applying statistical and visual analysis, the study identifies Capomulin and Ramicane as the most effective treatments. Key metrics such as mean, median, variance, and standard error were calculated for each regimen, providing insight into the consistency and performance of the treatments. Visualizations like bar charts, box plots, and scatter plots helped reinforce findings, while correlation analysis revealed a strong relationship between mouse weight and tumor size under Capomulin, highlighting its potential as a promising cancer treatment.

Prepare the Data:-

I was able to merge datasets into a single DataFrame.
The number of mice are shown from the merged DataFrame.
Each duplicate mice was found based on the Mouse ID and Timepoint.
A clean DataFrame was created with the dropped duplicate mice.
The number of mice were shown from the clean DataFrame.
Well done with this deliverable !!!!
----------------------------------------------------------
Generate Summary Statistics:-

I was able to find the mean of the tumor volume for each regimen was calculated using groupby.
I was able to find the media of the tumor volume for each regimen was calculated using groupby.
I was able to find the variance of the tumor volume for each regimen was calculated using groupby.
The standard deviation of the tumor volume for each regimen was calculated using groupby.
The SEM of the tumor volume for each regimen was calculated using groupby.
I was able to create a new DataFrame with using the summary statistics.
Good Job here !!!!
---------------------------------------------------------------
Create Bar Charts and Pie Charts:-
---------------------------------------------------------------
A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas was generated.
A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot was generated.
A pie plot showing the distribution of female versus male mice using Pandas was generated.
A pie plot showing the distribution of female versus male mice using pyplot was generated.
Great job !!!
----------------------------------------------------------------------------------------------
Calculate Quartiles, Find Outliers, and Create a Box Plot:-

A DataFrame that has the last timepoint for each mouse ID was created using groupby.
The index of the DataFrame was reset.
Retrieved the maximum timepoint for each mouse.
The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, were put in a list.
An empty list was created to fill with tumor volume data.
A for loop was used to display the interquartile range (IQR) and the outliers for each treatment group.
A box plot was generated that shows the distribution of the final tumor volume for all the mice in each treatment group.
Well Done !!!
-------------------------------------------------------------------
Create a Line Plot and a Scatter Plot :-
A line plot was generated that shows the tumor volume vs. time point for one mouse treated with Capomulin.
A scatter plot was generated that shows average tumor volume vs. mouse weight for the Capomulin regimen.
---------------------------------------------------------------------
Calculate Correlation and Regression:-
The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen.
