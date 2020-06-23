

## Project Title 
1. Predict Customer Lifetime Value (CLV)
 
## Business Drivers and Significance
1. They would like to predict the Lifetime Value of all new customers. Knowing a customers lifetime value would be benificial when determine the marketing dollars to spend acquiring new customers. 

## Project Overview- 
1. Train a model in ML Azure Studio that will predict which quantile (10 - 100 with 10 being the lowest value), new customers fall in. This will also create an api that can be integrated into an application that will predict new customers. 
2. Use R to connect to the api, make the prediction and append the new data to the existing dataset. This data can then be used to create reports and dashboards.
 
## Implementation Process
1. Preprocess and prepare the data using ML Azure Studio.
2. Train the model in ML Azure Studio.
3. Create the api in ML Azure Studio.
4. Create the R Script needed run the prediction using the api and then appended the new data onto the existing dataset.

## Features
1. A spreadshet with an additional column that contains the predicted value for each customer.

## Timeline
From start to finish, the total process took about 3 weeks to develop. This is dependent on how accessible the customer is to provide feedback. 

## Screenshots
1. After pre-processing the data,creating the model in ML Azure, in the screenshot below i have a trained model with a predicted column. The predicted column predicts new customer's CLV. The prediction engine scores each customer from 10 to 100, with 10 being on the low end up to 100 on the high end. Also an API was created. I could integrate that API into an application to predict new customers. I normally use it with Power BI, so that i can include the new customer scores into values in a dashboard. I did not for this project. 

![Alt text](/predictive_analytics/scored_dataset.PNG?raw=true "Film Analysis Dashboard")

## Technologies Used
1. ML Azure Studio
2. R-Scrip to integrate the api into Power BI
3. Excel

## License
I have included the code i used to get new predicted data and merge back into an existing dataset. This code can be used directly in Power Bi.


