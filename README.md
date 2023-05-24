# Recommendation_engine_using_netflix_prediction
Here I have to go through a large datasets of movies where different users have different opinion. So by using SVD, I have made sure that which movies are frequently watched and how that movie should be recommend to others.
## First step will be upload the file and then I had to go through the dataset for better understanding
** After understanding the datasets, i went to do the next step that is data preprocessing. Where i just removed the null values but not in a normal way as those null values are actually stating the movie id. so i applied a loop and stored the movie id in an array which I converted into a column later on.
After creating the new column named movie id. I simple removed the null values.
But then again i had to go through the reviews that the customer made. And i simply created a bench mark. As i do not want to recommend the low rated movie to the viewers.
After creating the benchmark I simply dropped those values which are not fulfilling the bench mark.
After that my model was ready to perform and I simply converted it into pivot table and applied SVD algorithm to continue training the model and predicting it.
## link of the file
https://drive.google.com/file/d/1cwC0pWb0jPwtsAQGyLjpKQDJUKqOZR-I/view?usp=drive_link
