This repository contains python source codes related to the paper "Investigating the effectiveness of Twitter sentiment in cryptocurrency close price prediction by using deep learning" written by me and published by wiley in the "Expert System" journal.

First, tweets are collected using the snscrap library. 
Then, the sentiments are extracted by taking the majority voting of three pre-trained language models in an ensemble way. FOr this, the " " code must be run. 
Finally, the "" code can be used to predict cryptocurrencies' close prices using the proposed hybrid model. 
For the hyper-parameter tuning of the model, the "" code must be used. 
