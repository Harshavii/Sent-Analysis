# Sent-Analysis

### Problem Statement:
Transformers Architecture

### Solution: 
GitHub: [Link](https://github.com/Harshavii/Sent-Analysis)

### Dataset:
Used “Twitter US Airline Sentiment” taken from Kaggle. It was originally scraped on February, 2015 and contributors categorized the tweets in positive, negative, and neutral tweets. 
[Source link](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment/)

### Data pre-processing:
For this project, considered only two relevant columns which are ‘text' and 'airline_sentiment' from the dataset. Used sklearn library from splitting the data into training and testing.

### Model Architecture:
Used a transformer-based BERT model and TensorFlow to implement sentiment analysis. Text sequences are processed using a pre-trained BERT tokenizer and model, which perform tokenization and padding. It builds a neural network model with BERT embeddings, uses the learned data to train it for sentiment analysis, then assesses its performance using the test data to produce an accuracy metric.

### Model Evaluation:
ReLU is the activation function used for the dense layer, and sigmoid is the one utilized for the output layer. Utilized  'Adam' as the optimizer. Used a batch size of 16 and 5 epochs to train the model. The final accuracy that had been achieved was 0.8432, or 84%.


