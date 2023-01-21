# Identify_unreliable_news_articles_using_NLP
Machine Learning program to identify when an article might be fake news or not. This problem is taken from Kaggle competation.
FAKE NEWS CLASSIFIER WITH MACHINE LEARNING ALGORITHMS USING Natural Language Processing- PART 1
This code is a solution for classifying fake news using machine learning algorithms with the help of Natural Language Processing (NLP). The code uses the dataset from kaggle competition "fake-news" (https://www.kaggle.com/c/fake-news/overview) for training and testing the model.

## Getting Started
To use this code, you will need to have Python and the following libraries installed:

- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- nltk

You will also need to have a Kaggle account and the kaggle library installed. If you do not have the kaggle library installed, you can install it by running !pip install kaggle.

## Data
The code uses the "fake-news" dataset from Kaggle competition (https://www.kaggle.com/c/fake-news/overview) to train and test the model. The dataset is loaded directly from Kaggle without the need to download it.

The code uses the "train.csv" and "test.csv" files from the dataset for training and testing the model.

## Code Structure
The code starts by loading the necessary libraries and setting up the environment. It then uses the kaggle library to download the "fake-news" dataset from Kaggle. The "train.csv" and "test.csv" files from the dataset are unzipped and used for training and testing the model.

The code then performs data cleaning and preprocessing on the dataset. It uses Natural Language Processing (NLP) techniques to convert the text data into numerical form which can be used by machine learning algorithms.

The code then uses various machine learning algorithms like Logistic Regression, Random Forest, and Support Vector Machine (SVM) to train and test the model.

Finally, the code evaluates the performance of the model and gives the accuracy score.

## Conclusion
This code provides a solution for classifying fake news using machine learning algorithms with the help of Natural Language Processing (NLP). The code uses the "fake-news" dataset from Kaggle competition for training and testing the model. It uses various machine learning algorithms and NLP techniques to classify the fake news. With the help of this code, we can easily identify the fake news and can take necessary steps to stop the spread of false information.
