# nosql-challenge

![image](https://github.com/user-attachments/assets/ad50c4b7-6f52-4559-a75f-ea8be6b623f9)


For Module 12 challenge we used nosql database mongodb to setup and analyze the data byThe UK Food Standards Agency which evaluates various establishments across the United Kingdom, and gives them a food hygiene rating.We evaluated some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

 First we imported the data provided in the establishments.json file from the Terminal.WE  Named the database uk_food and the collection establishments and copied the text we used to import your data from  Terminal to a markdown cell in the notebook.

Within  notebook,we  imported the libraries we need: PyMongo and Pretty Print (pprint).

Created an instance of the Mongo Client.

Confirmed that we created the database and loaded the data properly:


 Updated the Database with ann exciting new halal restaurant just opened in Greenwich, but hasn't been rated yet. The magazine has asked us to include it in our analysis.
we converted some number values which were stored as strings to decimal and integers.

Then we did an exploratory analysis for some specific questions:
1. Which establishments have a hygiene score equal to 20?

2. Which establishments in London have a RatingValue greater than or equal to 4?


3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?


4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.


