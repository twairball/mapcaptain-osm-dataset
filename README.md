# README

Dataset for Map Captain OSM map data translation. 

Raw data extracted from www.openstreetmap.org.


### Datasets

- china-latest

    Contains whole china corpus. 

- greater_shanghai

    Contains a large area of municipal Shanghai

- shanghai_sample

    Small sample of downtown Shanghai, around Jingan District. 


### Corpus

Each dataset contains the following corpus:

- dataset.csv

    CSV with `name` and `name:en` as filtered and extracted from `.osm` file. 

- dataset.csv.en and dataset.csv.zh

    CSV files split to parallel corpus for English and Chinese respectively.

- dataset.tok.en 

    English tokenized corpus, processed by `nltk.word_tokenizer`

- dataset.tok.zh

    Chinese tokenized corpus, processed by `jieba`

- dataset.vocab.50k.en, dataset.vocab.50k.zh

    Corpus vocab, limited to top 50k words. 

