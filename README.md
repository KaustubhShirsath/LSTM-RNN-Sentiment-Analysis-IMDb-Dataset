# LSTM-RNN-Sentiment-Analysis-IMDb-Dataset

So, here we will build a classifier on IMDB movie dataset using a Deep Learning technique called RNN.

I’m outlining a step-by-step process for how Recurrent Neural Networks (RNN) can be implemented using Long Short Term Memory (LSTM) architecture:

1. Load in and visualize the data
2. Data Processing — convert to lower case
3. Data Processing — Remove punctuation
4. Tokenize — Create Vocab to Int mapping dictionary
5. Tokenize — Encode the words
6. Tokenize — Encode the labels
7. Analyze Reviews Length
8. Removing Outliers — Getting rid of extremely long or short reviews
9. Padding / Truncating the remaining data
10. Training, Validation, Test Dataset Split
11. Dataloaders and Batching
12. Define the LSTM Network Architecture
13. Define the Model Class
14. Training the Network
15. Testing (on Test data and User- generated data)
16. Inference
