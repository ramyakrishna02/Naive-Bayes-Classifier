# Naive Bayes Classifier
Naive Bayes classification model is a type of machine learning algorithm that uses the Bayes’ theorem to predict the class of a given data point based on the features and the prior probabilities of the classes. 
It is called naive because it assumes that the features are independent of each other, which is often not true in real-world situations. 
However, naive Bayes classifiers are simple, fast, and effective for many classification tasks, especially for text and document analysis. 

Some examples of naive Bayes classifiers are:
- ### Gaussian naive Bayes:
  It assumes that the features follow a normal distribution and calculates the likelihood of each feature using the mean and standard deviation of the feature values for each class.

- ### Multinomial naive Bayes:
  It assumes that the features are discrete counts and calculates the likelihood of each feature using the frequency of the feature values for each class. It is often used for text classification with bag-of-words or tf-idf features.

## Implementation
- Importing the required Libraries
- Reading the train and the test datasets
- Performing EDA on both the datasets (train and test)
- Splitting the train and the test data
- Normalization of the data
- Building the Model
  - using Gaussian Naïve Bayes
  - using Multinomial Naïve Bayes
- Conclusion

## Packages Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- warnings
- from sklearn.preprocessing import LabelEncoder
- from sklearn.metrics import accuracy_score, confusion_matrix
- from sklearn.naive_bayes import GaussianNB
- from sklearn.naive_bayes import MultinomialNB
