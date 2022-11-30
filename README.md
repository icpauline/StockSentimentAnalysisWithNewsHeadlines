# Stock Sentiment Analysis With NewsHeadlines
## Task : 
  To predict whether the stock price will increase or decrease based on the news headlines
## Dataset:
  The dataset is downloaded from Kaggle
## Approach:
   1. Imported the dataset
   2. Cleaned the text data to hold only alphabets
   3. Converted the text data to lower case to avoid duplication
   4. Joined the text of each feature ( joined the news from various sources)
   5. Created bag of words with 2 neighbors
   6. Trained the data with random Forest Classifier
   7. Did predictions with test data
   8. Created a model with 86% accuracy
