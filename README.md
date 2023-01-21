# Topic-Extraction
 
## Overview
A Machine Learning NLP project to extract research topics based on publication titles using KeyBERT unsupervised keyword extraction approach.

## Prerequisite
- Anaconda 3
- Python 

## Official Docs
[KeyBERT Github Repository](https://github.com/MaartenGr/KeyBERT)
[KeyBERT Article](https://towardsdatascience.com/keyword-extraction-with-bert-724efca412ea)

## Installation
### Installing library to nlp preprocessing
    pip install nltk 

### Installing library to keyword extraction
    pip install keybert
    pip3 install keybert

### Downloading nltk stopwords
If you don't have the nltk stopword data yet, you need to download the nltk stopword data as follows below.

    import nltk
    nltk.download()

### Result
- Raw Data
<img width="408" alt="Screenshot 2023-01-22 at 04 47 00" src="https://user-images.githubusercontent.com/74947224/213888315-cd6ba97d-736b-486f-8638-81877782f2ed.png">

- Topic Result
<img width="707" alt="Screenshot 2023-01-22 at 04 47 26" src="https://user-images.githubusercontent.com/74947224/213888319-06b8008d-42b9-4793-91b9-01a3b005778b.png">

