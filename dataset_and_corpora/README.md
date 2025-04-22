# Datasets and Corpora

This folder should have the dataset used in the project as well as some custom corpora for some models.

Download the [dataset](#dataset) and the [corpora](#corpora) mentioned below and move it to this folder.

## Dataset

The dataset is a CSV file with the following columns:

- _title_: the title of the article
- _text_: the text of the article
- _label_: the label of the article (0 for fake, 1 for real)

The dataset used is the WELFake dataset [available here](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)

This dataset is a collection of news articles, with each article labeled as either fake or real. The dataset contains 10,000 articles, with 5,000 fake and 5,000 real articles. The articles are in English and cover a wide range of topics, including politics, sports, entertainment, and technology.

## Corpora

- Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/pubs/glove.pdf).
  - Pre-trained word vectors: [Wikipedia 2024 + Gigaword 5 (glove.6B.zip)](https://nlp.stanford.edu/data/glove.6B.zip)
