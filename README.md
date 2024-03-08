This repository contains python source codes related to the paper "Investigating the effectiveness of Twitter sentiment in cryptocurrency close price prediction by using deep learning" written by me and published by wiley in the "Expert System" journal.
Here is the link to the paper: 
https://onlinelibrary.wiley.com/doi/abs/10.1111/exsy.13428

First, tweets are collected using the snscrap library. Then, they are preprocessed for the next steps.
Then, the sentiments are extracted by taking the majority voting of three pre-trained language models in an ensemble way. For this, the following code must be run: "Twitter_Sentiment_Analysis_using_three_pre_trained_language_models_in_an_ensemble_way"
Finally, the "" code can be used to predict cryptocurrencies' close prices using the proposed hybrid model. 

