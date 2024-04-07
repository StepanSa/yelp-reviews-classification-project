# Yelp Reviews Classification using Natural Language Processing
This project is part of the "Python for Data Science and Machine Learning Bootcamp" on Udemy. In this project, we explore Natural Language Processing (NLP) techniques to classify Yelp reviews into 1-star or 5-star categories based on their text content.

## Dataset
The dataset used for this project is the Yelp Review Data Set obtained from Kaggle. Each observation in this dataset represents a review of a particular business by a specific user. The dataset includes the following columns:

* stars: The rating given by the reviewer to the business (1 through 5).
* text: The content of the review.
* cool: The number of "cool" votes received by the review.
* useful: The number of "useful" votes received by the review.
* funny: The number of "funny" votes received by the review.

## Project Workflow
### 1. Exploratory Data Analysis (EDA):

* Histograms of text length based on star ratings.
* Boxplot of text length for each star category.
* Countplot of the number of occurrences for each star rating.
* Analysis of mean values of numerical columns using groupby.
* Correlation analysis among numerical features using a heatmap.

### 2. NLP Classification Task:

* Creation of a new dataframe containing only 1-star and 5-star reviews.
* Transformation of text data into numerical features using CountVectorizer.
* Splitting the dataset into training and testing sets.

### 3. Training a Model:

* Training a Multinomial Naive Bayes classifier on the training data.

### 4. Predictions and Evaluations:

* Making predictions on the testing data.
* Evaluating the model performance using confusion matrix and classification report.

### 5. Using Text Processing:

* Creating a pipeline incorporating CountVectorizer, TF-IDF Transformer, and Multinomial Naive Bayes classifier.

### 6. Predictions and Evaluation with Pipeline:

* Using the pipeline to preprocess text data and make predictions.
* Evaluating the model performance with TF-IDF preprocessing.
