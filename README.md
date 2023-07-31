# Brainstation_Capstone
Capstone project for Brainstation bootcamp. Anime recommendation systems

Project Name: Anime Recommendation System

Project Description:
This project implements a recommendation system for anime using content-based filtering and collaborative filtering with FunkSVD. The system aims to provide personalized anime recommendations based on user preferences and anime features.

Notebook 1: Content-Based Recommender System and Exploratory Data Analysis (EDA)
- Description:
  This notebook explores the anime dataset, performs data cleaning, and conducts exploratory data analysis (EDA). It then implements a content-based recommender system using the genre column of the dataset.
- Instructions:
  To run the notebook, ensure you have the required libraries installed and execute each cell sequentially. Follow the comments and descriptions in the notebook for guidance.
- EDA Summary:
  The EDA provides insights into the distribution of anime genres, ratings, and user preferences. The content-based recommender system utilizes genre information to suggest similar anime based on user interests.

Notebook 2: Collaborative Recommender with FunkSVD
- Description:
  This notebook focuses on collaborative filtering using FunkSVD, a matrix factorization technique. It creates user-item rating matrices, factorizes them, and predicts missing ratings.
- Instructions:
  Run the notebook by installing the necessary libraries and executing each cell. Refer to the notebook's comments and explanations for assistance.
- Collaborative Recommender Summary:
  The collaborative recommender employs FunkSVD to predict anime ratings for users. It recommends anime based on user-item interactions and preferences.

Dataset:
The dataset used in this project contains user ratings for anime, including columns: user_id, anime_id, and rating. It will be available in the rating.csv file in the project repository.

The second dataset contains the columns, anime_id, name, genre, type, episodes, rating, and members. It will be available in the anime.csv file in the project repository

Installation:
Ensure you have Python 3.x and the following libraries installed: pandas, numpy, scikit-learn. If required, install them using 'pip install <library_name>'.

Usage:
1. Clone the GitHub repository to your local machine.
2. Navigate to the respective notebooks for content-based and collaborative recommenders.
3. Execute the notebooks to analyze data and generate anime recommendations.

Results:
The content-based recommender suggests anime based on genre similarities, while the collaborative recommender predicts user ratings using FunkSVD. Both systems provide personalized anime recommendations based on different approaches.

Future Improvements:
- Incorporate anime overviews or descriptions for better content-based recommendations.
- Implement hybrid recommendation methods to combine content-based and collaborative filtering approaches.

Feel free to explore the notebooks and provide feedback or suggestions for improvement.

Happy anime watching!



