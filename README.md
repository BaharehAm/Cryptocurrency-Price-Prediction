This repository contains python source codes for the paper "Investigating the effectiveness of Twitter sentiment in cryptocurrency close price prediction by using deep learning" published in the "Expert System" journal.

### **Abstract:**
In this study, I proposed a hybrid model for predicting the daily close price of cryptocurrencies based on different neural networks such as long short-term memory, convolutional neural network and attention mechanism. Using an ensemble of three pre-trained language models, I extracted sentiment of cryptocurrency-related tweets posted between January 1, 2021 and December 31, 2021. I constructed 20 different versions of the proposed model and evaluated their performance on data of 27 most traded cryptocurrencies using a history of previous days' sentiment data along with close prices as input data. The flexible input layer of this model enables different ways of feeding data into the model to adjust it for different cryptocurrencies to obtain better predictions. My analysis revealed several important findings. I showed that longer sequences of input data achieve most accurate predictions on average. More specifically, using a history of 14- and 21-days' data results in lowest RMSE values on average compared to using a history of 7 days. However, there is no significant difference between the results related to the input sequences with lengths of 14 and 21. In addition, my findings suggest that sentiment data can be useful in predicting prices for more than 70% of the studied cryptocurrencies. Thus, peoples' emotions, opinions, and sentiment that are expressed through their posts on Twitter platform play a significant role in prediction of cryptocurrencies' prices.

### **Link to the published paper:** 
https://onlinelibrary.wiley.com/doi/abs/10.1111/exsy.13428

### **Repository Structure:**

First, tweets are collected using the [snscrape](https://github.com/JustAnotherArchivist/snscrape) python library. Then, they are preprocessed for the next steps. Please see the "**Twitter-Web-Scraping.ipynb**" source code. This code must be run on Jupyter notebook.  

In the second stage, sentiments are extracted by taking the majority voting of three pre-trained language models in an ensemble way. For this, the following code must be run: "**Domain-Specific-BERT-Models-for-Sentiment-Analysis.ipynb**".  

Finally, the "**CSentiment_LSTM_CNN_Att.ipynb**" code can be used to predict cryptocurrencies' close prices using the proposed hybrid model. 

### **The overall diagram of the hybrid model:**
<img width="625" alt="Screenshot 2024-07-23 at 10 58 19 PM" src="https://github.com/user-attachments/assets/6f924649-a769-4a88-97dd-552d2ef3b2b6">


### **Results:**

<img width="539" alt="Screenshot 2024-07-23 at 11 00 35 PM" src="https://github.com/user-attachments/assets/4eb11c23-d376-4b25-8a04-aa602952f226">


