# Sentence embeddings of Football commentaries 

This project proposes a deep learning method to label text commentaries as scenarios taking place in the game.In this project, we utilize a Kaggle dataset containing text commentaries from numerous games in different leagues across Europe.As doc2vec is designed for large data analysis, it should be trained on large corpora in order to get effective results. Therefore, we used a doc2vec model that was pre-trained on a collection of Wikipedia articles that it got from the English Wikipedia database dump using the WikiExtractor code. Our hypothesis is that our CNN model to which doc2vec embeddings are fed is able to learn a labeling process describing the game scenarios associated with each commentary.

![Sample Reconstruction](https://github.com/ahariri13/commentary_classification/blob/master/flowchart.png)
