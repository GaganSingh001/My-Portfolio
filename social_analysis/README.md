

## Project Title 
Social Analysis Of Sentiment (Comparing Brands)

## Business Drivers and Significance
I wanted to do a comparison of different movies to determine where the followers were coming from and what topics were most important to them. This could be used for any type brands and not just movies. I just used movie comparisons as an example. It could be brand comparison. The main objective what to determine where the followers are coming from and what topics are most important to the followers.

## Project Overview- 
1. Scrape comments from differnt social networks, clean up the comments and then categorize the comments. 
2. Get the locations of the users making the comment and put into a heat mat.
 
## Implementation Phases
1. Create the script to scrape Twitter, Instagram, and Youtube.
2. Create script to clean up the comments, taking out words that would not be useful for anaysis and leaving words that would be relavant.
3. Categorize the comments pulling out the most common keywords.
4. Determine how many times each of those keywords showed up in each comment.
5. Geocode the users location, so that they could be integrated into a heat map.(Twitter is the only Network that can be Geo-coded)
5. Graphical show the results.

## Timeline
From start to finish, this script took about 4 weeks to develop. This is dependent on how accessible the customer is to provide feedback. (The web scraping of the data was a part of a different phase)

## Features on the Application
1. Network Selection 
2. Search boxes that would allow to do 3 searches, similar to what you would do to find the information on the web. It could be a movie name,a product, a brand. (You need to specify the twitter hashtag, instagram account, or Youtube address)
3. The app grabs all the comments from the social network, cleans & categorize, geocodes, displays it in a bar graph and a heat map.
4. The display shows the % of times a topic was mentioned in the comments. Assuming that if a topic is mentioned the most it was the thing that stood out the most and was commented on the most.
5. The heatmap shows the regions where most of the comments orginated. 

## Screenshots
1.![Alt text](/social_analysis/social_2.gif?raw=true "Social Sentiment App")

## Technologies Used
1. Used R to create the script to scrap the data, preprocess the data, categorize the data, geo-code the data and display the results.

## License
Code is licensed to Reelanaytics, Inc. but snippets are share to augment understanding of the project.


