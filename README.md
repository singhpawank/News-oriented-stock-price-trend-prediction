# News oriented stock price trend prediction
 
  The main goal of our project is to clean and analyse data and train a machine learning
  model to analyse news data and anticipate market trend movement using two of the
  most common machine learning methods, Logistic Regression and Support Vector
  Machine (SVM).

## Dataset
  The dataset we're working with is a mix of Reddit news and the stock price of the Dow
  Jones Industrial Average (DJIA) from 2008 to 2016. From 2008 to 2016, the news
  dataset covers the top 25 stories on Reddit for each day. Each trading day's basic stock
  market information, such as Open, Close, and Volume, is contained in the DJIA. The
  dataset's label indicates whether the stock price increased (labelled as 1) or decreased
  (labelled as 0) on that particular day. The dataset has a total of 1989 days.
  
## DATA SEGMENTATION AND CLEANING:
  * News wordcloud before removing Stopwords

    ![](https://drive.google.com/uc?export=view&id=1YPAstmztS4mZK7VWEhPJ8eK4q1593OnG)

  * News wordcloud after removing Stopwords 
  
    ![](https://drive.google.com/uc?export=view&id=1SDlnzFCUTYFz11UgSxEiv6s3zbrAUGSF)

  * Top 25 Unigram words in News before removing Stopwords
    
    ![](https://drive.google.com/uc?export=view&id=1S1RTebJeNq7SHD6VjCSZyd-C0JLPy_JS)

  * Top 25 Unigram words in News after removing Stopwords
    
    ![](https://drive.google.com/uc?export=view&id=1FKDliMMrD32GABMhJfpxo2sSVPdjnTAY)

  * Top 25 bigram words in News before removing Stopwords
    
    ![](https://drive.google.com/uc?export=view&id=1F6Q9QhtbM6k5E5xwjOewdCijarzFRpHG)
    
  * Top 25 bigram words in News after removing Stopwords
    
    ![](https://drive.google.com/uc?export=view&id=153XgetbWShjMqwRge62Kqo57KS-ET8Xr)

## Model training
* Logistic Regression       

                     precision    recall  f1-score   support

                0       0.98      0.70      0.82       186
                1       0.77      0.99      0.87       192

            accuracy                        0.85       378
        macro avg       0.88      0.84      0.84       378
        weighted avg    0.88      0.85      0.84       378

* Support Vector Machine(SVM)

                     precision    recall  f1-score   support

                0       1.00      0.70      0.82       186
                1       0.77      1.00      0.87       192

            accuracy                        0.85       378
        macro avg       0.89      0.85      0.85       378
        weighted avg    0.89      0.85      0.85       378


### For both the models we achieved the maximum accuracy of 85% , and this was achieved when we included all unigrams, bigrams and trigrams.

Dataset_Source:-  
https://data.world/finance/daily-news-for-stock-market




    



  
  




    
