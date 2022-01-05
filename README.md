# Content Based Movie Recommendation
### Context:
Online streaming services like 'Amazon Prime', 'Netflix' uses some Recommendation systems to recommend movies to their users based on movie plot, actors, ratings, user preferences.
### Objective
Build a recommendation system that recommends movies to the users based on the movie plot, director, actors and Genre 
### Resources Available
The data is available in the below link
#####
https://query.data.world/s/uikepcpffyo2nhig52xxeevdialfl7
### Details
There are three major steps in this project:
#### Key Words Extraction  
Extract the keywords from the plot and combine information from other attributes like 'actors','Director' and 'Genre' into a single column  
##### 
#### Vectorization
Convert the text data into numerical data. This process is also known as 'Word Embeddings'
#### Cosine similarity
Cosine similarity is a metric used to measure the similarity between the two vectors. Mathematically it measures cosine of the angles between two vectors projected in a dimensional space
![Cosine Formula](https://github.com/VAMSEE92/MovieRecommendationSystem/blob/main/Images/Cosine-Similarity.png)
#### 
We will get a similarity matrix which can be used to predict the similar movies based on the plot of the movie searched
### Value of project
Some platforms allows users to search for movies in anonymous mode. We can recommend movies to those users based on their search without having any user information in our database
#### Disadvantage
The major disadvantage of this method is that user lacks the variety in the suggested movies. He recieves suggetions of the movies having similar plot and genre
### Reference
[Use cases of Recommendation System](https://emerj.com/ai-sector-overviews/use-cases-recommendation-systems/)    
