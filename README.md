# IMDB-sentiment-analysis

This project performs sentiment analysis on movie reviews from the IMDb dataset using deep learning models such as LSTM, GRU, Bidirectional RNNs and BERT.
The goal is to classify reviews as positive or negative and compare the performance of different neural network architectures.

## Dataset

The models are trained on the IMDb Movie Reviews Dataset, which contains 50,000 movie reviews labeled as positive or negative sentiment.
The dataset is widely used for benchmarking sentiment analysis models in natural language processing.

### The following models were implemented and compared:

1. Single LSTM (baseline) - 87.5
2. Stacked LSTM - 88.8
3. Bidirectional LSTM - planned
4. Stacked GRU - planned
5. Bidirectional GRU - planned
6. CNN + LSTM hybrid - Planned
7. BERT - Planned

### Pipeline:
1. Data preprocessing
2. Tokenization
3. Sequence padding
4. Model training
5. Evaluation

Review: "This movie was absolutely fantastic."

Prediction: Positive

Review: "The plot was boring and predictable."

Prediction: Negative


## Results

Model performance comparison is documented in results.md.


