## Data Format Description

The format for each line contains one input sentence and a list of output triplets.

> sentence#### #### ####[triplet_0, ..., triplet_n]

Each triplet is a tuple that consists of `(span_a, span_b, label)`. Each span is a list. If the span covers a single word, the list will contain only the word index. If the span covers multiple words, the list will contain the all indexes of the phrase. 

