

## Project Title 
1. Predict Customer Lifetime Value (CLV)
 
## Business Drivers and Significance
1. They would like to predict the Lifetime Value of all new customers. Knowing a customers lifetime value would be benificial when determine the marketing dollars to spend acquiring new customers. 

## Project Overview- 
1. Train a model in ML Azure Studio that will predict which quantile (10 - 100 with 10 being the lowest value), new customers fall in. This will also create an api that can be integrated into an application that will predict new customers. 
2. Create a web service(api) that will now predict new customers. 
3. To predict new customers, I created a script in R, that connects to the api, passes in new data. The model creates the prediction and passes the results. I then used json to convert the results, which i then join to the original dataset.
4. Export to .csv (can be automatically saved to Sharepoint, SQL Server,etc.)  

Note: New customer data can be housed on an external system in an excel document. The R Script can pass that data in to be predicted on.

## Implementation Process
1. Preprocess and prepare the data using ML Azure Studio.
2. Train the model in ML Azure Studio.
3. Create the web service/api in ML Azure Studio.
4. Create the R Script needed run the prediction through api and then append the new data onto the existing dataset.

## Features
1. A spreadsheet with an additional column that contains the predicted score for the new customer.

## Timeline
From start to finish, the total process took about 3 weeks to develop. This is dependent on how accessible the customer is to provide feedback and assistance. 

## Screenshots
1. After pre-processing the data,creating the model in ML Azure, in the screenshot below i have a trained model with a predicted column. The predicted column predicts new customer's CLV. The prediction engine scores each customer from 10 to 100, with 10 being on the low end up to 100 on the high end. Also an API was created. I could integrate that API into an application to predict new customers. I normally use it with Power BI, so that i can include the new customer scores into values in a dashboard. I did not for this project. 

![Alt text](/predictive_analytics/scored_dataset.PNG?raw=true "Film Analysis Dashboard")

## Technologies Used
1. ML Azure Studio
2. R to create the script
3. Excel

## License
I have included the code template i used to get the information from ML Azure and into the final dataset.


