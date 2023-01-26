# DataCleaning-Visualization-Modeling
DataCleaning:-

First I loaded the 3 csv files then I Examined the datasets with Pandas, which displays all columns and their data
types, the top ten for each dataset, and basic statistics for numeric columns
(Count, mean, std, min, max).
2. Then I Showed the missing data and incorrect values for each column, such as zeros and
negative sales.
3. I Decided to drop the negative values and leave the zeros as zeroes may be an important indicator but the negative values were incorrect as I compared it 
with the previous values and it showed that they were outliers
4. Then I Merged all datasets into data frame based on the date and store

Visualization:-
Then I made lots of plots to understand the data and the relationships among them 
1. made a chart to illustrate if weekly sales are increasing or decreasing over time.
2. made a chart to show how much each brand sells.
3. Determined the top ten selling stores.
4. made a histogram to show the top 10 stores sales.
5. Created a chart that compares average weekly sales for the top ten selling stores during holidays and non-holidays.
6. Created a chart that displays the average weekly sales for each brand department for the top 10 selling stores.
7. made a line chart to show the relationship between weekly sales and weather Temperature.
8. made a line chart to show the relationship between the cost of fuel and weather weekly sales.
9. For each possible pair,I created a pair plot to show different correlations using sns.pairplot.
10. plotted and saved a correlation matrix between all of the numerical attributes and discussed various correlations that I've discovered.

Modeling:-
To forecast weekly sales, I created machine learning models:
1.I chose category, sales and holiday because they have a good relation with weekly sales 

2. Divided the data into training and testing categories (80 percent training data and 20 percent testing data).

3. Created KNeighborsRegressor and LinearRegression supervised learning models to forecast weekly sales based on category, sales and holiday.

4. Compared the accuracy of the two models (in percentages) and the KNN had a much better percentage.

5. Created a clustering model to group together store categories with similar sales.
and figured out that the best number of Clusters is 3 according to elbow plot.
