# Final Project Data Science

I. Introduction



1.1 Background:

Being one of the world capitals of arts, culture, gastronomy and fashion, millions of travelers visit Paris each year to explore the city's cultural attractions. There are a lot of travel agencies that offer various deals on flights, hotel stays and rental cars. Also, there are people who prefer not to work with a travel agency and who want to plan the holiday on their own.

1.2 Problem:

In this scenario, the business problem is: How could I provide support to different stakeholders (people or tourism agencies) in choosing the best surrounding facilities near the hotel? Where would I recommend that is the best place to stay considering the surrounding near the hotel?
To solve this business problem, we will use Foursquare location data and we will create machine learning models to cluster Paris neighborhoods in order to recommend profitable hotels based on different surrounding facilities such as restaurants, stores, attractions and so on.

1.3 Interest:

Through these models the tourists will have a wide range of recommendations for accommodation, they will know all the facilities to enjoy on vacation, will receive a wide range of options and, in this way, they will know exactly what hotel is the most suitable for them.


II. Data selection


To realize that, there was used data from 2 different sources. Data about hotels from Paris was taken from booking. It was collected information related to postal code, name of the hotel, address, latitude, longitude and average price per night and it was integrated into a database which contain 71 observations about 71 hotels from Paris. For a better analysis it was selected data about hotels from different areas and with different facilities of Paris but it was collected only the top hotel which means the hotel that received the greatest note by the customers.

The second source used is Foursquare location data in order to explore and target recommended locations across different venues. 
The final database which combine Foursquare location data and Paris hotels data will be used to develop our machine learning models and to cluster Paris areas neighborhoods in order to provide the best recommendations in choosing a hotel based on a wide range of surrounding facilities.


III. Methodology: 


As a database, I used GitHub repository in my study. My master data which has the main components Postal code, Address, Average price per night, Latitude and Longitude. 

There was use python folium library to visualize geographic details of Paris and a map of Paris with all the hotels address superimposed on top was created. I used latitude and longitude values to obtain the map. 

Finnaly, there was used k-means Clustering to cluster hotels in Paris to see how they belong and based on that we got useful information regardin the venues and which hotel to choose based on price and top venues. 

IV. Result Section:

It was observed what venues are available near each hotel. Hotels that are in the center of Paris have the most facilities. Compared to the hotels located further from the center. There is a huge variety of facilities from local and foreign restaurants, airport services, art gallery, art museum, bus and trail station, shops, church, comedy club, grocery stores, market to  medical center, museum, nightclub, park, theater and many others. Hotels from central area have in particular facilities, such as: local and foreign restaurants, bistro, cafe, bar, bakery, stores, plaza, lounge, along with the biggest tourist attractions: The Eiffel Tower, Louvre Museum, Notre Dame de Paris, Pantheon, Arc de Triomphe.
The map and the last 7 tables show the cluster grouping mode. The clusters were grouped by similarities. It can be noticed that hotels with common venues and many tourism attractions are grouped together, compared with hotels located in less crowded areas and with fewer facilities and venues. The largest cluster, the last one, contains the most number of hotels. They have the largest number of facilities and benefit of many tourist attractions.

