This project performs sentiment analysis on a dataset of restaurant reviews using Natural Language Processing (NLP) techniques and machine learning.The dataset used is "Restaurant_Reviews.tsv", containing 1000 restaurant reviews labeled as positive or negative.
## Steps

1. **Data Cleaning and Preprocessing:**
   - Remove non-alphabetical characters.
   - Convert text to lowercase.
   - Tokenize the text into words.
   - Apply stemming using PorterStemmer.
   - Remove stopwords, excluding "not".

2. **Feature Extraction:**
   - Create a bag-of-words model using CountVectorizer with a maximum of 1500 features.

3. **Model Training:**
   - Split the dataset into training (80%) and testing (20%) sets.
   - Train a Gaussian Naive Bayes classifier on the training data.

4. **Prediction and Evaluation:**
   - Predict sentiments on the testing data.
   - Generate a confusion matrix to evaluate the model's performance.
   - Calculate the accuracy score.

## Libraries Used

- NumPy
- Matplotlib
- Pandas
- re
- nltk
- scikit-learn

## How to Run

1. Make sure you have the necessary libraries installed:
