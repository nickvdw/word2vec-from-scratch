# word2vec-from-scratch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nickvdw/word2vec-from-scratch/blob/master/word2vec.ipynb)

In this notebook, we explore the models proposed by Mikolov et al. in [1]. 
We build the Skipgram and CBOW models from scratch, train them on a relatively small corpus, implement an analogy function using the cosine similarity, and provide some examples that make use of the trained models and analogy function to perform the word analogy task.
We look at three different number of dimensions for the word embeddings in order to get a better intuition how the number of dimensions influences the result.

[1] [Mikolov, Tomas, et al. "Efficient Estimation of Word Representations in Vector Space" Advances in neural information processing systems. 2013.](https://arxiv.org/abs/1301.3781)
