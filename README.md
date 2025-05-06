<div align="center"><h1>IMDB Sentiment Analysis using LSTM</h1></div>

<div ><h3>Overview</h3></div>
<h6>This project focuses on performing sentiment analysis on the IMDB movie review dataset using a deep learning model based on LSTM. The dataset contains 50,000 movie reviews labeled as either positive or negative. 
<div ><h3>Preprocessing</h3></div>
The text data is preprocessed by removing HTML tags, punctuation, and stopwords, while carefully preserving negation words like "not" and "isn't" to retain sentiment context. The cleaned reviews are then tokenized and padded to ensure uniform input length.
<div ><h3>Model Building</h3></div>
A sequential neural network model is built using an embedding layer, an LSTM layer with 40 units, and a dense output layer with sigmoid activation to classify sentiments. The model is trained for 5 epochs using the binary crossentropy loss function and the Adam optimizer. After training, the model is evaluated on a test set, achieving approximately X percent accuracy (replace with actual accuracy). The project also includes predictions on custom review samples to demonstrate its effectiveness.
<div ><h3>Libraries and Language Used</h3></div>
All code is written in Python using libraries such as TensorFlow, Keras, NLTK, Pandas, and BeautifulSoup, and is designed to run smoothly on Google Colab with Drive integration.</h6>
