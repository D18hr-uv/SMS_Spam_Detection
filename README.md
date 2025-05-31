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

## Dataset
![image](https://github.com/user-attachments/assets/54a4796a-aa56-41c4-a46c-929547d9137c)
![image](https://github.com/user-attachments/assets/226f5043-1faa-46ef-a8ec-2b85f3d7e545)

## Distribution of word_count for Ham SMS
![image](https://github.com/user-attachments/assets/a1c7d63a-4d09-4f69-abae-df5ec26cbe6a)

## Distribution of word_count for Spam SMS
![image](https://github.com/user-attachments/assets/231158e6-d2f5-4d8a-b1d7-c9c355ca3140)

## Countplot for Containing currency symbol
![image](https://github.com/user-attachments/assets/80f563bd-4d9d-462c-8a86-2648da3d32a5)

## Countplot for Containing number
![image](https://github.com/user-attachments/assets/5aaf7315-6f4e-4b25-9b5d-a2c19546f76a)

## Confusion Matrix
![image](https://github.com/user-attachments/assets/d39dcba4-637a-412e-981c-fc676840d49d)

