# Predict Next Safety Incident
Description : Can we leverage NLP techniques to tap into the potential of text data ? Can we predict next accident that is going to happen, and try to avoid it ? Can we save members from injuries and probably save a few valuable lives ?

Tech stack used : Python packages - numpy, pandas, matplotlib, nltk, gensim, pyLDAvis

Keywords : Visualizations, NLP, Text data, Lemmatization,Tokenization, Word cloud, High frequency words, N-grams, Text topics, Topic modeling, LDA, Bag of words, TF-IDF

Training Data : Past Safety incidents

Test Data : Current hazards (potential safety incidents) recorded 

Methodology : 

1) Pre-processing and Visualization of Text data field in training data set 
2) Feature extraction and Text Modeling using NLP techniques on training data
3) Pre-processing and applying the model on test dataset
4) Fetch the observation with maximum coherency score in test data set. This hazard has the maximum similarity to a past safety incident.
5) Action needs to be taken for all hazards with high scores to avoid recurrence of similar accidents in future.
