# NYC-Taxi-Cab-ANOVA
My portion of a Data Mining group project where I perform multiple ANOVA tests on NYC Taxi Cab data.

As part of a final project for an introductory Data Mining course, my groupmates and I decided to perform an exploratory analysis upon a comprehensive dataset of NYC Taxi Cab information. Some of the attributes included the travel time and distance as well as the number of passengers and tipping amount. My portion of the project focused on determining whether true statisitcal differences in tipping percentage and travel distance existed between various groups such as the number of passengers (single or multiple), season, and year (pre-post-Covid and pre-post-Uber). To do so, I enlisted bootstrap sampling to invoke the Central Limit Theorem in order to satisfy one of the assumptions needed for ANOVA analysis.

My portion of the project is entirely coded in Python using Google Colab.
My work can be viewed in the anova.ipynb file which is intended to be viewed in Google Colab as it was the environment used to work in. The final report detailing all members' work can be read in Cpts315-FinalPaper.pdf. Lastly, TaxiDataCleaned.csv contains the cleaned data (performed by one of the group members) in which I then use to perform ANOVA tests.
