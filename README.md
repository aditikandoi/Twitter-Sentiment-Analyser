# Twitter-Sentiment-Analyser
A web app which can be used to analyze users' sentiments across Twitter hashtags. Its created using Django and uses an LSTM model trained on the Kaggle Sentiment140 dataset and served as a REST API to the ReactJS frontend.

The server pulls tweets using tweepy and performs inference using Keras. It also pulls data from the Wikipedia API based the hashtag chosen to display a short description. As part of the analysis, I also added few examples of the tweets and their predicted sentiments. A kernel for another sentiment classification using a CNN + 1D pooling can be found here
