# SMS_Spam_Detection

In our day-to-day life, we come across many spam messages, which consist of various kinds of fraud. In this project, I have used the oversampling method to address data imbalance. Then train the data on already labeled data as Ham or Spam.

The code flow:
1) Importing the dataset and libraries like numpy , pandas.
2) Observing the Dataset for any Data imbalance.
3) Then filling the Data imbalance with the oversampling method.
4) Differentiating Ham and Spam messages based on Words Count, Under Histogram.
5) Differentiating Ham and Spam messages on the basis of Currency symbol present or not, Under bar graph.
6) Now cleaning Data with the help of Lemmatizer of nltk library.
7) Then, making bag of words by TfidfVectorizer from sklearn liberary.
8) Training with Naive bayes model over train data set.
9) checking how well the model is trained.
