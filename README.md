# Chatbot Intent Architecure

Creating an intent architecture using clustering

![Chatbot](https://cdn.pixabay.com/photo/2019/03/21/15/51/chatbot-4071274_960_720.jpg?raw=true)

## Description

Given a dataset of user utterances, how do we determine intents, or classifications, we should train a chatbot on? We could manually label the utterances one-by-one with their respective intent, but that could take too much time. We could filter the utterances by keywords, but different words may mean the same thing – or the same words may mean different things. We could deploy intents iteratively, but we would have a high chance of mistaking untrained utterances as trained ones. This project explores a solution; cluster the entire dataset of user utterances based on their similarity and use the resulting clusters as the intents in the bot.

## Data

[Bitext Free Dataset](https://blog.bitext.com/free-customer-support-dataset)

## Contents

* bitext_free_dataset.csv - starting data from Bitext
* Training Dataset.xlsx - data used for training the AWS Lex bot
* Hierarchical Clustering and Cosine Similarity.ipynb - Initial attempt at cluserting
* Clustering with Word2Vec word embedding.ipynb - Final clustering method notebook
* Chatbot Intent Architecture.docx - Writeup
* Chatbot Intent Architecture.pptx - [Presentation Video](https://bellevueuniversity-my.sharepoint.com/:v:/g/personal/spsears_my365_bellevue_edu/EaenpwkCqN5PlceQQizEuAoBOU3pcA8SICumRf-IgP_6nw?e=O6jW41)
* Results.xlsx - Performance Metrics from testing

## Tools
* Python
* Gensim
* SKLearn
* Scipy
* NLTK

## Author

Samuel Sears @ssears219

## Acknowledgments

* [Bitext](https://www.bitext.com/)
* [Blog Post on Sentence Similarity](https://towardsdatascience.com/cutting-edge-semantic-search-and-sentence-similarity-53380328c655)
* [Blog Post on Text Preprocessing](https://medium.com/@datamonsters/text-preprocessing-in-python-steps-tools-and-examples-bf025f872908)
