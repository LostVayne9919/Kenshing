
The Kenshing Movie-Recommender-System is a project aimed at creating a personalized movie recommendation system using data from the Kaggle IMDB database and TMDB. The project leverages various Python libraries and tools to preprocess data, build recommendation models, and provide an interactive user interface.

Project Components
Data Sources
Kaggle IMDB Database: Used for fetching movie metadata.
TMDB (The Movie Database): Utilized for retrieving additional movie details and posters.
Tools and Technologies
Python: Core programming language used for data processing and model building.
Jupyter Notebook: Used for exploratory data analysis, data preprocessing, and model development.
Streamlit: Used for building the interactive frontend of the application.
PyCharm: Integrated Development Environment (IDE) used for coding and debugging.
Methodology
Data Preprocessing
Loading Data: The data from Kaggle IMDB and TMDB is loaded into pandas DataFrames.
Cleaning Data: This involves removing missing values, correcting data types, and eliminating irrelevant columns to ensure the data is clean and ready for analysis.
Feature Extraction: Extracting relevant features such as movie genres, cast, director, and keywords.
Vectorization
To facilitate the recommendation system, the text data is converted into numerical format using vectorization techniques:

TF-IDF (Term Frequency-Inverse Document Frequency): Applied to movie overviews to convert text into numerical vectors.
Count Vectorization: Used for categorical features like genres, cast, and crew.
Building the Recommendation System
The recommendation system is built using a content-based filtering approach:

Cosine Similarity: This metric is used to measure the similarity between movie vectors. Movies with higher cosine similarity scores are considered more similar.
Content-Based Filtering: The system recommends movies based on the similarity of content features such as genres, plot summaries, and cast.
Implementation
Jupyter Notebook
Data Preprocessing: Scripts are written in Jupyter Notebook to preprocess the data, including cleaning and feature extraction.
Model Development: The content-based recommendation model is developed and tested within the notebook environment.
Streamlit Frontend
The interactive frontend for the movie recommendation system is built using Streamlit:

User Interface: Users can select a movie from a dropdown menu.
Recommendation Display: Upon selection, the system displays recommended movies along with their posters.
Integration: The frontend communicates with the backend model to fetch and display recommendations in real-time.

Features
Content-Based Recommendations: Recommends movies based on content similarity.
Cosine Similarity: Utilized to measure the similarity between movies.
Interactive UI: Built with Streamlit to provide a seamless user experience.
Data Visualization: Jupyter Notebook is used for data visualization and exploratory data analysis.
Future Work
Hybrid Recommendation System: Combining content-based and collaborative filtering methods.
Improved UI: Enhancing the user interface for better user engagement.
Real-Time Updates: Implementing real-time data updates for recommendations.
Conclusion
The Kenshing Movie-Recommender-System demonstrates the application of data preprocessing, vectorization, and content-based filtering techniques to build an effective movie recommendation system. The project integrates various tools and technologies to provide an interactive and user-friendly experience.


![Screenshot 2024-07-11 203613](https://github.com/LostVayne9919/Kenshing/assets/117676583/d8d3e359-560e-4059-9606-a426b3aac236)

![Screenshot 2024-07-11 203150](https://github.com/LostVayne9919/Kenshing/assets/117676583/25c99cd8-7a48-4917-b008-17b187bdfaa2)

![Screenshot 2024-07-11 203233](https://github.com/LostVayne9919/Kenshing/assets/117676583/e30d9849-c82b-4676-bad1-e19cf977fa4d)
