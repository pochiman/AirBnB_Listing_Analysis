# AirBnB Listing Analysis

## The Situation
You've just been hired as a Performance Analyst for AirBnB, a platform that allows individuals to rent out their homes for travellers.

## The Assignment
As AirBnB has grown in popularity, it has increasingly become the focus of regulations designed to limit the number of properties listed in each city.
You've been asked to analyze Paris listings, with a focus on pricing. Leadership wants a visual summary of factors affecting pricing and whether regulations adopted in 2015 impacted listings in the Paris Market.

## The Objectives
1. Explore and profile the data to correct any quality issues
2. Prepare and reformat the data for visualization
3. Visualize the data and identify key insights and recommendations

## The Data Set

#### Airbnb Listings & Reviews
Airbnb data for 250,000+ listings in 10 major cities, including information about hosts, pricing, location, and room type, along with over 5 million historical reviews.

NOTE: Prices are in local currency

#### Recommended Analysis
1. Can you spot any major differences in the Airbnb market between cities?
2. Which attributes have the biggest influence in price?
3. Are you able to identify any trends or seasonality in the review data?
4. Which city offers a better value for travel?

#### Objective 1: Profile & QA the data
Your first objective is to read in the AirBnB listings data, calculate basic profiling metrics, change column datatypes as necessary, and filter down to only Paris Listings.

* Import/Open the Listings.csv file.
* Cast any date columns as a datetime format.
* Filter the data down to rows where the city is Paris, and keep only the columns ‘host_since’, ‘neighbourhood’, ‘city’, ‘accommodates’, and ‘price’.
* QA the Paris listings data: check for missing values, and calculate the minimum, maximum, and average for each numeric field.

#### Objective 2: Prepare the data for visualization
Your second objective is to produce DataFrames that will be used in visualizations by aggregating and manipulating the listings data in several ways.

* Create a table named paris_listings_neighbourhood that groups Paris listings by 'neighbourhood' and calculates the mean price (sorted low to high).
* Create a table named paris_listings_accomodations, filter down to the most expensive neighborhood, group by the ‘accommodations’ column, and add the mean price for each value of ‘accommodates’ (sorted low to high).
* Create a table called paris_listings_over_time grouped by the ‘host_since’ year, and calculate the average price and count of rows representing the number of new hosts.

#### Objective 3: Visualize the data and summarize findings
Your final objective is to build visuals to show the number of new hosts by year, overall average price by year and neighborhood, and average price for various types of listings in Paris' most expensive neighborhood.

* Create a horizontal bar chart of the average price by neighborhood in Paris, and make sure to add a title and change axis labels as needed.
* Create a horizontal bar chart of the average price by ‘accommodates’ in Paris’ most expensive neighborhood, and make sure to add a title and change axis labels as needed.
* Create two line charts: one showing the count of new hosts over time, and one showing average price. Set the y-axis limit to 0, add a title, and change axis labels as needed.
* Based on your findings, what insights do you have about the impact of the 2015 regulations on new hosts and prices?
* BONUS: Create a dual axis line chart to show both new hosts and average price over time.

#### [Project Link]()