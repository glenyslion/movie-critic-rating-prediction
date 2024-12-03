# Movie Critic Rating Prediction

## Purpose:
The purpose of this project is to predict the critic rating using a structured data science workflow. It includes stapes like data cleaning, data exploration, data visualization, and data modeling.

The main idea is to use a dataset with movie-related information to figure out factors, such as movie title, movie genre, movie runtime, etc. that affect ratings. The goal is to build a model that can predict the rating based on these features. 

## What is in This Repo:
- READEME.md: Explains what the project is about and what's included in the repository
- raw_movie_data.csv: The raw dataset used for this project.
- movie_data.csv: The cleaned dataset used for the project. If you want to run the code directly to test the machine learning model without going through the data cleaning process, you can use this dataset. I have added a note in the code to show where you can start using this file, right before splitting the train and test datasets.
- movie_rating_prediction_code.ipynb: Notebook file with all the code for the project. In the code, I use data gathering method from postgresql to take the data. I have attached the data in this repo, which is the raw_movie_data.csv. The notebook file will include all of the codes such as the exploratory data analysis, data cleaning, and data modeling.
- requirements.txt: A list of Python packages that you need to install to run the project.
