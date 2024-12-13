# Sentiment Analysis with BERT

This repository contains a sentiment analysis application that utilizes 
BERT (Bidirectional Encoder Representations from Transformers) to classify 
movie reviews from the IMDb dataset as positive or negative. 
The project demonstrates how to preprocess text data, train a BERT model, 
evaluate its performance using various metrics.

## Installation
To set up the environment and install the required packages, run the following commands:
``` 
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install transformers datasets scikit-learn
```

## Usage
Clone the repository:
```
git clone https://github.com/riishabhraj/sentiment-analysis-using-BERT.git
cd sentiment-analysis-using-BERT
```

## Run the Jupyter Notebook:
Open the sentiment_analysis_using_BERT.ipynb file in Jupyter Notebook or Google Colab.

## Predict Sentiment:
Use the provided functions to predict sentiment for new text inputs.

JSON Configuration Example
Here is an example of how you can structure your JSON configuration for input data:
``` 
{
  "text": "The movie was absolutely fantastic!",
  "expected_output": {
    "label": "positive",
    "confidence": 0.95
  }
}
``` 
