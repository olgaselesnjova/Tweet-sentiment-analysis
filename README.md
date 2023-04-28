# Tweet sentiment prediction 
**Competition on Kaggle:** https://www.kaggle.com/competitions/gsom-23sm1-ml-hometask-2/overview

**Dataset:** about 45,000 tweets about COVID 19 collected in 2020 manually labelled with sentiments

The dataset contains about 45,000 tweets about COVID 19 collected in 2020 separated into two files: train and test data sets.The tweets were manually labelled with 5 sentiment labels: 'Extremely Negative', 'Negative', 'Neutral', 'Positive', 'Extremely Positive'.

corona_train.csv contains tweets with the target variable (Sentiment) included. You should use these data to train your models and check their quality before making a submission.

corona_test.csv contains tweets without associated values of the target variable. You should predict sentiments for every tweet from this file and upload the results to Kaggle. Correct answers are already stored in the system, and the system will use these answers to evaluate the quality of your solution.

corona_sample_submission.csv is an example of how a submission prediction results should look like. You need to replace sentiment predictions in this file with predictions produced by your own model.

Columns:

- **UserName** - login of a user.
- **ScreenName** - screen name of a user.
- **Location** - location of a tweet.
- **Tweet At** - date of a tweet.
- **Original Tweet** - text of the original tweet.
- **Sentiment** - sentiment in a tweet.
- **Usernames** and **screen names** were hidden to avoid any privacy concerns.

## Result: 
XGBClassifier: Accuracy = 0.60260 in private leaderboard
