# Text-Summarization

The objective of this project is to build a seq2seq model that can create relevant summaries. The dataset contains above 500,000 reviews, and is hosted on [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews). It's too large to host here, it's over 300MB.

To build model use a two-layered bidirectional RNN with LSTMs on the input data and two layers, each with an LSTM using bahdanau attention on the target data.
This model uses [Conceptnet Numberbatch's](https://github.com/commonsense/conceptnet-numberbatch) pre-trained word vectors. 
