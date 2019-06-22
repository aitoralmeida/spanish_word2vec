Ready to use gensim Word2Vec embedding models for Spanish language. Models are created using a window of +/- 5 words, discarding those words with less than 5 instances and creating a vector of 400 dimensions for each word. The text used to create the embeddings has been recovered from news, Wikipedia, the Spanish BOE, web crawling and open literary sources.  The used text has a total of 3.257.329.900 words and 18.852.481.207 characters.

The models are shared at Zenodo: https://zenodo.org/record/1410403

We support two types of models: Gensim full models (complete_model.zip) and KeyedVectors (keyed_vectors.zip). You can check the differences between them in the following URL: https://radimrehurek.com/gensim/models/keyedvectors.html

To load the full model use:
```
model = Word2Vec.load("complete.model")
```

To load the KeyedVectors use:
```
word_vectors = KeyedVectors.load('complete.kv', mmap='r')
```

If you use our models in you programs or research, please use the following citation:
```
Aitor Almeida, & Aritz Bilbao. (2018). Spanish Word2Vec Model (Version 1.0) [Data set]. Zenodo. http://doi.org/10.5281/10.5281/zenodo.11554733

Bilbao-Jayo, A., & Almeida, A. (2018). Automatic political discourse analysis with multi-scale convolutional neural networks and contextual data. International Journal of Distributed Sensor Networks, 14(11), 1550147718811827.
```

## Other datasets

Take a look at our other datasets:
* City4Age Behaviour dataset: https://zenodo.org/record/2602652#.XJtz26SkGUl
* Spanish 3B words Word2Vec Embeddings: https://github.com/aitoralmeida/spanish_word2vec
*  Political party and candidate tweets for the campaign period of the 2016 Spanish general election: https://github.com/aitoralmeida/spanish_general_election_2016
*  Political party and candidate tweets for the campaign period of the 2015 Spanish general election: https://github.com/aitoralmeida/spanish_general_election_2015
* Tweets for the campaign period of the 2014 European Parliament election: https://github.com/aitoralmeida/european_parliament_election_2014

