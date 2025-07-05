
# 📊 Sentiment Analysis with LSTM

A deep learning model for sentiment analysis on IMDB movie reviews using LSTM networks.

## Features

- Text classification for positive/negative sentiment  
- LSTM neural network architecture  
- Keras/TensorFlow implementation  
- Data preprocessing with tokenization and padding  
- Model evaluation metrics  

## Dataset

This project uses the [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) from Kaggle containing:  
- 50,000 movie reviews  
- Balanced dataset (25k positive, 25k negative)  
- Text preprocessing including HTML tag removal  

## Setup Instructions

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
2. **Download dataset**
   ```bash
   kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
   unzip imdb-dataset-of-50k-movie-reviews.zip
   ```

3. **Run the notebook**
   ```bash
   jupyter notebook Sequence_Modeling_for_Sentiment_Analysis_on_IMDB_using_LSTM.ipynb
   ```
Test different Plant images and have fun!
