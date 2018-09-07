Ready to use gensim Word2Vec embedding models for Spanish language. Models are created using a window of +/- 5 words, discarding those words with less than 5 instances and creating a vector of 400 dimensions for each word. The text used to create the embeddings has been recovered from news, Wikipedia, the Spanish BOE, web crawling and open literary sources.  The used text has a total of 3.257.329.900 words and 18.852.481.207 characters.

The models are shared at Zenodo: https://zenodo.org/record/1155474

We support two types of models: Gensim full models (complete_model.zip) and KeyedVectors (keyed_vectors.zip). You can check the differences between them in the following URL: https://radimrehurek.com/gensim/models/keyedvectors.html

To load the full model use:
```
model = Word2Vec.load("complete.model")
```

To load the KeyedVectors use:
```
word_vectors = KeyedVectors.load('complete.kv', mmap='r')
```

If you use our models in you programs or research, please use the following citation (other citation stiles available at Zenodo):
```
Aitor Almeida, & Aritz Bilbao. (2018). Spanish Word2Vec Model (Version 1.0) [Data set]. Zenodo. http://doi.org/10.5281/10.5281/zenodo.11554733
```

