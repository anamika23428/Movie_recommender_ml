# Movie Recommender System

## Overview
This project implements a movie recommender system using machine learning techniques to suggest movies based on user preferences. The model leverages a dataset from Kaggle and utilizes various attributes such as genres, keywords, cast, and crew to generate recommendations. 

## Features
- **Content-Based Filtering**: The recommender system uses content-based filtering to suggest similar movies based on their attributes.
- **Data Preprocessing**: The system preprocesses the dataset to handle missing values and transform the relevant columns into a suitable format for analysis.
- **Vectorization**: It employs the Bag of Words method to vectorize the combined attributes of movies.
- **Cosine Similarity**: The model calculates the cosine similarity between movie vectors to identify and recommend similar films.
- **User-Friendly Recommendations**: Users can input the title of a movie to receive recommendations for similar films.

## Dataset
The project uses the following datasets:
- `tmdb_5000_movies.csv`: Contains information about movies, including titles, overviews, genres, and more.
- `tmdb_5000_credits.csv`: Contains credits information, including cast and crew details.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Change directory to the project folder:
```bash
cd <project-directory>
```
3. Install the required packages:
```bash
pip install numpy pandas scikit-learn nltk
```
## Conclusion
This movie recommender system is a simple yet effective way to provide users with personalized movie suggestions. The implementation can be extended by incorporating additional features such as user ratings and advanced filtering techniques.

## Run the Streamlit app:
Launch the Streamlit app by running the following command:
```
streamlit run app.py
```
