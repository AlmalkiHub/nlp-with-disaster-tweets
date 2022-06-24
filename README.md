# NLP with Disaster Tweets Project

I have run multiple NLP experiments to predict whether a given tweet is about a real disaster or not.

### Dataset:

`train.csv` - the training set <br>
`test.csv` - the test set <br>
`sample_submission.csv` - a sample submission file in the correct format <br>

Columns:

id - a unique identifier for each tweet
text - the text of the tweet
location - the location the tweet was sent from (may be blank)
keyword - a particular keyword from the tweet (may be blank)
target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

### Modelling Part
I have conducted the following series of experiemnts:
* **Model 0**: Naive Bayes (baseline)
* **Model 1**: Feed-forward neural network (dense model)
* **Model 2**: LSTM model
* **Model 3**: GRU model
* **Model 4**: Bidirectional-LSTM model
* **Model 5**: 1D Convolutional Neural Network
* **Model 6**: TensorFlow Hub Pretrained Feature Extractor
* **Model 7**: Same as model 6 with 10% of training data
