# Topic-Modeling-for-Customer-Reviews
This repo to cluster customer review about new product in english try to apply different approaches to reach this goal 

## Details

**Aproach 1**

1. Bussiness Understanding and Data visualization 
2. Data Processing include
   * simple preprocess with gensim 
   * Remove stopwords using nltk 
   * Drop letters
   * stemming
3. Vectorize text using BOW 
4. Apply LDA model
5. Visualize topics using pyLDAvis for more understand
6. Different trails for LDA model


**Aproach 2**

Apply BERTOPIC without preprocessing as it has it's own embedding model

Modify BERTopic by various tips
  * CountVectorizer and then remove stopwords (NOTE: this happened after embedding)
  * ctfidf_model identify the importance of word accrose topics
  * limit the number of duplicate words we find in each topic
  * 
Visualize topics using BERTopic visualize_barchart method
Visualize top words using Create wordcloud

