# nosql-challenge
## Module 12 Challenge
For this project I used PyMongo and Jupyter Notebook to evaluate the data of various establishments across the United Kingdom. You can view the code for Part 1 and Part 2 [here](https://github.com/isabellajade/nosql-challenge/blob/main/NoSQL_setup_starter.ipynb). To view the code for Part 3, click [here](https://github.com/isabellajade/nosql-challenge/blob/main/NoSQL_analysis_starter.ipynb). 

## Part 1 | Set Up
In order to set up for this project I imported the JSON file with the data used for this project to MongoDB from my terminal. I then used PyMongo, Pandas, Jupyter Notebook, and MongoDB Compass to help me with my analysis.

## Part 2 | Updating the Database
With PyMongo I updated the data by:

- Adding a new restaurant to the database
- Updating the BusinessTypeID for a new restaurant
- Removing all establishments within the Dover Local Authority
- Changing the datatype of longitude and latitude to decimal numbers

## Part 3 | Exploratory Analysis
For each of the questions below I displayed the number of documents contained in the results, used pprint to display the first document, converted the results into a Pandas DataFrame, printed the number of rows in the DataFrame, and displayed the first 10 rows.

The questions answered with my analysis were:

1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.


