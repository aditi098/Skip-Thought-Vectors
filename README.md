# Skip-Thought-Vectors
An unsupervised model for learning an encoding of high-quality sentence vectors. As compared to previous studies
which use word vector embeddings to predict context, this paper converts the word embeddings to sentence embeddings
and uses Long Short Term Memory Units or Gated Recurrent Units(GRUs) to process the sentences.

Also includes Evaluation of the sentence representation(features extracted by the encoder) on Movie Review dataset and
TREC(Question Type) dataset by training a logistic regression on the encoded skip thought vectors and 10
fold nested cross validation method.
