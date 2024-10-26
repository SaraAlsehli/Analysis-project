Simplified explanation :

It is (Sentiment Analysis) on Twitter tweets about airlines, where tweets are classified into sentiments such as (positive, negative, and neutral), It relies on text classification to determine users' feelings toward a particular company or service , This analysis can help airlines understand the level of customer satisfaction and identify common issues they face, and thus improve their services based on negative tweets and appreciation of positive feedback.

•  Dataset:
It's based on data from the Kaggle Twitter Airline Sentiment collection, which contains Twitter tweets related to users' experiences with airlines.
The data set includes multiple columns, including the tweet itself, the airline, and the type of sentiment (positive, negative, neutral), in addition to other columns that may be useful for deeper analysis.

•  Model:
- The basic model used is (Naive Bayes), specifically Complement Naive Bayes, which is effective in processing text classification especially when there is imbalanced data.
- (Logistic Regression): To analyze texts
  
•  data preprocessing steps:
- Data Cleaning: Removing useless links, numbers, and tags from texts.
- Remove stop words: Such as common unimportant words (such as "the", "and") using nltk library.
- Segmentation and Rooting: Using nltk to divide text into words and retrieve roots.
- Create a word cloud  (WordCloud): to visualize the most common words in tweets and identify key terms that are frequently used.


   ● Colab link:
https://colab.research.google.com/drive/1r-p5--sQ1Y1xE43kIs7KCGR51pR683W1

