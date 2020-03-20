# resonance_model
This repository showcases a langauge model that uses word embeddings to quantify the resonance of the language being used between corpora.

The steps to this model are:
  1) Train Word2Vec word embeddings from a baseline corpus.
  2) Train Word2Vec word embeddings from one or more target corpora.
  3) Gather the list of words found in all corpora.
  4) Compute the distance between embeddings of the common words from the baseline corpus and target corpus (or target corpora).
  5) Aggregate these distance measures over all common words to get a final resonance score.

Please see the paper and the Jupyter Notebook for a more detailed explanation.

Ryan Lattanzi
