Line plot
---------

  1. A line plot is a graph that displays data using a number line.

  2. To create a line plot, first create a number line that includes all the values in the data set. Next, place an X (or dot) above each data value on the number line.

  3. If a value occurs more than once in a data set, place an over that number for each time it occurs.

Bar plot
--------
  1. A bar graph shows comparisons among discrete categories. One axis of the chart shows the specific categories being compared, and the other axis represents a measured value. 
  2. Some bar graphs present bars clustered in groups of more than one, showing the values of more than one measured variable. 

Histogram
---------
  1. A histogram is an approximate representation of the distribution of numerical data.

  2. To construct a histogram, the first step is to "bin" (or "bucket") the range of values—that is, divide the entire range of values into a series of intervals—and then count how many values fall into each interval.

  3. The words used to describe the patterns in a histogram are: "symmetric", "skewed left" or "right", "unimodal", "bimodal" or "multimodal".

Scatter plot
------------
  1. A scatter plot is a type of plot using Cartesian coordinates to display values for typically two variables for a set of data.

  2. The data are displayed as a collection of points, each having the value of one variable determining the position on the horizontal axis and the value of the other variable determining the position on the vertical axis.

  3. Scatter plot's are used to observe and show relationships between two numeric variables.


Pair plot
---------
It is a seaborn method to plot pair wise data at once.
    refer this image:
      ![alt pair plot](https://miro.medium.com/max/2000/1*xoLUv_IOzG7ExOOj6Ao7-g.png)


Count plot
----------
  1. A countplot is kind of likea histogram or a bar graph for some categorical area.

  2. It simply shows the number of occurrences of an item based on a certain type of category. 

Box plot
--------
   A boxplot is a standardized way of displaying the dataset based on a five-number summary:

   1. Minimum (Q0 or 0th percentile): the lowest data point excluding any outliers.

   2. Maximum (Q4 or 100th percentile): the largest data point excluding any outliers.

   3. Median (Q2 or 50th percentile): the middle value of the dataset.

   4. First quartile (Q1 or 25th percentile): also known as the lower quartile qn(0.25), is the median of the lower half of the dataset.

   5. Third quartile (Q3 or 75th percentile): also known as the upper quartile qn(0.75), is the median of the upper half of the dataset

   refer this image: ![alt box plot](https://www.researchgate.net/publication/318986284/figure/fig1/AS:525404105646080@1502277508250/Boxplot-with-outliers-The-upper-and-lower-fences-represent-values-more-and-less-than.png)


Violin plot
-----------
   1. A violin plot is a method of plotting numeric data.

   2. Violin plots are similar to box plots, except that they also show the probability density of the data at different values, usually smoothed by a kernel density estimator.
   3. It has:

      1. Median (a white dot on the violin plot)
      2. Interquartile range (the black bar in the center of violin)
      3. The lower/upper adjacent values (the black lines stretched from the bar) — defined as first quartile — 1.5 IQR and third quartile + 1.5 IQR respectively. 

      refer these images: 
      
      ![alt Violin plot example](https://miro.medium.com/max/650/1*TTMOaNG1o4PgQd-e8LurMg.png)
			![alt Violin plot example](https://miro.medium.com/max/875/1*dLw-Ib14E5VNSR_w1eIFug.png)
			![alt Violin plot example](https://miro.medium.com/max/875/1*Uv7CXOXoYKM4B7ZkuvoXCQ.png)

Boxen plot
----------
   1. The Boxen plot is very similar to box plot, except for the fact that it plots different quartile values.

   2. By plotting different quartile values, we are able to understand the shape of the distribution particularly in the head end and tail end.

   refer this image:
		![alt Boxen plot](https://miro.medium.com/max/2000/1*0xDlqwqIIeJqUbKmbo0_EA.png)


Point plot (seaborn)
--------------------

  1. A point plot uses scatter plot glyphs to visualize features like point estimates and confidence intervals.

  2. A point plot uses scatter plot points to represent the central tendency of numeric data.

  3. These plots make use of error bars to indicate any uncertainty around the numeric variables.
	refer this image:
		![alt Point plot](https://media.geeksforgeeks.org/wp-content/uploads/20200716095149/Screenshot339.png)

Strip plot
----------
  1. A strip plot is a scatter plot where one of the variables is categorical.
	refere image:
		![](http://alanpryorjr.com/visualizations/seaborn/stripplot/output_11_0.png)

  2. They can be combined with other plots to provide additional information
	example: Strip plot + Box lot
	refere image:
		![](http://alanpryorjr.com/visualizations/seaborn/stripplot/output_27_0.png)



Swarm plot
----------
  1. The swarm plot is a type of scatter plot, but helps in visualizing different categorical variables.

  2. Scatter plots generally plots based on numeric values, but most of the data analyses happens on categorical variables.

  3. So, swarm plots seem very useful in those cases.

  refer this image:
	 	![alt Swarm plot](https://miro.medium.com/max/2000/1*BrKie5dntOvX6d1_jEsu_g.png)


Cat plot
--------
  It is a seaborn function which give access to several types of plots that show relationship between numerical variable and one or more categorical variables, like boxplot, stripplot and so on.

  Categorical scatterplots
    stripplot() – with kind="strip"
    swarmplot() – with kind="swarm"

  Categorical distribution plots

    boxplot() – with kind="box"
    violinplot() – with kind="violin"
    boxenplot() – with kind="boxen"

  Categorical estimate plots

    pointplot() – with kind="point"
    barplot() – with kind="bar"
    countplot() – with kind="count"


Dendrogram
----------
  1. A dendrogram is a diagram that shows the hierarchical relationship between objects. 
  
  2. It is most commonly created as an output from hierarchical clustering. 

  3. The main use of a dendrogram is to work out the best way to allocate objects to clusters.

  refer this image:
		![alt dendrogram examle](https://46gyn61z4i0t1u1pnq2bbk2e-wpengine.netdna-ssl.com/wp-content/uploads/2018/03/What-is-a-Dendrogram.png)
		![alt dendrogram examle](https://46gyn61z4i0t1u1pnq2bbk2e-wpengine.netdna-ssl.com/wp-content/uploads/2018/03/Screen-Shot-2018-03-21-at-4.45.46-pm.png)


Chi-Square test
---------------
   1. The Chi Square statistic is commonly used for testing relationships between categorical variables.
      
   2. The null hypothesis of the Chi-Square test is that no relationship exists on the categorical variables in the population; they are independent.

   3. Example: Is there any significant relationship between gender and education qualification?

   4. The Chi-Square statistic is most commonly used to evaluate Tests of Independence when using a crosstabulation.

   5. Crosstabulation presents the distributions of two categorical variables simultaneously, with the intersections of the categories of the variables appearing in the cells of the table. that is values of one variable represents the row and other's value represents the column.

   Example: 
   ![alt crosstabulation of male female education qualification](https://www.researchgate.net/profile/Robert-Nathan-2/publication/50367376/figure/tbl3/AS:669323903369245@1536590662441/Cross-tabulation-between-Gender-and-Highest-Education-Achieved.png)

   7. formula: ![alt formula](https://cdn1.byjus.com/wp-content/uploads/2020/10/Chi-Square-Test.png)

   8. The Chi-Square statistic is based on the difference between what is actually observed in the data and what would be expected if there was truly no relationship between the variables.

   9. This statistic can be evaluated by comparing the actual value against a critical value found in a Chi-Square distribution (where degrees of freedom is calculated as of rows – 1 x columns – 1), but it is easier to simply examine the p-value.

   10. To make a conclusion about the hypothesis with 95% confidence. Significance(p value of the Chi-square statistic) should be less than 0.05.

   11. Alpha level = 0.05(i.e 5%) 95% confidence about conclusion and 5% risk of not making a correct conclusion.

   12. Interpret the key results for Chi-Square Test for Association
       1. Determine whether the association between the variables is statistically significant.

       2. Examine the differences between expected counts and observed counts to determine which variable levels may have the most impact on association.