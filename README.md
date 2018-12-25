/*

     Author:: Raj Mehrotra
     Date:: 25-12-2018
     
 */

# IMDB-Movie-Review-Sentiment-Analysis


Text classification on the famous Imdb dataset on Kaggle.

**I have used different approaches:-**

**1 )** The first approach used is by creating **Word Embeddings in Keras** using the Embedding layer and training a neural network. The accuracy using this approach is **89.04% after training for 5 epochs.**

**2 )** The second approach is the traditional **Bag-of-Words approach with Tfidf values in the Document-Term-Matrix ( DTM )**. This gives an accuracy of **88.68% with the Logistic Regression algo**. 

**3 )** Lastly I have used the **Word2Vec** approach. I have implemented them through the **Gensim** library and then **averaged the word vectors to get a embedding or a feature vector a particular document**.

**Can also try Doc2Vec** but that sometimes work inferior to averaged word vectors.

**Note that since dataset is small the peroformance of neural net ,DL based approaches and BOW approach is comparable.**

