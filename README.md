IMDB Sentiment Analysis using LSTM
This project performs sentiment analysis on the IMDB movie review dataset using a deep learning model built with LSTM layers.

Dataset
IMDB Movie Reviews dataset containing 50,000 labeled reviews (positive and negative).

Objective
To classify movie reviews as positive or negative using a deep learning model.

Steps Performed
Loaded and explored the dataset
Cleaned the text by removing HTML tags, punctuation, and stopwords (excluding negation words like 'not')
Tokenized the reviews and applied padding to equalize input length
Converted sentiment labels to binary values (1 for positive, 0 for negative)
Built a sequential model with an embedding layer, an LSTM layer, and a dense output layer
Trained the model for 5 epochs and evaluated performance on a test set
Tested the model on sample review sentences

Model Details
Embedding dimension: 64
LSTM units: 40
Loss function: Binary Crossentropy
Optimizer: Adam
Accuracy achieved: Approximately X percent (replace with actual value)

Libraries Used
TensorFlow, Keras, NLTK, Pandas, Matplotlib, Seaborn, BeautifulSoup

How to Run
Run the Jupyter or Colab notebook and make sure to mount your Google Drive if using Colab. Update the dataset path accordingly.
