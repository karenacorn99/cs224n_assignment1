# cs224n_assignment1

Exploring count-based and prediction-based word vectors

Count-based:
  1) read_corpus: preprocessing of text(tokenize, add start/end tokens, lowercase)
  2) disrinct_words: sorted list of distinct words across corpus
  3) compute_co_occurrence_matrix: compute co-occurence matrix
  4) reduce_to_k_dim: dimension reduction using SVD
  5) plot_embedding: plot 2D vectors in Cartesian plane

Prediction-based:
  1) polysemous words
  2) synonyms & antonyms
  3) analogies
  4) bias
