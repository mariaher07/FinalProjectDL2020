# FinalProjectDL2020
*Final Project of course Deep Learning, UPF 2020.*  

Sentiment Analysis on Restaurant Reviews Dataset. 

Comparison between CNN and RNN approach.

This project was developed by:

- Esther Flores

- Candela García

- María Hernández

Dataset used: https://www.kaggle.com/vigneshwarsofficial/reviews

The aim of the project is to train two different Neural Networks: CNN and RNN. 

Theoretically, as the dataset is made of: text sequences (reviews) and a label whether it is a positive or negative review (1 and 0 respectively), we had a first hypothesis that RNN model would get better results, a higher accuracy.

We based our models in the models uploaded in the following repository: https://github.com/bentrevett/pytorch-sentiment-analysis

This is how we proceeded: 

  ## Preparation of dataset
  
  Divide our initial dataset into: 
  
  - Training Set
  
  - Validation Set
  
  - Test Set
  
  We convert every subset into type Dataset, of TorchText, to be able to process natural language ( which have presence in the reviews).
  
  We build the vocabulary our models will have, which is take from vector "glove.6B.100d"
