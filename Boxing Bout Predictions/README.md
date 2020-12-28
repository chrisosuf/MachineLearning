# Boxing Bout Predictions

Personal project for predicting winning boxers based on scraped BoxRec data (https://boxrec.com/)

Includes all data cleaning, feature engineering, models deployed, and model evaluation.

Boxer physical attributes such as weight and reach proved to be less significant features than age, W/L ratio, and Knockout percentage with respect to total fights. 

I chose to account for a boxer's total number of fights in my engineered ratio features using a wilson score interval: Score = Lower bound of Wilson score confidence interval for a Bernoulli parameter. This concept is further described here: https://www.evanmiller.org/how-not-to-sort-by-average-rating.html
