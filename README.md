# Movie-Recommendation-System

Welcome to the Movie Recommendation System ML Project! This project is designed to showcase the implementation of a movie recommendation system using machine learning techniques. This README file will provide you with a comprehensive guide on how to set up and use the recommendation system.

![image](https://github.com/Harshit-3905/Movie-Recommendation-System/assets/89678705/5bd32cd6-8408-4366-8913-5e73511f862c)

## Table of Contents
- Introduction
- Installation
- Algorithm
- Dataset
  
## Introduction

The Movie Recommendation System ML Project is designed to offer users personalized movie recommendations based on their preferences and a selected movie. This system employs machine learning techniques to analyze user behavior and provide accurate and relevant movie suggestions.

When a user selects a particular movie, the recommendation system uses this choice as a starting point. It identifies the characteristics and attributes of the selected movie, such as its genre, actors, director, and plot details. Then, it applies these attributes to find other movies in its database that share similar features.

## Installation

Clone the repository:

```sh
git clone https://github.com/Harshit-3905/Movie-Recommendation-System.git
```

Install the required dependencies:

```sh
pip install -r requirements.txt
```

Download the dataset and place it in the designated directory (see Dataset section).

Start the recommendation system:
```sh
streamlit run app.py
```
If using the web interface:

Navigate to http://localhost:8501 in your web browser.

## Algorithm

The project demonstrates Content-Based Filtering:

Content-Based Filtering: The algorithm used in the Movie Recommendation System recommends movies by analyzing and comparing the attributes and features of the selected movie with those of other movies in the system's database.

When a user selects a particular movie, the recommendation algorithm focuses on understanding the unique characteristics of that movie. These characteristics can include various aspects such as the genre, actors, director, release year, plot summary, and even more detailed attributes like themes, settings, and keywords associated with the movie.

Once the algorithm has extracted and identified these attributes from the selected movie, it starts searching for other movies that share similar attributes. It looks for movies with comparable genres, actors, directors, and other relevant features. This process is often referred to as "content-based filtering."

The goal of this approach is to find movies that have a high degree of similarity to the selected movie in terms of their content. By doing so, the algorithm aims to recommend movies that align with the user's demonstrated interest in the chosen movie. For instance, if the user selects a science fiction movie with a specific actor and theme, the algorithm will search for other science fiction movies with the same actor and theme.

## Dataset
The project uses the TMDB dataset on Kaggle, which provides a collection of movie ratings and information. You can download the dataset from [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) 

![image](https://github.com/Harshit-3905/Movie-Recommendation-System/assets/89678705/85ab935c-1413-4d10-aba3-89a368c17751)


Enjoy using the Movie Recommendation System ML Project!
