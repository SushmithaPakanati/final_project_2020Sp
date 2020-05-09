Project:  Analyzing tobacco consumption in the US and predicting the smoking behavior for the next years

Main  Notebook: https://github.com/SushmithaPakanati/final_project_2020Sp/blob/master/Code.ipynb
Outputs: https://github.com/SushmithaPakanati/final_project_2020Sp/tree/master/outputs

Overview: 
The tobacco consumption dataset shows four level smoking data from 1995 to 2010. It is taken to analyze the percentage of people smoking every day, people smoking on some days, former smokers and the people who never smoked in each state in the United states of America. This data is further cleaned and used for Vector Auto Regression modeling where prediction is done for the next 10 years which are 2011 to 2019, showing the percentage of people smoking every day, people smoking on some days, the percentage of people who may have stopped smoking and lastly the latest probable percentage of people who never smoked.

Data cleaning:  
The tobacco-use dataset that is taken for the analysis and prediction shows the four-level data for all the states in the US for the years 1995 to 2010. To make it easier to understand, the dataset is split into individual files so that we would have one file for every state which has all the values through the years.

Analysis of hypothesis:
The tobacco consumption in the US differ by State and the behavioral trend over time.
Here, the investigation is done on the tobacco use in different states and the predictions done based on the smoking behavior of people in different states. For this project, the 10 largest state economies of the US are highlighted in the notebook whereas the information on all the states is stored in the output files,
The inferences drawn for the 10 states are:
*  California: In 1995, 56.70 percent of the population never smoked or have stopped smoking and that slowly increased to 64.80 in 2010 to 74.28 in 2019. Using VAR model, it is predicted that people in California have eventually reduced smoking over the years. This change might be because of many reasons, it could be because of the multiple tobacco control laws that were implemented and the awareness about the consequences of smoking. About 74.28 percentage of the population in California have stopped smoking or never smoked
* Texas: In 1995, 52.80 percent of the population in Texas never smoked and that eventually changed to 62.90 in 2010 to 70.30 in 2019. Again, this could be because of the many reasons like encouraging smokers to quit smoking by running campaigns or making public places as no smoking zones or because of educating the people on the dangers of smoking
* Likewise, in New York, the percent of people smoking was 53.40 and in 2010, 57.80. in 2019 it is 61.13
* In Florida, 1995 records 48.50, 2010 shows 53 and 2019 shows 52.83 percent of people who may have stopped smoking or have never smoked
* In Illinois, about 53.40% in 1995 to 59.50 %in 2010 to 56.68% in 2019
* In Pennsylvania, 48% in 1995, 55.40% in 2010, 59.48 in 2019
* Ohio records 50.20% in 1995, 52.90% in 2010, 52.37% in 2019
* New Jersey shows progress as it was 55.70% in 1995, 59.40% in 2010, 62.60% in 2019
* Virginia stands at 53.50% in 1995 to 57 in 2010 to a decline in 2019 to 56.61
* Lastly, North Carolina shows 51.60% in 1995 to 55.80% in 2010 to 55.86% in 2019
From all these observations we can infer that over time, with improvements in resources to help smokers quit and new control laws in place, we can see from the prediction model that more number of people may stop smoking in the future.





