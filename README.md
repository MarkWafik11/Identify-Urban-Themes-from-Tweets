# Research Title

Using Tweets to Analyze Urban Topics and Sentiment

## Introduction

This research aims to develop a technique for extracting tweets about city issues, analyzing the sentiment of the extracted tweets, and creating a pipeline to extract useful data about any urban issue from a city. 

## Methodology

Four methods were tested in the relevant tweets extraction phase, and three approaches were tested in the relevant sentiment analysis part. The best method for extracting tweets on urban topics is to search for tweets that include specific keywords like "Traffic", "Green parks", and "Pollution". If the keyword has multiple definitions, use BERT embedding and KNN classifier to filter the tweets by determining the correct meaning of the keyword. To analyze the sentiment of the tweets, the deep learning using BERT technique outperformed the rule-based approach using VADER and the machine learning approach using Random Forest Classifier.

### Pipeline
<img width="723" alt="image" src="https://user-images.githubusercontent.com/86123180/220918344-b9432e41-14e1-4386-a545-10049a82101a.png">


## Files

- `Complete_BERT With Charts.ipynb`: A notebook for performing sentiment analysis on Twitter data using BERT embeddings and visualizing the results using charts and graphs.
- `Double meaning Identification using Bert Embeddings.ipynb`: A notebook for identifying double-meaning words in Twitter data using BERT embeddings and KNN.
- `Extract Tweets.ipynb`: A notebook for extracting tweets related to specific keywords or hashtags using the Twitter API.
- `Random Forest Model and TFID.ipynb`: A notebook for performing sentiment analysis on Twitter data using a random forest model and TF-IDF vectorization.
- `Topic Modelling For Tweets.ipynb`: A notebook for identifying and analyzing topics in Twitter data using topic modeling techniques such as Latent Dirichlet Allocation (LDA).

## Usage

To use the pipeline for extracting tweets and analyzing sentiment on urban topics, follow these steps:

1. Run `Extract Tweets.ipynb` to extract tweets related to specific keywords or hashtags using the Twitter API.
2. Run `Double meaning Identification using Bert Embeddings.ipynb` to identify double-meaning words in the extracted tweets using BERT embeddings and KNN.
3. Run `Complete_BERT With Charts.ipynb` to perform sentiment analysis on the extracted tweets using BERT embeddings and visualize the results using charts and graphs.

## Conclusion

Using tweets to capture citizens’ feelings about various aspects and topics relating to the city’s quality of life, services, and events can provide meaningful insights into how those citizens feel about these issues. With the pipeline developed in this research, we can extract valuable data about any urban issue from a city by analyzing tweets on specific keywords related to the topic of interest.

