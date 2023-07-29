# nosql-challenge

This analysis is conducted using MongoDB and PyMongo to explore the establishments' ratings data.

**PART 1: DATABASE AND JUPYTER NOTEBOOK SET UP**

**1. Importing Data**

  The data provided in the establishments.json file was imported into the MongoDB      database.
 
  Database Name: uk_food
  
  Collection Name: establishments

**2. Libraries Used**

  PyMongo: Python library to interact with MongoDB

  Pretty Print (pprint): Used for displaying data in a readable format

**3. Database Confirmation**

**PART 2: UPDATE THE DATABASE**

1. Added New Restaurant

2. Removing Establishments in Dover

3. Data Type Conversions

**PART 3: EXPLORATORY ANALYSIS**

**Question 1**: Establishments with Hygiene Score Equal to 20

Displayed the establishments with a hygiene score equal to 20.

Converted the result to a Pandas DataFrame and displayed the first 10 rows.

**Question 2**: Establishments in London with RatingValue >= 4

Displayed the establishments in London with a RatingValue greater than or equal to 4.

Converted the result to a Pandas DataFrame and displayed the first 10 rows.

**Question 3**: Top 5 Establishments with RatingValue of 5, Sorted by Lowest Hygiene Score

Found the top 5 establishments with a RatingValue of 5.

Sorted the results by the lowest hygiene score, nearest to "Penang Flavours" restaurant.

Compared the geocode to find the nearest locations.

**Question 4**: Number of Establishments with Hygiene Score of 0 in Each Local Authority Area

Displayed the number of establishments in each Local Authority area with a hygiene score of 0.

Sorted the results from highest to lowest and displayed the top ten Local Authority areas.
