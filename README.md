# matplotlib-Pymaceuticals 💊
"What good is data without a good plot to tell the story?" 📊  

![Laboratory](https://github.com/RutgersCodingBootcamp/RU-JER-DATA-PT-01-2020/blob/master/02-Homework/05-Matplotlib/Instructions/Images/Laboratory.jpg?raw=true)  


Pymaceuticals Inc. is a *fictional* pharmaceutical company. It specializes in anti-cancer pharmaceuticals; in its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. I am its senior data analyst, I have been given access to the complete data from their most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. I have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.  
My tasks were to do the following:
- Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of data points for each treatment regimen. NOTE: These plots should look identical.  

![Bar Plot](https://github.com/ognjenstrbanovic/matplotlib-challenge/blob/master/screenshots/Bar%20Plot%20Screen%20Shot.jpg?raw=true)  

- Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study. NOTE: These plots should look identical.
- Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
- Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. Hint: All four box plots should be within the same figure.  

![Box and Whisker Plot](https://github.com/ognjenstrbanovic/matplotlib-challenge/blob/master/screenshots/Box%20and%20Whisker%20Plot.jpg?raw=true)  

- Generate a line plot of time point versus tumor volume for a single mouse treated with Capomulin.
- Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
- Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.  

![Linear Regression Model](https://github.com/ognjenstrbanovic/matplotlib-challenge/blob/master/screenshots/Linear%20Regression%20Model.jpg?raw=true)  

- Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
```
Objectives for Unit 5 - Intro to Matplotlib
- Understand Matplotlib's pyplot interface.
- Be able to create line; bar; scatter; and pie charts.
- Be familiar with basic plot configuration options, such as xlim and ylim.
- Feel comfortable creating plots using the DataFrame.plot() method.
- Understand the advantages and disadvantages of creating charts using the DataFrame.plot() method.
- Be able to work through a complex data set using Pandas and then chart some visualizations based upon the cleaned DataFrame.
- Be able to define mean, median, and mode, and choose which one is most appropriate to describe a given data set.
- Be able to explain the meaning of variance and standard deviation.
- Be able to describe standard error and the difference between a sample and a population.
- Be able to add error bars to their plots.
- Be able to fit lines to their data.
```
