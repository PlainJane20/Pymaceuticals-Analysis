# Pymaceuticals-Analysis

![Laboratory](Images/Laboratory.jpg)

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Tumor development was observed and measured over the course of 45 days. The goal of the study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the three other treatment regimens. The executive team has asked for a top-level summary of the study results listed below.

Datasets used were [Mouse_metadata.csv](Pymaceuticals-Analysis/Pymaceuticals/Resources/Mouse_metadata.csv) and [Study_results.csv](Pymaceuticals-Analysis/Pymaceuticals/Resources/Study_results.csv)

Using MatPlotLib and Pandas Python libraries in a Jupyter notebook, the following is generated (this is high level, for detailed data analysis please click on the link): [Pymaceuticals_Outcome](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/pymaceuticals_starter.ipynb)

* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![Stats_Summary.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Stats%20Summary.JPG)

* Bar plot showing the total number of unique mice tested on each drug regimen using pandas.

![Bar01.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Bar01.JPG)

* Bar plot showing the total number of unqiue mice tested on each drug regimen using using pyplot.

![Bar02.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Bar02.JPG)

* A Pie plot showing the distribution of female versus male mice using pandas.

![Pie01.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Pie01.JPG)

* A pie plot showing the distribution of female versus male mice using pyplot

![Pie02.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Pie02.JPG)

* Box plot of the final tumor volume of each mouse across four regimens of interest.

![Box01.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Box01.JPG)

* A line plot of tumor volume vs. time point for a mouse treated with Capomulin.

![Line01.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Line01.JPG)

* A scatter plot of average tumor volume vs. mouse weight for the Capomulin regimen

![Scatter01.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Scatter01.JPG)

* The correlation between mouse weight and the average tumor volume is 0.84.

![Correlaton01.JPG](https://github.com/PlainJane20/Pymaceuticals-Analysis/blob/main/Pymaceuticals/Images/Correlaton01.JPG)

### Few observations: 
* Capomulin seemed to be effective in reducing the average SCC tumor volume in mice over a 45 day period. 
* When looking at the gender correlation, the case study had nearly identical number of male vs female mice count. 
* Weight of the mice correlated strongly (r- 0.84) with average tumor volume. 
* Out of the four drugs regimen Capomulin, Infubinol, Ramicane, and Ceftamin only Infubinol had one outlier data point. 

# Navi Sohi | Data Analytics
