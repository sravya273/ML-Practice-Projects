## Movie-Movie Recommendation

#### DESCRIPTION
Consider the ratings dataset below containing data on UserID, MovieID, Rating, and Timestamp. 
Each line of this file represents one rating of one movie by one user and has the following format: UserID::MovieID::Rating::Timestamp 
Ratings are made on a 5 star scale with half star increments.   
UserID: represents the ID of the user   
MovieID: represents the ID of the movie  
Timestamp: represents seconds from midnight Coordinated Universal Time (UTC) of January 1, 1970.

#### Objective: Predict a movie-movie recommendation model.

#### Steps involved:  
1. Import libraries and dataset  
2. Identify total number of users and movies
3. Split the data into training and test sets
4. Populate train test matrices with ratings
5. Create cosine similarity matrices for users and movies
6. Perform predictions
7. Find the best model
