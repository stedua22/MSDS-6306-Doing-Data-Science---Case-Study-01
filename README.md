# MSDS-6306-Doing-Data-Science---Case-Study-01

## Introduction
In this project, we will analyze the alcohol contents(ABV) and bitterness(IBU) of craft beers in the breweries of United States based on the data that was provided by Budweiser. The purpose of this analysis is to find a conclusion that would be beneficial to the Budwiser enterprise and provide leadership (CEO and CFO of Budweiser) with data driven conclusions. We will perform an EDA and introduce the KNN classification model of beer types using ABV and IBU values and verified with beer samples in the market including Budweiser. 

## Datasets
The Beers dataset contains a list of 2410 US craft beers and Breweries dataset contains 558 US breweries. The datasets descriptions are as follows. We will be using R to perform statistical analysis.

### Beers.csv:  
Name: Name of the beer
Beer_ID: Unique identifier of the beer  
ABV: Alcohol by volume of the beer  
IBU: International Bitterness Units of the beer  
Brewery_ID: Brewery id associated with the beer  
Style: Style of the beer  
Ounces: Ounces of beer  

### Breweries.csv:  
Brew_ID: Unique identifier of the brewery  
Name: Name of the brewery  
City: City where the brewery is located  
State: U.S. State where the brewery is located  

## Questions
1.	How many breweries are present in each state?
2.	Merge beer data with the breweries data. Print the first 6 observations and the last six observations to check the merged file.  (RMD only, this does not need to be included in the presentation or the deck.)
3.	Address the missing values in each column.
4.	Compute the median alcohol content and international bitterness unit for each state. Plot a bar chart to compare.
5.	Which state has the maximum alcoholic (ABV) beer? Which state has the most bitter (IBU) beer?
6.	Comment on the summary statistics and distribution of the ABV variable.
7.	Is there an apparent relationship between the bitterness of the beer and its alcoholic content? Draw a scatter plot.  Make your best judgment of a relationship and EXPLAIN your answer.
8.	Budweiser would also like to investigate the difference with respect to IBU and ABV between IPAs (India Pale Ales) and other types of Ale (any beer with “Ale” in its name other than IPA).  You decide to use KNN classification to investigate this relationship.  Provide statistical evidence one way or the other. You can of course assume your audience is comfortable with percentages … KNN is very easy to understand conceptually. 
9.  Find one other useful inference from the data that you feel Budweiser may be able to find value in.  You must convince them why it is important and back up your conviction with appropriate statistical evidence

## Table of Contents
1. Beers and Breweries Dataset  
2. RMD file  
3. Knit html file  
4. Codebook
5. ReadMe.md

## Conclusion
In our data analysis, we have analyzed the datasets of Brew and Breweries focused on the alcohol contents(ABV) and bitterness(IBU) in the United States. We discovered that Colorado and California are the states with highest numbers of breweries (47 and 39 respectively). We compared two methods, where we eliminated the missing values and replaced the missing data with an average. Which resulted in the minimum ABV to go from 2.7% to 0.1%. Since no other siginificant changes to the data summaries were observed, analysis continued with the removal of missing data. The median ABV was found to be 5.6%. The highest ABV and IBU was 12.8% (Colorado) and 138 (Oregon). Interestingly, we found a strong, positive linear relationship between ABV and IBU. After additional analysis, we can see that IPAs have a higher ABV and IBU than other ales, and by using a KNN algorithim, accuractely predict if its an IPA with 83% accuracyIn our KNN model, we decided to include our N/A using the median. We showed the classification model of beer types using ABV and IBU values and verified with beer samples in the market including Budweiser. We suggested in making IPAs for Budweiser because we use the average IBU and ABV values in our KNN model to predict IPAs. 

## Authors
Stephanie Duarte

Catherine Ticzon
