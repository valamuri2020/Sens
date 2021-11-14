# Sense

A NLP algorithm using Sci-kit Learn and NLTK to detect severity of mental illness in Reddit posts.

### Process
* read text data into a Pandas Dataframe
* randomly sampled data to reduce runtime due to limited resources
* perfomed expoloratory data analysis and feature engineered message length
* transformed text data into a bag of words by vectorizing each message
* applied TF-IDF metric to determine term importance in corpus
* split messages into training and testing data
* trained Random Forest Classifier model with n_estimators=300

Achieved an overall **accuracy of 75% in classifying 3 categories**.



