# The Economics Behind Happiness
##### A Quantitative Exploration of What Makes Us Happy

I wanted to explore the age old question “How to be happy?” and "Does money buy happiness?" by using my background in Economics and RStudio to analyze quantitative data from Kaggle. Using "World Happiness Report 2021" created by Ajaypal Singh, I was able to predict happiness levels based on freedom to make life decisions, and generosity based on happiness levels. Finally, I analyzed each of the seven factors to determine which of them predicted happiness levels the best.

The packages used in this data exploration project are ggplot2 and dplyr. 

In this repository, "world-happiness-report-2021.csv" is the working data set used for this project.

A challenge I faced in this project was skewed data due to a small number of observations in the Australia region indicator. I could have split up the continent region indicator into more specific regions such as Western/Eastern Europe, North/Central/South America, Carribean, Sub Saharan/Central/South Africa, Middle East, East/South/Southeast Asia, Pacific Islands, and Oceania. By doing this, I'll be able to accurately determine the variance in different factors instead of blindly categorizing culturally and economically different countries together based on their location.

In a future project, I'd like to explore more factors that determine happiness levels in certain regions. Explanatory variables such as GDP per capita, annual income per household, government expenditure on education, government expenditure on healthcare, and import to export ratio in order to fully answer the age old question "Does money buy happiness?". 