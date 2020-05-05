Required Libraries:
["pyspark","sklearn","pandas","pathlib","glob","os","imblearn","collections"]

Performance comparison:

1. Logistic regression with tokenization, bag of words and removing stopwords: 0.81 (Without class weights)

2. First model with class weights: Unknown

2. Logistic regression tf-idf of already tokenized features: 0.88 (With class weights and 10 fold crossvalidation)

3. Naive Bayes with bag of words and tokenization: 0.78 (With class weights)

4. Random forest with tokenization, bag of words and removing stopwords: 0.76 (Without class weights)

5. Random forest with smot: Unknown

