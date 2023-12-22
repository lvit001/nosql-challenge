# Module 12 Challenge Assignment: nosql-challenge
## [Parts 1 and 2: NoSQL Setup Starter](https://github.com/lvit001/nosql-challenge/blob/main/NoSQL_setup_starter.ipynb)
### Part 1: Database and Jupyter Notebook Set Up
- Successfully imported the establishments.json file using `mongoimport --type json -d uk_food -c establishments --drop --jsonArray Resources/establishments.json` and ensured that the desired database and collection were present.
### Part 2: Update the Database
- Added the new restaurant Penang Flavours into the database and updated its Business Type ID to match others in the system.
- Removed establishments in Dover Local Authority from the database.
- Updated data types for latitude, longitude, and RatingValue.
## Part 3: [NoSQL Analysis Starter](https://github.com/lvit001/nosql-challenge/blob/main/NoSQL_analysis_starter.ipynb)
- Created various queries and converted them into DataFrames to answer four questions about the dataset.
### Question 1: Which establishments have a hygiene score equal to 20?
- Answer: There are 41 establishments in the collection with a hygiene score equal to 20. One of these establishments is called The Chase Rest Home.
- ![image](https://github.com/lvit001/nosql-challenge/assets/140283164/bb9b4d12-e92a-49bf-ada9-5cd897e97547)
### Question 2: Which establishments in London have a RatingValue greater than or equal to 4?
- Answer: There are 33 establishments in London with a Rating Value that is greater than or equal to 4. One of these establishments is called Charlie's.
- ![image](https://github.com/lvit001/nosql-challenge/assets/140283164/718309ae-de0b-4486-83dd-50b92a30c143)
### Question 3: What are the top 5 establishments with a RatingValue rating value of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
- Answer: The top 5 establishments with a Rating Value of 5 and the lowest hygiene scores nearest to Penang Flavours are Volunteer, Plumstead Manor Nursery, Atlantic Fish Bar, Iceland, and Howe and Co Fish and Chips - Van 17.
- ![image](https://github.com/lvit001/nosql-challenge/assets/140283164/97dba2f1-ff04-4a44-9d0d-18ce8aa93a51)
### Question 4: How many establishments in each Local Authority area have a hygiene score of 0?
- Answer: The top 5 Local Authorities in terms of having the most establishments with hygiene scores equal to 0 are Thanet (1130), Greenwich (882), Maidstone (713), Newham (711), and Swale (686).
- ![image](https://github.com/lvit001/nosql-challenge/assets/140283164/ffaeffa7-921d-43cb-a274-7604a1c165aa)
