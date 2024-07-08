## Introduction
In this project, we perform sentiment analysis on Amazon Fine Food Reviews using two methods:
- ** VADER **: A lexicon and rule-based sentiment analysis tool.
- ** RoBERTa ** : A transformer-based model trained on a large corpus of data.

## Data
The dataset used is the Amazon Fine Food Reviews, which can be found on Kaggle. The dataset contains reviews of fine foods from Amazon.

## Quick EDA
We start by performing a quick exploratory data analysis (EDA) to understand the distribution of review scores.

## VADER Sentiment Scoring
VADER (Valence Aware Dictionary and sEntiment Reasoner) is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media.

## Steps:

- Read and preprocess the data.
- Use NLTK's SentimentIntensityAnalyzer to get sentiment scores.
- Analyze and visualize the sentiment scores.
- RoBERTa Pretrained Model
- RoBERTa (A Robustly Optimized BERT Pretraining Approach) is a transformer-based model from Huggingface's library, used for sentiment analysis.

## Steps:

- Load the pretrained RoBERTa model and tokenizer.
- Tokenize the text and run it through the model.
- Analyze and visualize the sentiment scores.
- Comparison of Results
We compare the results from the VADER and RoBERTa models to see how they differ in sentiment scoring.

## Review Examples
We look at specific examples where the review score and model predictions differ significantly to understand the nuances of each model.

## Transformers Pipeline
We also explore using Huggingface's pipeline for a quick and easy way to run sentiment predictions.

## How to Run
- Clone the repository.
- Ensure you have all the dependencies installed (see below).
- Run the Jupyter notebook.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- tqdm
- transformers
- scipy

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to explore the notebook and adapt the code for your own sentiment analysis projects! If you have any questions or suggestions, please open an issue or submit a pull request.






