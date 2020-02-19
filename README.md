# Zomato_Blore

## Zomato Dataset

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the aggregate rating of each restaurant, the establishment of different types of the restaurant at different places, Bengaluru being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world. With each day new restaurants opening the industry hasn’t been saturated yet and the demand is increasing day by day. In spite of increasing demand, it however, has become difficult for new restaurants to compete with established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves. With such an overwhelming demand for restaurants, it has therefore become important to study the demography of a location. What kind of food is more popular in a locality. Do the entire locality love vegetarian food. If yes then is that locality populated by a particular set of people for eg. Jain, Marwaris, Gujaratis who are mostly vegetarian. This kind of analysis can be done using the data, by studying different factors.

## Dataset -Columns
•	URL - contains the URL of the restaurant in the zomato website
•	address - contains the address of the restaurant in Bengaluru
•	name - contains the name of the restaurant
•	online_order - whether online ordering is available in the restaurant or not
•	book_table - table book option available or not
•	rate - contains the overall rating of the restaurant out of 5
•	votes - contains the total number of rating for the restaurant as of the above-mentioned date
•	phone - contains the phone number of the restaurant
•	location - contains the neighborhood in which the restaurant is located
•	rest_type  - restaurant type
•	dish_liked - dishes people liked in the restaurant
•	cuisines - food styles, separated by a comma
•	approx_cost(for two people) - contains the approximate cost for a meal for two people
•	reviews_list - list of tuples containing reviews for the restaurant, each tuple consists of two values, rating and review by the customer
•	menu_item - contains a list of menus available in the restaurant
•	listed_in(type) - type of meal
•	listed_in(city) - contains the neighborhood in which the restaurant is listed

## Objective-To make a prediction about the expected rating of a restaurant to be opened with given cuisines and menu.  

## RESULT

•	Model: RANDOM FOREST - 91% accuracy
•	Model: Decision Tree - 87% accuracy
•	Model: Knn - 72%  accuracy


