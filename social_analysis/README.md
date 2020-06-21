

## Project Title 
Social Analysis (Brand Comparison)

## Business Drivers and Significance
I wanted to do a comparison of different movies to determine where the followers located geographically and what topics concerning the brand were most important to them. This could be used for any brands, as long as they have a social presence on Twitter, Youtube, or Instagram. For the example i am doing film comparisons. 

## Project Overview- 
1. Call the api's from differnt social networks and load the comment into a dataframe.  
2. Preprocess the unstructured comments and then categorize the comments. 
. 3Geocoding the locations of the users/followers .
4. Graphical display the results using Shiny io. 

## Timeline
From start to finish, this script took about 4 weeks to complete. This is dependent on how accessible the customer is to provide feedback. 

## Features on the Application
1. Network Selection (Analysis could be done on Twitter, Youtube or Instagram. The most accurate analysis comes from Youtube because Youtube comments contain the least amount of noise(advertisements) that skew the results.
2. Search boxes that would allow to do 3 searches, similar to what you would do to find the information on the web. It could be a movie ,a product, a brand. (You need to specify the twitter hashtag, instagram account, or Youtube address)
3. The app grabs all the comments from the social network, cleans & categorize, geocodes, displays it in a bar graph and a heat map.
4. The display shows the % of times a topic was mentioned in the comments. Assuming that if a topic is mentioned the most it was the thing that stood out the most and was commented on the most.
5. The heatmap shows the regions where most of the comments orginated. 

## Screenshots
![Alt text](/social_analysis/social_2.gif?raw=true "Social Sentiment App")

## Technologies Used
1. Used R to create the script to scrap the data, preprocess the data, categorize the data, geo-code the data and display the results.

## License
Code is licensed to Reelanaytics, Inc. but snippets are share to augment understanding of the project.


