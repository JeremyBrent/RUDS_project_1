## Project 1: "All work and no play makes for unhappy nations"

# **Navigating Kasia’s Notebook:** 

## Questions: 
In these two sub-question, we seek to answer the following questions: 
1) Does working more make us less happy? 
2) Is there a correlation between working hours and amount of alcohol consumed?

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

