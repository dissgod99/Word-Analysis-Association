# Word-Analysis-Association
Homework 02 of "Ethics in NLP" where we analyse several language corpora and the association of words.


1)
In the file zipf.ipynb, we analyze the Wikitext-2 dataset and apply the Zipf's Law on it in two different ways.
Zipf's Law w states that if the words in a corpus are sorted by frequency, then the frequency of the
word at rank r is proportional to r^(−s), where s is a free parameter usually around 1. Another way to view
Zipf’s law is that a plot of log frequency against log rank will be linear.


2)
In the file diachronic_corpus.ipynb, we explore how the language used to describe and report news about the LGBTQ community
has changed over time by analyzing newspaper articles from 1986 to 2015.
We conduct a Context Analysis for some seed words and display the context words in form of Word Clouds.

3)
In the file pmi.ipynb, we build a tool for calculating pointwise mutual information (PMI) between unigram frequencies in the SNLI dataset.
We analyze certain hypotheses from the SNLI dataset where an identity label occurs with a top-associated term that shows some social bias.
