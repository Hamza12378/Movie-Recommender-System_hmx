# Movie-Recommender-System_hmx
Python Framework Frontend API

Updated version of this application can be found at: https://github.com/Hamza12378/Movie-Recommender-System_hmx

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

**Note:** The project includes a Jupyter Notebook source file, which you can run to generate the required .pkl files. These files are not included in the repository due to their size, but you can easily create them by following these steps:

1. Clone or download the repository to your local machine.
2. Open the Jupyter Notebook source file (e.g., "Movie_Recommender_System.ipynb").
3. Execute the notebook by running it cell by cell.
4. At the end of the notebook, you will find commands that create the necessary .pkl files.
5. Once you have generated the .pkl files, you can use them with the Streamlit app to enjoy personalized movie recommendations.

This note provides clear instructions to users on how to generate the .pkl files when they run the Jupyter source file. It ensures that users have the necessary data files for the Movie Recommender System.



`import pickle
pickle.dump(new,open('movie_list.pkl','wb'))
pickle.dump(similarity,open('similarity.pkl','wb'))
pickle.dump(new.to_dict(),open('moviedict.pkl','wb'))`





<img width="684" alt="Screenshot 2023-07-18 122427" src="https://github.com/Hamza12378/Movie-Recommender-System_hmx/assets/111439617/35b32b83-7845-45ea-a5d0-e89d2182586d">
<img width="684" alt="Screenshot 2023-07-18 122500" src="https://github.com/Hamza12378/Movie-Recommender-System_hmx/assets/111439617/0fe4f866-6261-48a5-a2a5-40cce14cee31">

