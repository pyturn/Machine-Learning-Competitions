

Problem Statement :

The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate 
speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from 
other tweets.
Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' 
denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.



Motivation :
Hate  speech  is  an  unfortunately  common  occurrence  on  the  Internet.  Often social media sites like Facebook and Twitter
face the problem of identifying and censoring  problematic  posts  while weighing the right to freedom of speech. The  
importance  of  detecting  and  moderating hate  speech  is  evident  from  the  strong  connection between hate speech and 
actual hate crimes. Early identification of users promoting  hate  speech  could  enable  outreach  programs that attempt to 
prevent an escalation from speech to action. Sites such as Twitter and Facebook have been seeking  to  actively  combat  hate  
speech. In spite of these reasons, NLP research on hate speech has been very limited, primarily due to the lack of a general 
definition of hate speech, an analysis of its demographic influences, and an investigation of the most effective features.



Data :
Our overall collection of tweets was split in the ratio of 65:35 into training and testing data. Out of the testing data, 
30% is public and the rest is private.



Evaluation Metric:
The metric used for evaluating the performance of classification model would be F1-Score.

True Positives (TP) - These are the correctly predicted positive values. 
True Negatives (TN) - These are the correctly predicted negative values.
False Positives (FP) – When actual class is no and predicted class is yes.
False Negatives (FN) – When actual class is yes but predicted class in no.
Precision = TP/TP+FP
Recall = TP/TP+FN
F1 Score = 2*(Recall * Precision) / (Recall + Precision)
F1 is usually more useful than accuracy, especially if for an uneven class distribution.



LeaderBoard Score : 0.67887323943662
Leaderboard : https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/my-submissions
