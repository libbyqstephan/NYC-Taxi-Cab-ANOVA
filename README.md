# NYC-Taxi-Cab-ANOVA
My portion of a Data Mining group project where I perform multiple ANOVA tests on NYC Taxi Cab data.

As part of a final project for an introductory Data Mining course, my groupmates and I perform exploratory analysis upon a comprehensive dataset of NYC Taxi Cab information. Some of the attributes included the travel time and distance as well as the number of passengers and tipping amount. My portion of the project focuses on determining whether true statisitcal differences in tipping percentage and travel distance existed between various groups such as the number of passengers (single or multiple), season, and year (pre-post-Covid and pre-post-Uber). In other words, I performed ANOVA (ANalysis Of VAriance) tests. 

To do so, I enlist bootstrap sampling to invoke the Central Limit Theorem. This theorem states that if an average of a sample (at least of size 30) were repeated for a very large number of times, then the distribution of the sample means will approach an approximately normal distribution. A normal distribution in each group is one of the three assumptions needed for more reliable and trustworthy ANOVA results. The other two assumptions being the variance between groups are roughly equivalent and observations are independent.

My portion of the project is entirely coded in Python using Google Colab.
My work can be viewed in the anova.ipynb file which is intended to be viewed in Google Colab as it was the environment used to work in. The final report detailing all members' work can be read in Cpts315-FinalPaper.pdf. Lastly, TaxiDataCleaned.csv contains the cleaned data (performed by one of the group members) in which I then use to perform ANOVA tests.
