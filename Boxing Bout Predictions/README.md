# Boxing Bout Predictions

Personal project for predicting winning boxers based on scraped BoxRec data (https://boxrec.com/)

Includes all data cleaning, feature engineering, models deployed, and model evaluation.

Boxer physcial attributes such as weight and reach proved to be less significant features than age, W/L ratio with respoect to total fights, and Knockout percentage wrt total fights. 

I chose to account for the total number of fights a boxer had using a wilson score interval, where Score = Lower bound of Wilson score confidence interval for a Bernoulli parameter. This concept is fo described here https://www.evanmiller.org/how-not-to-sort-by-average-rating.html
