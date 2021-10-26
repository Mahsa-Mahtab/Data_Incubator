# Project goal
It has been more than two years in global scale that the world is dealing with the ongoing COVID pandemic. Some countries were affected more than others, and this was the result of many combined factors such as country population and demographic, quarantine restrictions strategies, border controls and so forth. On  Monday, November 09, 2020, Pfizer and BioNTech announced the very first effective vaccine with more than 90% protection based on their preliminary analysis. However, it took several weeks to months for the vaccination process to be established in different countries and more months to see the downward trend in COVID rate. In early summer 2021, many countries started to remove COVID restrictions gradually and one of those were school opening for this fall.  In this project, my goal was to investigate the effect of removing restrictions on COVID rate; specifically, the school opening.  

# Effect of school opening on COVID rate  
The main question for this part is to see if there is any correlation between school opening and positive cases of covid. To investigate this, the official day of school opening was considered to be September 1st of 2021. A time period of 10 days and 50 days, before and after school opening, was selected to investigate if there is a significant correlation. 

# Data acquisition 
Historical data is taken from ourworldindata.org that gathers data from governments and health ministries worldwide. Data can be downloaded in csv format for the countries of interest. The source data doesn’t require extensive cleaning and is arranged in 65 columns with Header’s identifier as can be seen in the Jupyter notebook. For studying the effect of school opening on number of covid cases, the “new cases” column data is used specifically

# Data visualization and exploration
Different features of the data can be easily visualized by selecting the desired time range within the Jupiter notebook. For example, as shown in the notebook, the positive rate of COVID is shown from January 2020 till today. 

# Hypothesis testing 
One hypothesis was if the school opening would increase the positive rate of COVID because of unavoidable decreased social distancing in school environment. For investigating this, back in September, I had only 10 days of data available for the first two weeks of September. Therefore, I tried to compare the positive rate within the 10 days before and after the school opening which showed about 80% increase in the positive rate. That means, opening the school has increased covid rate based on this time interval. 
However, after having more data available, I tested the hypothesis over 100 days of data that included 50 days before and after the school opening. This test resulted into 150% decrease in the positive rate which means that covid rate was not increased with school opening. 

# Future work: Feature importance analysis
COVID rate is actually a function of several factors and each of these needs to be included to obtain more reliable result. One important piece of information that is not included in this study yet is the vaccinated population that has been increasing rapidly during the past several months. As a data scientist, one important fact that we need to consider it to find out how different factors can affect our analysis and prediction and how they are compared with each other in terms of importance. 
For such purpose, I plan to investigate other factors while the most important one seems to be the vaccination rate. Several features can be studied such as vaccine type and administered dose in different countries to see what combination has been the most effective one to reduce the covid rate. The result of such study can be used not only for those countries that are still experiencing a high rate of covid but also in future if another variety of covid becomes dominant or entirely different virus attack a society.  


