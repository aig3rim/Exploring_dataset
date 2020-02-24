# Exploring_dataset
This is the second project done on [Udacity's Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) program, where I analyzed data from a fact tank [Gapminder](https://www.gapminder.org/data/) and then communicated findings on correlations between suicide rates and income per person, population density and Human Development Index (HDI) and its comparison between 1990 and 2015 years.

## Getting started
You need an installation of Python, plus the following libraries:
* numpy
* pandas
* matplotlib.pyplot
* seaborn

## About the project

### Motivation
I am passionate about psychology and getting interesting insights from data and I decided to combine it. On Gapminder I could find data on mental health, particularly, suicide rates for different countries per year. While looking at the data, I assumed that maybe in developed countries people less commit suicide, which was the starting point for creating research questions.
## Content
This project consists of the following steps:
* **Introduction** - a brief explaination of data used for the project and its documentation. Also, there you can find the research questions
* **Data Wrangling** - loading and exploring data on suicide, population, population density, income per person and HDI data
* **Data Cleaning** - dealing with NULL values
* **Exploratory Data Analysis** - answering research questions using descriptive statistics and visualization
* **Conclusions** - communicating the findings based on the research questions

## Research questions and results
### Q1: Did the percentage of suicides increase/decrease in 2015 compared to 1990 year?  Which countries have the highest and the lowest rates of suicide deaths? Did the countries with the highest and the lowest suicide rates change in 2015?
* The percentage of suicieds out of the total population was increased in 73 countries. However, there are 70 countries where the suicide rate was decreased in 2015. Overall, a ratio between the countries with increased and decreased suicide rates is almost equal (70 to 73); 
* Countries with the highest proportion of suicides out of the total population: Hungary (1990) and Lithuania (2015); 
* Countries with the lowest proportion of suicides out of the total population: Jamaica (1990) and Sao Tome and Principe (2015).

### Q2: Are people in countries with high income and high HDI less tend to commit suicide? Is there any change between 1990 and 2015 years?

* An interesting finding of the analysis is people in developed countries with high and moderately high income and HDI are more tend to commit suicide; 
* In 2015 countries with moderately high income had the highest suicide rate, while in 1990 countries with high income had the highest chance of suicides; 
* There is the same pattern for average percentage of suicides and HDI levels for 1990 and 2015 years. 


### Q3: Is there any correlation between densily populated countries and suicide rates? Did the pattern of suicides change in 2015 compared to 1990 year?

* It seems that there is no strong correlation between population density and average suicide rates. For example, in 1990 countries with moderately high and high population density had the highest rate of sucides. However, in 2015 the suicide rates are almost similar for each population density levels. 
