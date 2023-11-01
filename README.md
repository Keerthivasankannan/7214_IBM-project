# 7214-IBM-Project

# Problem Statement: A Brief
The goal of the project is to create a machine learning model that can forecast the IMDb scores of movies on a platform like Films. 
It aims to do this by analysing various movie attributes such as genre, premiere date, runtime, and language. 
The primary objective is to build a model that can reliably predict a movie's popularity, making it easier for users to find highly-rated films that align with their tastes.
To accomplish this, the project will involve tasks like preparing the data, creating new features from the existing ones, choosing an appropriate machine learning model,
training it on the data, and assessing its performance.

# Dataset Details
Here are some columns from the Netflix original films dataset that we use for our project to predict IMDb scores:
•	Title: The title of the film.
•	Genre: The genre of the film.
•	Premiere date: The date on which the film was released on Netflix.
•	Runtime: The length of the film in minutes.
•	IMDB score: The film's rating on IMDb.
•	Language: The primary language of the film.
Here are the strategies we will be using for the different columns to predict IMDb scores:
Genre: Create a feature that represents the genre of the film. This could be a one-hot encoded feature, where each genre has its own column. 
Runtime: Use the runtime of the film as a feature. This feature could be normalized to a scale of 0 to 1.
IMDB score: Use the IMDB score of the film as the target variable for your machine learning model.


# Implementation Steps

1. Data Preprocessing: 
Cleaning and transforming the dataset, handling missing values, and encoding categorical variables.
2. Feature Engineering: 
Create new features, derive meaningful insights, and perform feature scaling and normalization.
3. Model Selection: 
Choose between Linear Regression, Lasso, Ridge, Gradient Boosting, Neural Networks, or a combination of these models based on cross-validation results.
4. Training and Evaluation: 
Train the selected models and evaluate their performance using metrics like Mean Squared Error (MSE), R-squared, and cross-validation techniques.
5. Innovation Integration: 
Implement the proposed innovations, such as feature importance analysis for Gradient Boosting and embedding layers for Neural Networks.
6. Hyperparameter Tuning: Optimize the hyperparameters of Gradient Boosting and Neural Networks to maximize prediction accuracy.
7. Model Ensemble: 
Consider ensemble techniques to combine the strengths of various models, if necessary.
8. Monitoring and Maintenance: 
Regularly monitor the model's performance and update it with new data as IMDb scores change.


# To run the project

1. Load the dataset and convert it into the data frame
2. All the preprocessing, model training, and evaluation should be executed next.
3. The visualization elements should be executed next for a better understanding of our model.
4. At last the user can give inputs of movie name, genre, runtime, language and premiere date as input.
5. The predicted IMDB Score will be given as output.
