# PRACTICE: DisneyLand Reviews NLP and Sentiments

To understand NLP and Sentiments. Practice from https://www.kaggle.com/code/ahmedterry/disneyland-reviews-nlp-sentiment-analysis


Textblob
It is a simple python library that offers API access to different NLP tasks such as sentiment analysis, spelling correction, etc.

Textblob sentiment analyzer returns two properties for a given input sentence:

1. Polarity is a float that lies between [-1,1], -1 indicates negative sentiment and +1 indicates positive sentiments.
2. Subjectivity is also a float which lies in the range of [0,1]. Subjective sentences generally refer to personal opinion, emotion, or judgment. 


INSTALLATION
```
conda activate ENV
conda install -c conda-forge textblob
pip install spacy
python -m spacy download en_core_web_lg
```
