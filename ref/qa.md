# Q & A

## Triplet loss Explain



## Zero-Shot Learning Explain

The zero-shot learning is to generalize to the samples taht were not observed during trainining.

## NLP Models Explain

We use Doc2Vec in the end.  

BM25 is a TD-IFD-based algorithm for quierying corpus and reutrning the ones most relevant to the query by similarity scoring, but it cannot generate embedding.

Then, we resort to Doc2Vec. It’s similar to Word2Vec but works on the phrase-, sentense-, and document-level. By adding the document0unique feature vector called paragraph ID in the distributed bag-of-words method, given a context of sentences, it can predict how likely it is for each sentence in the documents being a sentence. 

The BERT is transformer-based pre-trained model. The bidirectional training of transformer that allows it to learn the context of a word based on all of is surroudings. It fails probably since it’s pre-traiend and work well on the logical and long documents but the product titles here are short and sometimes disorderly. 

Faiss we don’t have time.

## CV Models Explain

TODO

## Embedding and KNN Explain



