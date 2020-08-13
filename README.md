# DisasterTweetPrediction
Entry level submission for Kaggle Real or Not? NLP With Disaster Tweets Competition which does some simple data exploration and preprocessing as well as basic classification.

Note this project relies on GloVe twitter embeddings, which can be found here: https://nlp.stanford.edu/projects/glove/. 

Specifically download the "glove.twitter.27B.zip" file from the site and move the glove.twitter.27B.200d.txt file into the data folder.

Additionally another note is that the cell which does the grid search is computationally heavy, so the random forest with the best hyperparameters is provided in pickle form, and 
can be loaded in place of training the model yourself.
