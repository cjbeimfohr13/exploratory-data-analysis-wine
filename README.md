# exploratory-data-analysis-wine
The data for this exploratory analysis comes from Kaggle and examines wine data scraped from WineEnthusiast during the week of June 15th, 2017.

Tools Used: Jupyter Notebook, Matplotlib, Numpy and Scipy Stats

Initial questions about the dataset?
* what country represents where most the wines in the dataset come from?
* Is there a correlation between price of wine and the points that it is rewarded?
* How many wineries are represented in the dataset? Which winery has the most wines entered?
* what country do the best wines come from? What variety of wine is considered the best(tends to get the most points)?
* how many different varieties are there?
* what wine has the best point score and what is the most expensive wine?
* what is the wine that has the lowest score and what is the cheapest wine on the list?
* what percentage of the wines from each of the countries have a score above 88 points and below 88 points? 
 
## Insights obtained throuhgout the project:

As I began exploring and cleaning the dataset scraped from WineEnthusiast, I determined that columns (Unnamed, Description, region_2 and designation) were not needed and therefore removed. I then decided that the best way to showcase the distribution and frequency of wine scores was with a histogram shown below.

![Image](https://github.com/cjbeimfohr13/exploratory-data-analysis-wine/blob/7b541ac0f69f69b90fd9a1a2d835e1d03385fa85/Images/histogram_points.png)

I utilized the .describe() function to determine the summary statistics for the points and found that the average or mean point value for the wines in the dataset was 87.86 (rounded). The summary stats also provided the standard deviation of 3.28 showing **

From then a boxplot was used to display outlier point values from each country. 

![image](Images/boxplot_points.png)

As you can see in the chart above*

I then went through and thought it was important to display the most expensive, cheapest, wine with the highest number of points and lowest. The most expensive wine in the data set was. The cheapest was. The wine with the highest score was. Finally the wine with the lowest score was.

Within the entire dataset, the most popular wine variety was a Pinot Noir with a total of 12193 Pinot Noir varieties examined for this study. In the entire dataset there were a total of 460 different varieties.*

The number of wineries that are represented in the dataset were 11,859 throughout all 7 countries with the winery that was most represented was Williams Seylem in California. California had the most wines in the dataset with over 60,000 wines and Canada had the least with under 10,000.

It was important to display what countries produced the most wines in the dataset which is displayed in the bar chart below because I wanted to determine if the ones that were produced displayed quality or if they just had an over abundance of quantity.

![image](Images/barchar_country.png)

The pie chart below describes the percentage of wines from Argentina that fall within each point value.

![image](Images/piechart_argentina.png)

Overall 

![image](Images/dataframe.png)

In order to determine which country had produced the better wine I used .loc to seperate the wines that were above 88 points and those that were below 88 and then divided that number from the overall wine count for each country.  

![image](Images/scatterplot.png)

Following this I wanted to see if there was a correlation between the point value and the price for the wine which I found using the .corr() function and then plotted in a scatter plot which you can see below. 

 


