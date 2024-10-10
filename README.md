# Project Title
Sentiment Analysis Prediction Using Naive Bayes and Logistic Regression

#dataset overview
Dataset I analysed was taken from the IMDB movie reviews dataset, which contains thousands of movie reviews with sentiment labels (positive, negative). There are two columns one is customers reviews and second columns is about the kind of sentiment


*   positive
*   negative
 # Methodology



The data cleaning process was carried out in several key steps to prepare the dataset for analysis and improve the performance of the classification models:

## 1. Removing HTML Tags

To remove any unnecessary HTML markup that could interfere with text analysis.

## 2. Converting Text to Lowercase

 To standardize the text by converting everything to lowercase, avoiding duplication of words with different cases.

## 3.Removing Special Characters and Punctuation
 To eliminate irrelevant symbols and focus on meaningful words.

## 4.Removing Stopwords

To reduce noise by eliminating common words that don't carry significant meaning, such as "the," "and," and "is.
## 5.Stemming

 To reduce words to their root forms, improving uniformity and model accuracy.
 I applied stemming using NLTK’s PorterStemmer to convert words like "running" to their root form "run," which helps reduce the complexity of the data and improves model performance.






