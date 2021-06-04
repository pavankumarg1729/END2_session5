# END2_session5

# There are 2 parts to this assignment in this session

1. Sentiment classification using LSTM after text data augmentation techniques

2. Sentiment classification on Stanford Sentiment Tree bank


# Sentiment classification using LSTM after text data augmentation techniques

- Implemented data augmentation techniques like

    - Random Swap
    - Random delete
    - Google back translate
  

#  Sentiment classification on Stanford Sentiment Tree bank

- Standford Sentiment Treebank is imdb movie review data with 5 classes (SST5)
    - Strongly negative
    - Weakly negative
    - Neutral
    - Weakly positive
    - Strongly positive

    - Process 
      - Have used "Flair" NLP package based on python to train the SST5 data set
      - Used LSTM, RNN with Glove and Flair word and document embeddings
      - The train, val and test accuracies are close to 45% with and without data 
      - augmentation techniques
      - Further to improve to SOTA levels, need sentence embedding instead of word embedding
  
