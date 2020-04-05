# FAKE-NEWS-DETECTION
Abstract:
Fake news is a type of yellow journalism. Now a days it has become hard to rely on online
news sites and news content, because we are unable to find out if we are reading the fake
news or real news. Social media and news outlets publish fake news to increase readership.
They post the news with flashy images and trendy headlines through which they will be
able to attain a greater number of views and shares. In general, fake news is profiting many
social sites and online news sites. Fake news is being shared and believed by many people
in recent times.
This project is a framework that detects and classifies fake news using Data Science
through ‘Machine Learning algorithms’. A dataset is extracted and cleaned to check if
there are any empty spaces in the dataset. This process is called as Data Wrangling. Then
the dataset is divided into Train set and Test set. A “TfidfVectorizer” is built on the dataset.
The TfidfVectorizer converts a collection of raw documents into a matrix of Term
Frequency-Inverse Document Frequency (TF-IDF) features. Then, the data is initialized to
a PassiveAggressiveClassifier to obtain an accuracy score. We also implement pipeline
which is set up with the fit/transform/predict functionality, so that we can fit the whole
pipeline to the training data and transform to the test data without doing it individually every
time. Here Naïve Bayes is also used as it’s a simple probabilistic classifier which uses
Bayes Theorem with strong independent assumptions
The result is in form of accuracy score through which we can predict if the news is real or
fake. Therefore, the user will be able to detect whether the news is fake or real. The output
is in the form of website, where the user is asked to enter a url. After receiving the input url
from user, using web scrapping the news content is extracted. Then the news article is
passed to the model and returns whether the news is fake or real
