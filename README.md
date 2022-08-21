# movie_sentiment
### OverView 
This repo contains the code and submission file I used for submitting in the kaggle competition https://www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews
A sentiment analysis is to be performed on the given dataset "train.csv" , which contains phrases for movie reviews and 5 labels/Sentiments classes corresponding to it.
### Approach
A simple approach is made . No pre trained models were used ( Like BERT , Roberta etc ) . The text was preprocessed using one hot representation and then further transformed into embedding vectors . 
![image](https://user-images.githubusercontent.com/95174361/185795824-eb0411ac-076d-40ac-9e2a-4823d22b7621.png)

Simple ANN model with an Embedding and LSTM  layer was used to build the model.
![image](https://user-images.githubusercontent.com/95174361/185796016-c7202bb4-08e2-40d6-9387-8b5af42519c4.png)

Stemming and lemmatization techniques was used to clean the text . 
![image](https://user-images.githubusercontent.com/95174361/185795902-8f179bcc-93aa-42fb-bd3e-9d5599cdee74.png)

Train accuracy achieved : 77% and test accuracy : 68% , Final submission Score : 0.5790
