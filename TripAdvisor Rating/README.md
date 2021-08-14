# TripAdvisor (TA) Rating Check

Search for the target variable ['rating'] and analyze the effect of other variables on ['rating'].

Used libraries:
  - pandas
  - numpy
  - seaborn
  - requests
  - matplotlib
  - BeautifulSoup (bs4)
  - datetime
  - re
  - sklearn

# Datasets Information

Dataset includes 40000 entries and 10 columns.

* Restaurant_id: Restaurant ID
* City: City 
* Cuisine Style: Cuisine
* Ranking: Restaurant ranking relative to other restaurants in the city
* Price Range: Restaurant prices in 3 categories
* Number of Reviews: Number of reviews
* Reviews: Last 2 reviews and dates of reviews
* URL_TA: The restaurant's page on 'www.tripadvisor.com'. 
* ID_TA: TripAdvisor restaurant ID
* Rating: Rating of the restaurant

# Search

  - Replacing empty values
  - Creation of new indicators: 
    - rank_city_min
    - rank_city_max
    - rank_normal
    - no_cuisine_style
    - cuisine_number
    - cuisine_national
    - no_price
    - words
    - bad_words
    - review_mood
    - review_mood_bad
    - reviews_date
    - review_check
    - reviews_on_website  
  - Creating dummy variables based on cities
  - Feature correlation
  - Creating samples for the test and for verification
  - Showing the Mean Absolute Error
  - Showing the most important features for the model
