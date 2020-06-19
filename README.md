# FinalProjectDL2020
**Final Project of course Deep Learning, UPF 2020.**  

Sentiment Analysis on Restaurant Reviews Dataset. 

Comparison between CNN and RNN approach.

This project was developed by:

- Esther Flores

- Candela García

- María Hernández

Dataset used: [Restaurant Customer Reviews, Kaggle](https://www.kaggle.com/vigneshwarsofficial/reviews)

The aim of the project is to train two different Neural Networks: CNN and RNN. 

Theoretically, as the dataset is made of: text sequences (reviews) and a label whether it is a positive or negative review (1 and 0 respectively), we had a first hypothesis that RNN model would get better results, a higher accuracy.

We based our models in the models uploaded in the following repository: [PyTorch Sentiment Analysis](https://github.com/bentrevett/pytorch-sentiment-analysis).

## Code

Our code was made in a .ipynb worked on Google Collaborate. See: [code]()

## Results: 

After preparing dataset and configuring the models we obtained the following results:

- RNN: accuracy of the test 73.05 %

- CNN: accuracy of the test 77.73 %

(We tried with different values for both hidden dimensions and number of layers, these are the best results we obtained by trying different values of both hyper-parameters).

1. First thing that draws our attention is the quite low accuracy obtained in both models.

2. Secondly, we see that, contrary to our expectations, we obtained a bit higher accuracy for CNN model.

## Conclusions

Our hypothesis is dismissed, as our idea was that we should obtain a better result for the RNN model (as theoretically it is better for text sequences, which keep a relation between the different words that appear).

Considering both results, we reach the conclusion that the dataset used is not a suitable one to obtain a good result in our project. Processing text is tough task, due to the complexity of speech: pragmatics, how context affect on the text, irony, etc. And a dataset consisting of 1000 samples is not enough for the model to learn these difficulties of speech processing.



Further explanation on the project is obtained in here: [slides]()
