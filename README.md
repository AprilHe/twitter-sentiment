# Twitter Sentiment Analysis

Data can be downloaded [here](https://www.kaggle.com/nitin194/twitter-sentiment-analysis)



## 1. Feature Engineering

- the number of word
- the number of characters
- average word length
- count stopwords
- count hashtags
- count numbers
- count upper case

## 2. Text Preprocessing
- convert to lower case
- Twitter Handles (@user)
- urls
- punctuations & numbers & Special Characters
- short words that len <= 3 (not applied)
- stop words
- remove the top10 and bottom 10 frequent word (not applied)
- spelling correction (not applied)
- normalize - stem and lemma

## 3. Feature Extraction
- Bag of words
- TF-IDF
- Word embedding(Word2vec)

## 4. Split data & Model selection
