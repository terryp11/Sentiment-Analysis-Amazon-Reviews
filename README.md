# Sentiment Analysis for Amazon Reviews 

The purpose of this project is to use sentiment analysis on Amazon product reviews to find out if a review is positive or negative with TensorFlow on Google Colab. Some natural language processing techniques used are tokenizing, text vectorization, sequence padding, and Long Short Term Memory (LSTM). The dataset can be found [here](https://www.kaggle.com/datasets/arhamrumi/amazon-product-reviews).

The process involves first getting the data from Kaggle through the Kaggle API, doing some data preprocessing and manipulation (removing non-alphabetical characters, converting label to binary, selecting necessary columns) and doing some EDA. Next the text data was transformed using tokenizing and text vectorization, and was followed by training an LSTM recurrent neural network. After the first model was trained, metrics were plotted and evaluated to see if any changes were needed to improve the model performance. 

After training some more LSTM models, the best performing model had an accuracy of 94% and loss of around 0.16.
