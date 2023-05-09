# NoSQL UK Food Hygiene Rating Analysis

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. Food magazine, Eat Safe, Love, hired out to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles. The Jupyter notebook called [NoSQL_setup_starter.ipynb ](https://github.com/adampaganini/NOSQL-Challenge/blob/main/NoSQL_setup_starter.ipynb) containing code that imports the data and sets up and updates the uk_food database. The Jupyter notebook called [NoSQL_analysis_starter.ipynb](https://github.com/adampaganini/NOSQL-Challenge/blob/main/NoSQL_analysis_starter.ipynb) contains code that performs the exploratory analysis queries in the database.

The analysis answers and prints out the following questions about the data:

- Which establishments have a hygiene score equal to 20?
- Which establishments in London have a RatingValue greater than or equal to 4?
- Hint: The London Local Authority has a longer name than "London" so you will need to use $regex as part of your search.
- What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area have a hygiene score of 0?

References:

- UK Food Standards Agency https://www.food.gov.uk (2022). 
- UK food hygiene rating data API: https://ratings.food.gov.uk/open-data/en-GB  Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
