/*

     Author:: Raj Mehrotra
     Date:: 25-12-2018
     
 */

# IMDB-Movie-Review-Sentiment-Analysis


Text classification on the famous Imdb dataset on Kaggle.

**I have used different approaches:-**

**1 )** The first approach used is by creating **Word Embeddings in Keras** using the Embedding layer and training a neural network. The accuracy using this approach is **89.04% after training for 5 epochs.**

**2 )** The second approach is the traditional **Bag-of-Words approach with Tfidf values in the Document-Term-Matrix ( DTM )**. This gives an accuracy of **88.68% with the Logistic Regression algo**. 

**Note that since dataset is small the peroformance of neural net and BOW approach is comparable.**

