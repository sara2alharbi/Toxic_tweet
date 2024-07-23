# Toxic-Tweets: Identifying Toxicity in Tweets Using Machine Learning and Persona Analysis

# Project Overview
The project uses the Toxic Tweets Dataset from Kaggle to identify toxicity in tweets, aidding in
natural language processing projects to mitigate online toxicity. using machine learning models
like LR and SVC as a baseline, and BERT models will be used for comparison, evaluated based
on f1 score, precision, recall, and accuracy.

# Dataset Source
https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset

# Methadology
1- LR (Logistic Regression ) : LR is a widely used algorithm for binary
classification. It estimates probabilities based on independent variables, allowing
for interpretable results. While assuming linearity, it performs well in various
applications like sentiment analysis and fraud detection. The model was trained
based on TF-IDF.

2- SVC (Support Vector Classifier) : SVC is utilized to construct a model that
categorizes tweets as toxic or non-toxic, learning from a labeled dataset and
determining the optimal hyperplane. The model was trained based on TF-IDF.

3- BERT (bert-base-uncased): We employ BERT “bert-base-uncased” for the
task of toxic tweet classification. The “bert-base-uncased” variant, a popular
version of BERT. BERT is pre-trained BERT is pre-trained using a masked
language model (MLM) objective on a vast corpora of text, enabling it to capture
intricate patterns and nuances within language. It’s bidirectional nature allows it
to consider both preceding and succeeding words when understanding a word in a
sentence.

As part of our methodology, we have expanded our dataset by introducing a new feature – a
column named "persona".
