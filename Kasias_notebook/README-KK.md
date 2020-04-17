# RUDS_project_1: Kasia's Analysis

## Research Questions:
In these two sub-question, we seek to answer the following questions: 
	1) Does working more make us less happy?
	2) Is the a correlation between working hours and amount of alcohol consumed? 

## Resources (URL):
- Working hours: https://ourworldindata.org/working-hours
- Happiness Data: https://www.kaggle.com/unsdsn/world-happiness
- Alcohol consumption: https://apps.who.int/gho/data/node.main.A1036?lang=en

## Data information: 
1) Happiness and working hours: 
There are two files exploring relationships between annual working hours and self-reported happiness on a cantril scale. Both sets take a snapshot of 2017 stats. The first set explores all the overlapping countries in the two data sets. The second set uses representative countries: 2 from each world region represeting politically and socially diverse outlooks. Both of these sets were derived from csv files and analyzed using jupyter notebook with pandas and matplotlib. 

Additional considered variables: Although our umbrella question focused on working hours and happiness, we also looked at GDP, Family, Health/Life Expectancy, and Trust in Government in relation to the happiness score. The strongest correlation to the happiness score was observed with increasing GDP. 

2) Alcohol consumption and working hours: 
Alcohol amount consumed in liters of pure alcohol was compared to annual hours worked for 2016 only. Similarly to the Happiness Data, this set has two files, one with all countries that overlapped between the two sets and one with the same selected countries as above. Both of these sets were derived from csv files and analyzed using jupyter notebook with pandas and matplotlib. 

## Results 
1. Happiness and annual working hours displayed the following correlations: 
	All countries overlapping countries for two datasets: Happiness vs. Annual Work Hours (n=64): r^2=-0.37
		Additional variable analysis for all countries: 
			Happiness vs. GDP (n=64): r^2=0.57
			Happiness vs. Family (n=64): r^2=0.47
			Happiness vs. Health & Life Expectancy (n=64): r^2=0.40
			Happiness vs. Trust in Government and Corruption (n=64): r^2=0.41
	Selected countries: Happiness vs. Annual Work Hours for 2017 (n=12) r^2=-0.4

There seems to be a downward trend for annual work and happiness scores. Although the correlation is not strong, there is a clear trend showing that the more you work, the less happy you tend to be. There are clear exceptions such as Mexico that rank high on the happiness scale but have one of the highest working hours in this data set. This could be related to factors that each culture defines as happiness. This data also showed that our "selected" countries were a good representation of the world as the r squared values between the two sets were close. 

2. Alcohol consumption and annual working hours displayed the following correlations: 
	All countries overlapping countries for two datasets: Alcohol Consumption vs. Annual Work Hours (n=57): r^2=-0.30
		All countries: Males only: r^2=-0.26
		All countries: Females only: r^2=-0.38	
	Selected countries: Alcohol Consumption vs. Annual Work Hours for 2017 (n=12) r^2=-0.13
		Selected countries: Males only: r^2=-0.08
		Selected countries: Females only: r^2=-0.10

A lack of strong correlation was observed between the two data sets. The limitations of this analysis was the fact that alcohol is not universally consumed and that there are cultural and religious factors that need to be considered for an appropriate analysis. An interesting finding from this data set however was the fact that males consumed siginifically more alcohol per year than females. Our selected countries did not correlate well with the whole world sample here. 

		
## Limitations
- Happiness is a self-reported scale. People's understanding of happiness may not be universal. 
- Alcohol data has only two year's worth of data. It might also be interesting to look at the types of alcohol consumed between the different countries. 
- Cultural and religious factors need to accounted for, for the alcohol data. 
	
 
 
