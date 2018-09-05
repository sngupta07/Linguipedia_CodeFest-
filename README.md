<pre>
# Linguipedia_CodeFest-
About Linguipedia codeFest Natural Language Processing

The problem is based on binary senntiment analysis, we have to predict the sentiment of the tweet is it positive or negative.

My approach: -

1. I used python dependencies for that.
2. After reading the data I preprocessed it and find out these
   A. Find the length of tweets
   B. Average length of words
   C. Number of chars
   D. Number of special characters
   E. Number of stopwords
   F. Number of numerics
   G. Number of characters
   
3. Afterward I cleaned the data includes
   A. Removed punctuations
   B. Removed stopwords
   C. Removed most frequent words
   D. Removed less frequent words
   E. Stemming
   F. Lemmatizing

4. Feature extraction
   A. Countvectorizer
   B. Tfidfvectorizer
   C. Add features to the sparse matrix (like: number of numerics, special characters, etc)
   
5. Then, machine learning modeling
   A. 1st used Logistic Regression with countvectorizer
   B. 2nd used Logistic Regression with tfidfvectorizer
   C. Compare them countvectorizer won.
   
6. Then, I tried ANN model using keras
   Try with different important parameters like by changing the hidden layers, nodes, activation function, no of epoches, 
   batch size, etc. And at last I got the best result from that with f1-score 0.81945.
   
 The competition has beed organized by the analytics vidhya.
 Result: -
 1. Public LB: - 27 (with f1-score: - 0.8979)
 2. Private LB: - 58 (with f1-score: - 0.8849)
 
</pre>
