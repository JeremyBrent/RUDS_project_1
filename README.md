## Project 1: "All work and no play makes for unhappy nations"

# **Navigating Kasia’s Notebook:** 

## Questions: 
In these two sub-question, we seek to answer the following questions: 
1. Does working more make us less happy? 
2. Is there a correlation between working hours and amount of alcohol consumed?

## Data: 
Happiness vs. Annual Working Hours 
- First file focuses on all overlapping countries between the two subsets for 2017 (kasia-happy-all.ipynb)
- Second file contains representative countries chosen by that group for 2017  (kasia-happy.ipynb)
- Each notebook contains additional analyses included for other factors outside of working hours that could correlate to happiness 

Amount of Alcohol Consumed vs. Annual Working Hours 
- First file focuses on all overlapping countries between the two subsets for 2016: analysis done for combined sex, males only, females only (kasia-alcohol-all.ipynb) 
- Second file contains representative countries chosen by that group for 2016: analysis done for combined sex, males only, females only (kasia-alcohol.ipynb)

## Tools: 
- All analyses were done in Jupyter Notebook using pandas and matplotlib  

## General Conclusions
- Happiness decreases the more hours we work 
- Alcohol and working hours have no strong correlation 
- However, males drink consistently more than females all over the world 
- Specific stats are described in depth within the Notebook’s Read Me 

# **Navigating Adriana’s Notebook:**

## Questions: 
1. Have the annual hours worked changed over the past 70 years for our representative nations?
2. What is the relationship between annual working hours and national GDP?
3. What is the relationship between annual working hours and productivity?

## Data: 
Annual hours, GDP, and productivity data were obtained from [Our World in Data](https://ourworldindata.org/working-hours) and cleaned.

## File explanation
- data_cleaner.ipynb is the initial data cleaning notebook which takes raw input and filtered to selected nation and year. Outputs cleaned data.
- economic_anaysis.ipynb is the figure generating notebook which takes the cleaned files and generates figures to answer the above questions.

**_NOTE:_ Both files assume that the input and output csv file path is located within a data folder at the same level of the notebook.**
Location of the data folder was moved post merge with the master branch. 

## Tools: 
- All data wrangling done using pandas and numpy. 
- Analysis done using scipy.stats.
- Figures built using matplotlib and seaborn.

## General Conclusions
- For the majority of nation's graphed a slight decline in annual hours worked over the past 70 years can be seen.
- Working hours vs GDP and working hours vs productivity is extremely nation dependant but graphing by single nation shows a clear correlation of a negative relationship in both.

##
For more detail please reference documentation within Adriana's Notebook.

# **Navigating Matteo’s Notebook:**

## Questions:

In this sub-question, we seek to answer the following questions: 
1.	Is there a correlation between GDP per Capita and the overall happiness of a country?

## Data:

GDP vs. Happiness (Life satisfaction, Cantril Ladder 0-10) – Cleaned up data some more to make it usable for my analysis. Removing unneeded columns and setting fields to numeric all in my jupyter notebook (GDP_vs_Happiness.ipynb). 

1st Analysis - First I set off to find the countries that had the highest and lowest happiness ratings. From there I plotted both in one graph to visually determine if GDP plays a part in happiness levels.

2nd Analysis – I then gathered all the countries from the entire dataset and plotted them to also check if the same applied from my 1st analysis. 
Tools: -- All analysis were done in Jupyter Notebook using pandas and matplotlib

## Conclusions:

From my 1st and 2nd analysis using this dataset we can determine that there is a correlation between GDP and happiness. 

Countries with higher happiness scores showed an increase in GDP over time.

Counties with lower happiness scores showed a decline in GDP over time.  


# **Navigating Jeremy’s Notebook:** 

## Questions: 
1. What is the average World Happiness Report Scores for the chosen countries?
2. What is the prevelance of mental health and substance use disorders for the chosen countries?
3. What is the average Cantril Happiness Scores for the chosen countries?
4. How has Cantril Happiness Scores changed over time?
5. What is the relationship between Cantril Happiness Scores and Working hours?
6. What is the relationship between Mental Health and Substance Use Disorders and Working hours?
7. What is the correlation between all of the variables we looked at?


## Data: 
- World Happiness Report data was obtained on Kaggle (https://www.kaggle.com/unsdsn/world-happiness#2019.csv)
- Mental Health Data was obtained on Our World in Data (https://ourworldindata.org/mental-health)

## Tools: 
- All analyses were done in Jupyter Notebook using pandas, matplotlib, scipy, seaborn, and plotly. 

## General Conclusions
- Sweden and Australia tended to have the highest happiness scores. 
- Cantril Happiness remained relatively consistent over time for most countries with exemption to Venezula who saw a sharp decline in happiness score in 2014. 
- Cantril Happiness and Working Hours had a small to moderate relationship (r<sup>2</sup> = .41) with a negative slope. 
- Mental Health and Substance Use Disorders and Working Hours had a  moderate relationship (r<sup>2</sup> = .46) with a negative slope

