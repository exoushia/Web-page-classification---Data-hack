# Web-page-classification---Data-hack
Classification of Web page content is vital to many tasks in Web information retrieval such as maintaining Web directories and focused crawling which is used to selectively seek out web pages that are relevant to a pre-defined set of topics.

Problem statement:

In this case study, we are provided with URLs from 53000+ web pages. The objective is to build a classifier that can classify the web pages into their respective classes (Each web page can belong to only 1 class).

Basically given the complete url, predict the tag a web page belongs to out of 9 predefined tags as given below:
* People profile
* Conferences/Congress
* Forums
* News article
* Clinical trials
* Publication
* Thesis
* Guidelines
* Others

Approach:
 Exploring frequency and types of URL tags | Feature extraction from URLs using bag-of-words, TF-IDF & N-Grams | Feature transformations | Model (Logistic Regression, Tree based methods, Multinomial NB) and K Fold cross validation
 
 Best model:
 Logistic Regression -
 Weighted F1 Score: 0.7476073359679621
