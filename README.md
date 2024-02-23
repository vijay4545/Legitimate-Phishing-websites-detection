# Legitimate-Phishing-websites-detection
This project is about identifying the fake websites based on URLs.
# URLs
URL stands for uniform resource locator. It is used to locate a resource such as hypertext pages, images, audio files etc. on web. Base URL is calculated by concatenating protocol, hostname and path of the URL.
# Phishing
Phishing continues to be of major concern not only because of increase in number of phishing attacks but also because of the sophisticated methods used by the attackers to perform the attack.
A Python program has been implemented which takes URL of a website as an input, extracts features from different parts of URL and the features can be either hand-crafted or obtained from TF-IDF. These extracted features are fed to the model trained using machine learning algorithms to classify the website either as legitimate or phishing.
# Importing the packages
Pandas is usually imported under the pd alias
NumPy is a Python package. It stands for 'Numerical Python'. It is a library consisting of multidimensional array objects and a collection of routines for processing of array.
Python Scikit-learn lets users perform various Machine Learning tasks and provides a means to implement Machine Learning in Python.
# For preprocessing,the techniques used are
CountVectorizer
It is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.
TfidVectorizer
The process of transforming text into a numerical feature is called text vectorization. TF-IDF is one of the most popular text vectorizers, the calculation is very simple and easy to understand. It gives the rare term high weight and gives the common term low weight.
# Machine learning algorithms
To evaluate the performance of CountVectorizer and TF-IDF features, we applied various machine learning classifiers such as XGBoost, logistic regression, K-Nearest neighbour, MultinomialNB & decision tree to train our proposed model. The main intention of comparing various classifiers is to choose the best classifier suitable for our feature set. To implement various machine learning classifiers, Scikit-learn package is used and Python is used for feature extraction.
# The Accuracy of the used models are as follows:
Naive Bayes : 96.0%                      XG Boost: 97.0%                     Random Forest: 96.0%
