# SMS_Spam_Detection

In our day to day life we come across so may Spam Messages, these Messages do consist of so many kinds of frauds. In this project, I have used Over Sampling method to fill data imbalance. Then train the data on an already labbled data as Ham or Spam.

The code flow:
1) Importing dataset and libraries like numpy , pandas.
2) Observing the Dataset for any Data imbalance.
3) Then filling the Data imbalance with oversampling method.
4) Differentiating Ham and Spam messages on the basis of Words Count, Under Histogram.
5) Differentiating Ham and Spam messages on the basis of Currency symbol present or not, Under bar graph.
6) Now cleaning Data with the help of Lemmatizer of nltk library.
7) Then, making bag of words by TfidfVectorizer from sklearn liberary.
8) Training with Naive bayes model over train data set.
9) checking how well the model is trained.
