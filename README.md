## Movie Recommendation System ([Demo](https://recommedationmovie.herokuapp.com/))
Movie Recommendation System created using Collaborative Filtering (Website) and Content based Filtering (Jupyter Notebook).Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

### Objectives
  1. To create a movie recommendation system using Collaborative Filtering and machine learning algorithms such as K Nearest Neighbours. 
  2. The system should recommend movies based on the movie title entered by the user. 
  3. The system should also be able to recommend movies on the basis of 'genre only' and 'genre and year' entered. 
  4. The system should apply sentiment analysis to categorize user comments on a particular movie.
  5. Additional Content Based Filtering is performed (can be seen [here](Recommovie_9604_Notebook.ipynb)) using Neural Network to perform Matrix Factorization.

### Dataset can be accessed from [here](https://grouplens.org/datasets/movielens/). 
  For reducing the deployment time, data exploration followed by feature selection is done on the complete dataset.

### Features of the System

1. Recommendations based on a Movie - In this section user enters a movie name and our system based on collabrative filtering will detect the similar movies as per the different features similarity on the basis of the cosine similarity and then give top movies as the result and is displayed on the webpage. There is also sentiment analysis implemented on the reviews of the people regarding a movie whether they are good or bad.
#### Home Page
![image](https://user-images.githubusercontent.com/43933680/140796151-fec85682-9275-44bb-8341-4801b1dbbeac.png)
#### About Movie
![image](https://user-images.githubusercontent.com/43933680/140796312-276601c7-1bce-49da-8b12-84f9b30ee100.png)
#### Recommendations
![image](https://user-images.githubusercontent.com/43933680/140796462-26fe8eef-f993-4b3b-acda-49f15d9557bc.png)
#### Sentiment Analysis
![image](https://user-images.githubusercontent.com/43933680/140796616-edcd35f4-1d10-4d38-ae0d-5def641d80f4.png)

2. Recommendation based on Genres and Year - A user can also search a movie according to genre and year and get top 10 recommendations of the movie as per threshold and with some accuracy and this list will be displayed to the user.

![Movie1](https://user-images.githubusercontent.com/43933680/140795922-bc31dc80-d6c1-4940-a916-b88877c2443a.PNG)

## Similarity Score
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

## How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![image](https://user-images.githubusercontent.com/43933680/140798697-e685f25e-27d2-4eb5-9fa1-6f884d8f42b1.png)
### Tech Stack Used for System
  1. Python
  2. Flask
  3. JavaScript
  4. sklearn
  5. Nltk

### Novelty
- A platform where user can get recommendations in seconds based on the movies preferred by the user and can easily get a summary of the movie with add on of sentiment analysis on the reviews given to the movie.
- User can get recommendations also on the basis of the genres and year preferring to watch in seconds of time get top 10 recommendations with accuracy of 86 percent which saves a lot of browsing time.
- A simple and efficient to use UI/UX has been implemented which makes it easier for the user to access various features in system with ease under a single platform.
 
### Flowchart of Methodology
<div align='center'>
<img src = 'flow-diagram.JPG' height="400px">
</div>

### Deployment
The application deployed can be accessed and tested directly from [here](https://recommedationmovie.herokuapp.com/) or https://recommedationmovie.herokuapp.com/
