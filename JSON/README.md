# Recipe

Data manipulation to work with a JSON file and create a DataFrame from a JSON file.

Used libraries:
  - pandas
  - json
  - pprint from pprint

# Dataset Information

The dataset recipe includes 39774 dishes. Each with a special ID - ['id'],
info about the cuisine - ['cuisine'] and a list of ingredients - ['ingredients'] that were used in the preparation of the dish.

# Search

JSON:
  - Search cuisine or ingredients by id
  - Serach the number of cuisines with to methods (creating a list of unique cuisine and run through a cicle or using set())
  - Serach the number of ingredients using set()
  - Assessing the popularity of ingredients
  - Search the most common ingredient in meals
  - Serach the number of ingredients used just in one dish

DataFrame:
  - Creating a function to fill each cell in the ingredients columns 1 - Yes, 0 - No (see if a specific dish inculdes the ingredient)
  - Change the information in the ingredient column to show the amount of ingredients included in the dish
  - Save the DataFrame as a CSV file and remove the index, so by opening the CSV file there won't be an extra column
 
Serialization:
  - Remade the JSON file from the CSV file
  - Storage the ids and ingredients names
  - Create a function to search for the ingredient included in the dish
  - Storage the result in the blank list - new_recipe
