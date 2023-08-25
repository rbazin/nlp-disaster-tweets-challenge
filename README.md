# NLP Disaster Tweets Classifier

Leveraging the power of BERT finetuned on a curated corpus of tweets for enriched Natural Language Understanding, our project achieved to reach the 27th spot among 871 contenders in [Kaggle's NLP challenge](https://www.kaggle.com/competitions/nlp-getting-started). This achievement was realized as part of the final project for the AI course ECSE526, at McGill University.

# Setup

To install the depencies needed for this project, you'll need to install conda, then run :
```bash
conda env create -f environment.yml
```

# Important files

Most of our work can be found in the notebook, here is a brief summary of what you can find in them :
* data_exploration.ipynb explores the data set and the pre-processing pipeline
* BERT.ipynb is about the fine-tuning of BERT, its optimization and how to create a simple ensemble prediction
* LSTM.ipynb is about the training of a LSTM network
