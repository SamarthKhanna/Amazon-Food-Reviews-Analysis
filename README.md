# Amazon-Food-Reviews-Analysis
Study of various methods to separate positive reviews from negative ones.
## Steps followed
### 1) Making data useful
- Splitting data into positive and negative reviews
- Selecting the useful features
- Removing duplicate entries

### 2) Text preprocessing
- Decontraction of words
- Removal of links, HTML tags
- Removal of any punctuations or limited set of special characters like , or . or # etc.
- Checking if the word is made up of english letters and is not alpha-numeric
- Converting the word to lowercase
- Removing Stopwords

### 3) Featurization
- Bag of Words
- TF-IDF
- Average Word2Vec
- TF-IDF Weighted Word2Vec

### 4) Data vsiualization with TSNE (separate notebook)
Using various values of perplexity to separate see if the points can be separated

### 5) Modelling
- K Nearest Neighbours
- Naive Bayes
- Logistic Regression
- Support Vector Machines (Linear)
- Decision Trees Classifier

(Hyperparameter tuning was done in each case)

### 6) Observation and metrics
- ROC-AUC curves were plotted for each combination

## Conclusion
- Logistic regression with TF-IDF vectorization performed the best
