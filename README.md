# Comparing Social Mobility in Baltimore and Washington, D.C.

## Background
For our final project, my group decided to focus on social metrics in Baltimore and Washington, D.C. in order to compare the viability of social mobility in these two cities. In particular, we focused on two independent variables: the percentage of adults who continue to live in the same neighborhood, and the household income of people who live within their commuting zone. 

Our dependent variable was the median household income of various neighborhoods in Baltimore. By comparing and analyzing these metrics, our goal was to determine if any conclusive observations could be drawn about the restrictions placed upon impoverished residents who are unable to commute to better economic opportunities.  The purpose of this write-up is to summarize and present my contribution to this project – the multiple linear regression.

## Question
For my portion of the final project, I focused on the issue of comparing the effect of the multiple independent variables on the dependent variables. Is it possible to graphically and numerically demonstrate a relationship between multiple data inputs?

## Data Source
All of the data used in this project was gathered from [The Opportunity Atlas](https://www.opportunityatlas.org/). If you would like to view the raw datasets used for this analysis, please see the "Import Data" section of our Google Colaboratory notebook.

## Data Answer
The following data analysis was conducted using Python, in the Google Colaboratory notebook.

## Single Variable Linearity
Before performing the multiple linear regression, I wanted to graphically represent the relationship between each individual independent variable and the dependent variable of median income. I used matplot to create scatter plots, which can be seen below.

### Baltimore, Median Income vs. Percentage Stay
![](.gitbook/assets/balti-pcnt.png)

### Baltimore, Median Income vs. Income of Workers Living in Commuting Zone
![](.gitbook/assets/balti-income.png)

### DC, Median Income vs. Percentage Stay
![](.gitbook/assets/dc-pcnt.png)

### DC, Median Income vs. Income of Workers Living in Commuting Zone
![](.gitbook/assets/dc-income.png)
