# Capstone-B-Proposals
Three proposed capstone ideas for Galvanize Data Science Capstone B

Idea 1: Craigslist Motorcycle Price Predictor

This project will build a price predictor for a motorcycle based on the craigslist marketplace. I will trial three different models (random-forest, gradient-boosting, and a neural network) and identify one that is the best fit to predict prices based existing features listed for motorcycles on the craigslist marketplace to include city. 

This project will produce a website utilizing flask for users to interact with where they can input their own features which will output a recommended price with a confidence interval provided as a recommended 'high'-'low' range. 

The data for this project will be built from craigslist motorcycle marketplace data scraped from every city in America on Craigslist.

Idea 2: Hawaii Housing Shortage Prediction

Hawaii has high demand for real estate because of its perception as an island paradise with limited available land. Recently there has been a backlash against AirBnB rentals by some because of the percieved impact to the housing shortage (an important issue in Hawaii coupled with a large homeless population). This project will build four different predictions against growing trends to compare them against eachother and test for a shortage. These predictions will be based on available housing, available hotel rooms, available bed and breakfast rentals (AirBnB type homeshares), and housing demand (population). I will trial a random forest and gradient boosting (and possibly a neural network if time is available) to build these models.

This project will produce a presentation with my findings for readers to read and interpret.

The data will be sourced from historical housing data, tourism data, and hotel data on the Hawaii State Government website. The Hawaii State Government website includes data on tourist stays by category for the past several years http://dbedt.hawaii.gov/visitor/tourism/. 

Idea 3: Kaiju Craigslist

If each city in the US were measured against their fighting ability and economic power and then fought in a tiered system, who would win? In this project I will measure the economic power for each city based on their craigslist marketplace's total posts (Height) and the sum of all items sold after removing outliers beyond four standard deviations for its total value (Weight). I will then take the populations of each of these cities to bracket them into their own 'weight classes' then normalize the heights and weights for each city against the population for each bracket. This will be my test data. My training data will be UFC fighting data for fighters based on their height, weight, matches won and matches lost with listed opponent, and home town.

I'm not exactly sure how I would execute the modeling for this yet, but I know I would like to include some score using KNN to account for fighter origin then train a neural network to predict the win or loss for each fighter against the others to identify the 'best fighter'. I would use the test data generated by the cities to determine which Kaiju would win against the others.

This project will output a bracketed infographic for each of the weight classes and their fighting cities.

I will source this data from scraping every city's Craigslist marketplace in the US. I'm still trying to find a UFC fighting database that includes the parameters listed (specifically hometown).
