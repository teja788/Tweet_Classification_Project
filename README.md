# Tweet_Classification_Project

## This Repository is to Showcase sample of my code for NLP Problems.

Data is from Kaggle **Real or Not? NLP with Disaster Tweets** competition.

## Model Methodology

1) Load Datasets and required packages (Keras, Tensorlow, Clean-Text, matplotlib, numpy, pandas).
2) Clean text using the loaded packages (changing to lower case, remove line breaks, remove punctuation.
3) Tokenize the words, pad sequences.
4) Download Glove Embeddings, Create embedding matrix from the downloaded weights.
5) Create Network Architecture using Sequential layer, Bi-Directional LSTM, GRU layers (Architecture is arrived at after many iterations.)
6) Fit the model (I used TPU's provided by Kaggle)
7) Predict on test data.

## Some Learnings

1) Network with Glove embeddings gave much better accuracy than normal networks.
2) Cleaning of text has impact on accuracy
3) Bi directional LSTM and GRU gave better results than uni directional ones.
