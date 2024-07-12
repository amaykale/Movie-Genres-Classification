# Movie-Genres-Classification

#Overview
This project aims to predict the genre of a movie based on just 1000 characters of its script. The dataset used for this project is sourced from a Kaggle competition. The script involves data preprocessing, visualization, model building, and evaluation.

#Dataset
The dataset used in this project is from Kaggle: Movie Genres.

Getting Started
Prerequisites
Google Colab
Google Drive
Python libraries: numpy, pandas, matplotlib, seaborn, nltk, sklearn, wordcloud

#Project Workflow
1. Data Exploration
Inspect the dataset structure.Visualize the distribution of movie genres using a count plot.
2. Data Cleaning and Preprocessing
Map genres to numerical values.Remove NaN values and unnecessary columns.
Clean the text by removing special characters, converting to lowercase, removing stop words, and stemming.
3. Visualization
Create word clouds for different genres to visualize common words.
4. Model Building
Create a Bag of Words model using CountVectorizer.Split the data into training and testing sets.Train a Multinomial Naive Bayes classifier.Evaluate the model using accuracy score and confusion matrix.Hyperparameter tuning for the Naive Bayes classifier.
5. Predictions
Define a function to predict the genre of a given script.Load the test dataset and predict genres for random scripts.


#Results
Visualization
Genre distribution plot.Word clouds for Drama, Action, and Comedy genres.
Model Evaluation
Accuracy score of the Naive Bayes classifier.Confusion matrix for detailed performance analysis.Best accuracy after hyperparameter tuning.
