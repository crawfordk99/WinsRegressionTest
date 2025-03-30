# WinsRegressionTest

## Statistical Test

This is a multiple logistic regression test. For this test, I was simply focused on comparing the effect these 
different type of scores have on the odds of winning for an NBA team this year (Not on how they interact with each other). Calculating the actual probability of a team
winning would require further analysis involving an NBA team's defensive stats, turnovers, rebounds, and efficiency. 
It is also important to note that the NBA's style has changed over the years. This test might turn out different
in the 80's-2000's compared to now.

## Packages/Data

R has a package called hoopR provided by sportsDataVerse that grabs box scores from ESPN. You can get the latest season's
box scores from it which was great for my test. Besides that I used tidyverse, pander (for clean summaries), and
ResourceSelection (provides the hoslem.test function for testing the goodness of fit for the data). 

## Helpful links

-[hoopR package](https://hoopr.sportsdataverse.org/)

## Future work
-Defensive stats and their effect on the odds of winning
-Turnovers
-The interactivity of all of these stats
-ML model
