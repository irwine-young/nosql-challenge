# nosql-challenge
Module 12 Challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them afood hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some ofthe ratings data in order to help their journalists and food critics decide where to focus future articles.

Part 1: Database and Jupyter Notebook Set up
- Import establishment.json from terminal
- Create instance for the Mongo Client
- Confirm that the database has been created and data loaded properly
- Assign "establishment" collection to variable to prepare the collection for use

Part 2: Update the Database
- Add new restaurant, Penang Flavours, to the database
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields
- Update the new restaurant with the BusinessTypeID found from above
- Delete all "Dover" establishment
- Convert Latitude and Longitude from string to decimal numbers
- Convert RatingValue from string to integers

Part 3: Exploratory Analysis
Using the data exploratory analysis to answer the following questions
- Which establishments have a hygiene score equal to 20?
- Which establishments in London have a RatingValue greater than or equal to 4?
- What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- How many establishments in each Local Authority area have a hygiene score of 0? Sort the results fromhighest to lowest, and print out the top ten local authority areas.

References
- UK Food Standards Agency (https://www.food.gov.uk/) (2022). UK food hygiene rating data API.
- https://ratings.food.gov.uk/open-data/en-GB (https://ratings.food.gov.uk/open-data/en-GB). Contains public sectorinformation licensed under the Open Government Licence v3.0 (https://www.nationalarchives.gov.uk/doc/opengovernment-licence/version/3/) Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072,