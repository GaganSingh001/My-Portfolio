

## Project Title 
Insurance Analysis

## Business Drivers and Significance
This analysis is needed to determine the variables that directly affect Customer Lifetime Value(CLV). Understanding these variable will help a company focus on areas that are important.

## Project Overview-
1. Determine what variables are important and eliminate from the dataset variables that have no affect on the analysis.
2. Create a Decisions Tree. A decision tree can be used to visually and explicitly represent decisions and decision making. As the name goes, it uses a tree-like model of decisions. 
3. Create a Correleation Plot. A correlation plot shows what fields relate most to other fields in the dataset. For instance,budget & profit. We know most of the time the higher the budget the greater the profit. The correlation plot will show those types of relationships graphically
4. Create a Cluster chart. Building off the previous Correlation plot i will create a cluster diagram using the the most important correlating fields to determine if there are any clusters or groupings. Knowing what cluster a customer falls in can assists in marketing efforts.  Customers in the same cluster are more like other customers in that cluster.

## Implementation Phases

1. Use R script to subset the dataset and include only the most important fields.
2. Create scripts for each of the chart listed in the Project Overview.
3. Create a Power Bi visuals for each of R scripts developed from #2. These visual will be R Script visuals.

## Features
1. An intuitive aggragate dashboard that allows the user to display the key factors that affect CLV.

## Timeline
From start to finish, this script took about 1 week to develop. This was dependent on how accessible the customer is to provide feedback. 

## Screenshots 
1. The most important variables in determining Customer Lifetime Value are No of Policies, Monthly Premium, Total Claim Amt, Months Since Last Claim, Vehicle Class, Months Since Policy Inception and Income. We will use these variables to do further analysis. The other variables do not have a signicant impact on CLV.
![Alt text](/data_analysis/importance.PNG?raw=true "Importance Variables")
2. The darker the color (blue), the higher the correlation between variables. There is less correlation between the reds. For instance looking at the chart below, it is showing that the higher the coverage, the higher the Monthly Premium Amount and that there is no correlation between income and Total Claim Amount.
![Alt text](/data_analysis/correlation.png?raw=true "Variables That Correlate")
3. Looking at the decision tree it seems that the people with the Monthly Premium Amount greater/equal to 96.5 give you the greater CLV.
![Alt text](/data_analysis/dt.PNG?raw=true "Decision Tree")
4. Analyzing Income and Customer Lifetime Value you can see below the distinct clusters of customers based on income and that the most prevalent clusters are the lighter blue and pink. If you  planning to do a marketing campain those are two distinct groups you can target.
![Alt text](/data_analysis/clusters.PNG?raw=true "Clusters")

## Technologies Used
1. R is used for development and Power BI is used for diplaying the data.

## License
Due to  privacy, i cannot diplay the final dashboard, but i did provide some of the code used to do the analysis.



