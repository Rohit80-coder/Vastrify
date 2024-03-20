# Vastrify Clothing Recommendation System






Vastrify is a clothing recommendation system designed to provide personalized clothing suggestions based on user preferences and various other factors. This repository contains the source code and resources for the Vastrify Clothing Recommendation System.

# Dataset Preparation

To train the recommendation system, a dataset of various clothing items for men and women was prepared through web scraping from e-commerce websites like Flipkart and Amazon. The dataset includes textual descriptions of the clothing items.

## Data Preprocessing

Before training the recommendation system, the textual data from the dataset undergoes several preprocessing steps:

1. Convert the text to lowercase.
2. Remove stopwords to eliminate common words that do not carry much meaning.
3. Tokenize the text to split it into individual words.
4. Lemmatize the words to reduce them to their base form.
5. Remove special characters to clean the text further.

These preprocessing steps help to normalize the textual data and remove noise.

## Writing Recommendation Function

The recommendation function in the code performs the following steps:

1. Clean the text input given by the user and add it to the dataset.
2. Convert the textual descriptions in the dataset to vectors using the bag-of-words technique.
3. Calculate the similarity score between the user input vector and the vectors of clothing items using cosine similarity.
4. Recommend the top clothing items with the highest similarity scores to the user.

These steps ensure that the recommendation system provides relevant clothing suggestions based on the user's input.


## Features

- Personalized clothing recommendations
- User preference customization
- Machine learning algorithms for enhanced recommendations



