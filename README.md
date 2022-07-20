![MyNextBook](https://user-images.githubusercontent.com/87125043/179919337-6b63e003-6f23-4849-a3a9-f74b4276e8e0.jpg)

# Book Recommendation System

•	During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys.

•	In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries).

•	The main objective of this project is to create a machine learning model to recommend relevant books to users based on popularity and user ratings.

•	Since, here we are trying to recommend books to users based on popularity or ratings the user gave previously, I have tried different models like Popularity based recommender system and Collaborative filtering to build a book recommendation system.

•	We are using Book-Crossing dataset to train and test our recommendation system. The dataset comprises of three .csv files: Books, Users and Ratings.

•	After loading our dataset and importing all the necessary libraries, we perform EDA on features to get insights from the data. 

•	In EDA we found that Majority of the readers were of the age bracket 20–35 and most of them came from North American and European countries namely USA, Canada, UK, Germany and Spain. Top rated books were essentially novels. Books like Harry Potter series, Lord of the Rings series, The Lovely Bone, etc.

•	After that I performed Feature engineering and Data cleaning on the Year-Of-Publication column in books dataset to handle misrepresented data.

•	Lastly, I build the recommendation system by using Popularity based approach model and Collaborative Filtering Model.

•	In Popularity based approach I have sorted top 50 books from the dataset on the basis of number of ratings received (more than 250) and highest average rating.

•	In Collaborative Filtering model, with the help of Cosine Similarity measurement, I have created the correlation matrix considering only those books which have total ratings of more than 50 and only those Users who have rated more than 200 books. For the input book using the correlation matrix, the model recommends top 4 books.

Webpage: https://book-recommendersystem.herokuapp.com/ 
