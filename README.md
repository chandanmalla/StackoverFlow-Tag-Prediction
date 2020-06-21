# StackoverFlow-Tag-Prediction
Prediction for StackOverFlow Tags based on the Content(Title + Body).


Data set is taken from https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction

I have taken very small set of data from 4 million data.

Steps in order which I have performed:
EDA --> PreProcessing(Stemming,Tokenization,Stopword removal,html tags removal etc) --> Logistic Regression with One vs Rest Classifier(Can use any classifier, as I was not hoping to get a good accuracy, used a Simple Linear Model)

#### Original Data-SET
![GitHub Logo](/images/data-set.PNG)

#### Data set after pre-processing
![GitHub Logo](/images/data-set2.PNG)


![GitHub Logo](/images/Distribution of Tags in each question.PNG)

![GitHub Logo](/images/popular-tags.PNG)

