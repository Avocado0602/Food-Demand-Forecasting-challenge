# Food-Demand-Forecasting-challenge
Your client is a meal delivery company which operates in multiple cities. They have various fulfillment centers in these cities for dispatching meal orders to their customers. The client wants you to help these centers with demand forecasting for upcoming weeks so that these centers will plan the stock of raw materials accordingly.

The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance. Secondly, staffing of the centers is also one area wherein accurate demand forecasts are really helpful. Given the following information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations in the test set:  

Historical data of demand for a product-center combination (Weeks: 1 to 145)
Product(Meal) features such as category, sub-category, current price and discount
Information for fulfillment center like center area, city information etc.
 

Weekly Demand data (train.csv): Contains the historical demand data for all centers, test.csv contains all the following features except the target variable
fulfilment_center_info.csv: Contains information for each fulfilment center
meal_info.csv: Contains information for each meal being served
 

Evaluation Metric
The evaluation metric for this competition is 100*RMSLE where RMSLE is Root of Mean Squared Logarithmic Error across all entries in the test set.

With this challenge, I obtain the ranking of 124 out of 7240 participants
The link of the contest is here: https://datahack.analyticsvidhya.com/contest/genpact-machine-learning-hackathon-1/
The link for my visualization to understand more about the data is here: https://public.tableau.com/app/profile/tai.nguyen5781
