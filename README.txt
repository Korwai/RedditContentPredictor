Project members: Nick Calkins, Matthew Levitt, Alex Liu, Khoa Le.
CS 4200 Final Report: Reddit Post Title Classification Using Huggingface’s RoBERTa and Scikit Learn’s MultinomialNB

Reddit Dataset Generation: https://colab.research.google.com/drive/1oiWioQ2p0d43CMu4N4ieO2YpbNljs-Pf
RoBERTa Model: https://colab.research.google.com/drive/1qYN50460xmTs8t3N3oHUtt4DuXnd7hjL?usp=sharing#scrollTo=xoZCV85d5u8U
Multinomial Naive Bayes Model: https://colab.research.google.com/drive/1qi5Zt9ARIpypBwJhwPLI9rGiLUjbZEj5#scrollTo=PUEnvpJvc8sf

Here, we've included the dataset generation as well as the two models that we used for our project. Both models have access to our data through an URL. We included a copy of the .csv in the .zip file for easier access. 

The RoBERTa model relies on PyTorch and its HuggingFace Transformer library and we use pandas to handle our dataframe.
Other dependencies: sklearn, matplotlib, string, numpy, os, nltk, tokenizers, re, requests, tqdm, seaborn.

The MultinomialNB model relies mainly on sklearn's library for the Naive Bayes model, feature extraction, and accuracy testing.
Other dependencies: pandas, numpy, os, nltk, re, requests, matplotlib, seaborn.

The data is a .csv file that contains the reddit posts that we used for both colabs. For each post, we included the title and flair. This was the main dataset that we tested our models with.  
All datasets that we've used can be found at: https://github.com/NTCalkins/content_predictor/

