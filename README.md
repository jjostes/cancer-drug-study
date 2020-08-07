

<!-- ABOUT THE PROJECT -->
## About The Project

The prompt for this assignment:

"As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 250 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results."


### Built With

Jupyter Notebook, with the following dependencies:
* matplotlib.pyplot
* pandas
* scipy.stats
* numpy

<!-- USAGE EXAMPLES -->
## Usage

Generates:
  * summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
  * bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of data points for each treatment regimen.
  * pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.
  * box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
  * line plot of time point versus tumor volume for a single mouse treated with Capomulin.
  * scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

Calculates:
  * the final tumor volume of each mouse across for four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
  * quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
  * correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Includes linear regresion.

<!-- CONTACT -->
## Contact

John Jostes - [https://www.linkedin.com/in/john-jostes-386b841a0/](https://www.linkedin.com/in/john-jostes-386b841a0/)

Project Link: [https://github.com/jjostes/cancer-drug-study](https://github.com/jjostes/cancer-drug-study)
