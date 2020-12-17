# Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago

# Background
The business question for the final project is "How can we combat life expectancy and mortality rates in the 45-64 age group in Baltimore City?" To support this, as part of the final project, we ran the simple regression between life expectancy rate and household income. Also, we did cluster analysis for life expectancy rate including variables such as bike lanes, free/reduced meals, healthy food index, etc. To better support the final project and add more information, I am going to add another varialbe which is poverty rate and another city which is going to be Chicago. The main objective of this project would be to see if both Baltimore and Chicago have same relationship between poverty rate and life expectancy, and also to see if Chicago has the same relationship between income and life exepctancy as Baltimore which we already did in our final project. This project would help the final project to have more solid solutions such as UBI that could possibly solve the poverty issue and eventually increase the life expectancy. Moreover, the project is going to cover how Chicago and Baltimore is different in terms of demographics. 

# Data
[Life expectancy rate - Baltimore] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/b481bba144d2f33ba44fdd1389e0b3b9429f5f1c

[Life expectancy rate - Chicago] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/ba0630b13bdda85658b30b36c04e7986d7f66cf9

[Poverty rate - Baltimore] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/e47e5b8c5518efe1a4e040130ae9fc8d4981027e

[Poverty rate - Chicago] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/63f67b746f5fa239960a06f4adff020d87ab6001

[Per capita income - Chicago] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/e04e484f06494f6c9fd614fd3b4811e4ae48e6b3

[Age group population - Baltimore] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/aacad35e0f49083eb6ba4d3764487ad89799b556

[Age group population - Chicago] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/dda5660ef2d04b565e399b8fc1641833a7cc58e6

[Gender ratio - Baltimore] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/cd4f8d77847caedacb07dfaec2b14e2e875e5ab1

[Gender ratio - Chicago] https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/commit/3e50fb09d0d0754315347d7ce60de9532cf4d429

# Python Notebook/Analysis

Used Python and Google Colaboratory to conduct analysis
* **Python - comparing incarceration rate for different parent income in Baltimore City and Washington, DC**: a Google Colaboratory notebook to aggregate data and conduct analysis with Python [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mtiqum_Bf5h6a5wmJOHzPdT9K9_QaklI#scrollTo=5o5o0qYgYZep)

# Data Analysis

# Demographics difference in Chicago and Baltimore
Before the poverty rate and life expectancy rate comparison in both cities, it would make sense to compare how two cities are different from each other in terms of demographics, including the total population, age group population, and gender ratio.  

## Age group population in Chicago and Baltimore
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.35.45%20AM.png)
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.36.28%20AM.png)

Age group population distribution between Chicago and Baltimore are almost the same. The highest age group population is 30 - 49 years old for both cities, and both cities have bell curved shape distributions. Also, the second highest age group populaiton were 21-29 age group and 50-61 age group for both cities. The only difference is that the total populaiton is much higher for Chicago where the total populaiton is almost 2.7M compared to Baltimore where the total populaiton is about 600K. Due to the higher population in Chicago, although the trend for age group distributions are same for both cities, the actual population for each bar is much higher for Chicago. 

## Gender ratio in Chicago and Baltimore
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.37.07%20AM.png)
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.37.38%20AM.png)

Next is gender ratio comparison in both cities. In both cities, there are more male population. However, Baltimore has a slightly higher male population of 53.1% whereas the male populaton in Chicago is 51.3%.

Now that we have seen how these two cities are different in some ways, I am going to compare poverty rate and life expectancy for both cities to see if they both have same trend. 

## Poverty rate vs. Life expectancy rate in Chicago and Baltimore
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.32.01%20AM.png)
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.33.48%20AM.png)

Both scatter plots and trend lines show that both Baltimore and Chicago have inverse relationship between the poverty rate and life expectancy rate. Thus, as poverty rate increases the life expectancy decreases. The only difference could be for Chicago, individual data points tend to spread out more than the ones in Baltimore scatter plot. For Baltimore scatter plot, individual data points tend to cluster around the trend line. This could indicate that the R^2 value could be slightly lower for Chicago which means the poverty rate could be less better in explaining the life expectancy value in Chicago compared to Baltimore.

## Income vs. Life expectancy rate in Chicago and Baltimore
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.33.06%20AM.png)

In our final project, we compared the median household income and life expectancy rate. Here, I used per capita income instead of median household income given that the information on median household income in Chicago was not available. Compared to the Baltimore scatterplot, both cities have the same trend of positive relaitonship between two variables which means that as income increases, the life expectancy rate increased. The main difference though again is that the individual dots are more spread out for Chicago whereas the individual dots are more closely clustered around the trend line for Baltimore. This might indicate that the R^2 value could be lower for Chicago, which means that per capita income could be less better in explaining the life expectancy rate in Chicago compared to Baltimore

## Average poverty rate and life expectancy rate in Chicago and Baltimore
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.34.35%20AM.png)
![alt text](https://github.com/michellesykim/Comparing-poverty-rate-income-and-life-expectancy-rate-in-Chicago/blob/main/Screen%20Shot%202020-12-11%20at%202.35.05%20AM.png)

Also, both the average poverty rate and life expectancy rate in Chicago are higher than Baltimore. One might think since the poverty rate and life expectancy have inverse relationship, if average poverty rate is higher in Chicago, it would makes sense for Chicago to have lower life expectancy. However, as I shown before, sinc e Chicago has higher population overall, there could be more outliers that could led to this result for Chicago. It is true that both Chicago and Baltimore had a strong inverse relationship for life expectancy rate and poverty rate. However, for our final project, considering the fact that individual data points for Chicago scatter plots were more spread out whereas the points in Baltimore were much more clustered around the trend line, it would be much more important for Baltimore to have solutions that could potentially lower the poverty rate given the fact that life expectancy rate in Baltimore is much more affected by the poverty rate compared to Chicago. 

