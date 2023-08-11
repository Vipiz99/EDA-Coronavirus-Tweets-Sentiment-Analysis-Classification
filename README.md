# EDA-Coronavirus-Tweets-Sentiment-Analysis-Classification

# OBJECTIVE

Sentiment analysis on tweets related to the coronavirus (COVID-19) can be useful for understanding public opinion, tracking trends, and identifying potential areas of concern. In this task, we can use machine learning techniques, such as logistic regression or support vector machines, to predict the sentiment of a given tweet as positive, negative, or neutral.

# DATASET

**UserName:** This column contains the username of the person who posted the tweet.

**ScreenName:** This column contains the screen name or handle of the user who posted the tweet.

**Location:** This column contains the location of the user who posted the tweet. This could be their city, state, country, or any other geographic location that they have specified in their Twitter profile.

**TweetAt:** This column contains the date and time when the tweet was posted.

**OriginalTweet:** This column contains the actual text of the tweet that was posted.

**Sentiment:** This column contains the sentiment label assigned to the tweet. This label could be positive, negative,extremely positive,extremely negative neutral, depending on the sentiment analysis algorithm used to classify the tweet.

# DATA PREPROCESSING

After loading the dataset and before building the models , the text should be cleaned and preprocessed to achieve better accuracy. Data preprocessing means to change the data in a way that it is more effective while building a model by minimizing the least important features in the data. It will include lowercasing, tokenization, punctuation removal, stopword removal like task.


# Feature Manipulation & Selection

It will include Extract relevant features from the data and transform them into a format that can be used for machine learning and Choose an appropriate machine learning algorithm or a combination of algorithms to solve the problem at hand.

# Model training

Split the data into training and testing sets, and train the model on the training set. Evaluate the model's performance on the testing set and tune the hyperparameters accordingly.Here, we use 80/20 ratio data spliting so get effective train & test data set.

# CONCLUSION

1.We applied 8 models namely, Logistic Regression with Grid Search CV, Decision Tree Classifier,Stochastic Gradient Descent , KNN, SVM,Multinomial Navies Bayes,Bernoulli Navies Bayes Classifier for both Count Vector And TF ID Vectorization techniques.

2..We conclude that the machine is generating the best results for the Stochastic Gradient Descent(count vectorizer) model with an Accuracy of 80.43% followed by the Logistic Regression with Grid Search CV (TF/ID vectorizer) model with an Accuracy of 78.86%.

3.In the future ,we can repeat the analysis and compare it with the present sentimental analysis to gauge the impact of the initiatives on the ground
