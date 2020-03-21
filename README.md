# The Problem
Detect and classify questions scraped from the Quora Website as being toxic or not. The provided dataset had the following structure : 
\ 
Training data: 1,306,122 observations
\
Test data: 56,370
\

# My Approach
Use a Word embedding model (GloVe) and apply a bidirectional LSTM to classify a question as being insincere/toxic, after applying nlp data wrangling techniques such as "stop word removal".

# My Result
The F1 score obtained was around 0.547 with the selected LSTM architecture.
