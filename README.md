This repository contains python source codes for the paper "Investigating the effectiveness of Twitter sentiment in cryptocurrency close price prediction by using deep learning" published in the "Expert System" journal.

#### **Link to the published paper:**
https://onlinelibrary.wiley.com/doi/abs/10.1111/exsy.13428

First, tweets are collected using the [snscrape](https://github.com/JustAnotherArchivist/snscrape) python library. Then, they are preprocessed for the next steps. Please see the "**Twitter-Web-Scraping.ipynb**" source code. This code must be run on Jupyter notebook.  

In the second stage, sentiments are extracted by taking the majority voting of three pre-trained language models in an ensemble way. For this, the following code must be run: "**Domain-Specific-BERT-Models-for-Sentiment-Analysis.ipynb**".  

Finally, the "**CSentiment_LSTM_CNN_Att.ipynb**" code can be used to predict cryptocurrencies' close prices using the proposed hybrid model. 

