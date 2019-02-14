# Trending-Diets-of-Twitter-Users in the US in the Last 30 Days


### Objective

* Where Were Twitter Hashtags for Keto, Plaeo, Weight Watchers and Whole30 Diets Trending in the US Within the Last 30 Days?
* Start Date: Feburary 14, 2019

### Tools

1. Twitter API
2. Libraries: Pandas, NumPy, Matplotlib, Requests, JSON, Pprint, Tweepy, Geocoder, Gmaps
3. Google Maps to create the Heatmaps

### Roadblocks

1. Maxed out API requests for API key
2. Locations were inaccurate (ex: State, Country instead of City, State, and obscure locations, ex: "from the sports grille")
3. Trying to grab the latitude and longitude coordinates by using the Google Maps API, but then found the Geocoder Library more useful
4. Number of locations and weights had to match to build heatmap
5. Only allowed to pull 100 results, and only 70-75 results per diet had location values

### Conclusions

Using Twitter to gather data on tweets based on location in regards to the 4 types of diets fads that were trending, we found:
1. Keto was trending highest in CA. When plotting by cities in CA, we noticed that SF and LA had a cluster of hits. These metros are more tech-savvy as compared to other cities in CA, which likely lead to more Twitter activity.
2. Paleo was heavily trending in CA, NY, and WA. In this case, WA seems like an outlier against the large populations of CA and NY.
3. Weight Watchers was heavily trending in TX and CA. This could be because these two states are highly populated compared to the other 48 states.
4. Whole30 was trending higher in CA, WA and MO. It seems like MO is an outlier given its small population.
