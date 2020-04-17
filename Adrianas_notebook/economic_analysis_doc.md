Stage 1 of my economic analysis was filtering the source data to include only information for our chosen years and nations.
Years = 1950 to present
Nations = 2 representatives from each continent* (USA, Mexico, Venezuela, Brazil, South Africa, Nigeria, Poland, Sweden, China, South Korea, Australia, Russia*)
*Russia was included to give an even number because Australia was only nation from Oceanania.

Once filtered this new data was marked clean and became primary source for analysis.

Stage 2 data analysis.
Part 1: 
I started by graphing the annual hours worked for each year. This was easy enough but very repetitive and required coding each nation with a different color to make readable. Biggest issue with this plot was the time spent writing the inputs and figuring out how to move my legend to outside my plot.
From this figure we could visualize some shifts in working hours and did some external research on possible causes. The most notable example was a sharp decline for South Korea around the late 80s, early 90s which we found was actually the transition period of SK into a democracy and the establishment of the organizd labor movement and labor laws. 

Part 2:
Next I moved onto plotting working hours versus GDP but quickly found that my data contained a lot of empty values (0s) as well as 2 nonsense columns likely leftover from previous data cleaning. So I had to add in an additional data cleaning step to remove these before building a scatter plot with a linear regression line. The grouping of the points made me suspect that the data was likely grouping far more within nation and our r square value was not great because of differences between nations.
I attempted a single nation graph by effectively making an exact copy of the code but filtering for only data with the code USA but this did not improve my r square value and issues with plot size halted my progress investigating this.
UPDATE: plot size issue fixed by removing annotation of linear regression line
To check if the points were indeed grouping by nation I made a seaborn plot using nation code as the hue argument and my suspicion was confirmed. 

Part 3:
I had intiailly planned to make a figure for each of the five data tables I had, but the hours worked in the house by age/gender group did not fit into the overall story as well as the others and because I knew that I would be dropping to only a couple figures anyway I decided not to wait my time and commented out what I had started workin on, which was originaly going to be a duo of pie charts for data from 1950 and 2010.

Part 4:
The final set of data I went to analyze was working hours vs productivity (measured in dollar generated per hour). For this I effectively recreated all the work I did for the gdp analysis, including the additional data cleaning step. The plot with all nations had a similarly poor r square value around -.5 and the seaborn displayed a large trend towards grouping within nation for data points. I did a USA only plot and found a much better r square of -.85, indicating a negative correlation between hours worked and productivity.

Part 5:
After seeing how the USA only graph I did a similar single nation graphing of working hours vs GDP working hours vs productivity for South Kora and Poland. I also added a coloring of the scatter dots by year to see if we could identify trends within nation clusters over time.
