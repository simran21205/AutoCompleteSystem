# AutoCompleteSystem

Dataset used - [link](https://www.kaggle.com/datasets/thedevastator/hellaswag-a-new-commonsense-nli-dataset)

Problem Statement:
The project aimed to develop a sentence auto-completion system using classical machine learning techniques. The objective was to predict the next word in a sentence by understanding the context and semantics of the sentence. 

For example, given the input "The quick brown fox jumps over the lazy", the system predicts the word "dog".

This example illustrates the system's challenge: to design an auto-completion mechanism capable of accurately understanding and completing sentences in diverse contexts.

The solution involved employing N-gram models, specifically bi-gram models, which are statistical language models used for predicting the likelihood of a sequence of words. These models compute the probability of a word based on the occurrence frequency of word sequences. The bi-gram model approximates the probability of a word given all previous words by using only the conditional probability of the preceding word. 

Additionally, K-Smoothing was used to adjust probabilities in the model, ensuring unseen n-grams are not assigned zero probability. This enhancement helped in providing a more robust and realistic probability estimation. 
