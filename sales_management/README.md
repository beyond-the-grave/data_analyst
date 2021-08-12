# Sales Management Project

Search for the necessary data at the request of the customer.

Used libraries:
  - pandas
  - numpy
  - seaborn
  - itertools
  - matplotlib

# Datasets Information

Dataset -- customers -- includes 18484 entries.
<br />
Dataset -- sales -- includes 58168 entries.
<br />
Dataset -- products -- includes 606 entries.

# Search

  - The data has been processed and cleared of unnecessary columns
  - The percentage of missing information was also checked.
  - Empty values have been partially restored. But some of the empty values had to be removed due to the lack of information on the prodcuts. Attempts were made to search for the same product by name, product id and categories.
  - Some of the empty values in the product value column were restored by finding the average value found using the general category and subcategory of similar products.
  - Datasets were combined with each other through special id keys
  - The analysis revealed the age of the target audience.
  - Cities with the highest demand are identified.
  - Identified products with the maximum demand for the general indicators and in each subcategory separately.
