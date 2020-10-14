<h1 style="text-align:center"> Sentiment Analysis </h1>



## Objectives

1. Implement a simple way to represent text data - Bag of words
2. Implement a basic statistical learning model - Bayesian Naive
3. Use these representations and this model for a sentiment analysis task.
4. Implement different ways of obtaining dense representations of the same data
5. Use a logistic regression model to train a classifier on these new representations.




## Prerequisites
You need to install 
- The Machine Learning API [Scikit-learn](http://scikit-learn.org/stable/install.html)

```console
$ pip install -U scikit-learn 
```
- The [Natural Language Toolkit](http://www.nltk.org/install.html)

```console
$ pip install --user -U numpy
$ pip install --user -U nltk
```
## Workflow 
- Naive Bayes  classifier class implemenation 
- Text preprocessing : Stemming, Tokenization , Part of speech tag 
- Exprementing with different piplines
- Evaluating performances with cross-validation 
- Improving representation of the data : 
    - BOW represenation 
    - TFIDF
    - Use of n-grams insted of Uni-grams
- Dense representation :
    - Co-occurence
    - Word2Vec
    - Gl0ve
- Data Reduction : 
    - Principal component analysis (PCA)
    - Dense represenation Visualisation using PCA data   
- Application On Sentiment analysis using Naive Bayes & Logistic regression 

## TODO 
- Try more complexe models and Neural Networks 

