Task1:  Naive Bayes Classifier


Simplified explanation :

Analyzing and classifying breast cancer-related data using the Breast Cancer Wisconsin (Diagnostic) dataset.
Classification of tumors into benign or malignant using data on diagnostic characteristics of tumors, and aims to build a model that can predict the type of tumor based on a set of features.

•  Dataset:
The data includes information about cancer cells, such as various measurements of the shape and size of the cells.
   The data set contains several columns, including (diagnosis), which indicates whether the tumor is benign or malignant.

•  Model:
The model used is (Gaussian Naive Bayes), which is a type of "Naive Bayes" algorithm designed to deal with data that follows a normal (Gaussian) distribution. 

Gaussian Naive Bayes was chosen to classify the tumor as (benign or malignant) based on cell characteristics, such as size and shape.

•  data preprocessing steps:

1- Data cleaning: Remove unnecessary columns such as "Unnamed: 32" and "id."

2- Data Splitting: Separating the data set into a training and testing set to verify the efficiency of the model.


● Colab link:
https://colab.research.google.com/drive/1cDO_yiKZxA7TdqrKW2zJepRF-wP74l6C

----------------------------------------------------------------------------------------------------------------------------------------------------













Task2: Market Basket Analysis 

Simplified explanation :

It is a data analysis related to purchases on the “Instacart” platform, where users’ behavior in shopping for products online is analyzed. 
Frequently purchased products
Times when orders are made (such as morning, evening, or weekdays).
Buying habits such as the products users prefer and their purchasing patterns.
The primary goal is to understand customer preferences and purchasing behavior to improve recommendations and user experience on the shopping platform.

•  Dataset:

 It includes multiple files such as "aisles," "departments," "order_products," "orders," and "products." These files provide details about products, departments, product categories, as well as order and purchase details.
In the initial steps, libraries like pandas, seaborn, and matplotlib are used for data visualization. This includes displaying top-selling products through charts.

•  Model:

The "Apriori" model from mlxtend.frequent_patterns is employed to extract association rules, revealing product combinations frequently purchased together.
 The data is transformed into a matrix format using TransactionEncoder, enabling its application in the Apriori model.

•  data preprocessing steps:

  1- Product Filtering: Selecting top-selling products and filtering the data to retain only frequently purchased items.
  
  2- Data Transformation: Using TransactionEncoder to convert product data within orders into a binary matrix, allowing for the application of the Apriori model.
  
  3- Rule Filtering: After extracting association rules, the results are filtered based on confidence and lift values.

  ● Colab link:
https://colab.research.google.com/drive/1eoIVGWZJWJ3vid0xPUdn1mciNo5_IuV0

----------------------------------------------------------------------------------------------------------------------------------------------------

Task3: Text Analysis 

Simplified explanation :

It is (Sentiment Analysis) on Twitter tweets about airlines, where tweets are classified into sentiments such as (positive, negative, and neutral), It relies on text classification to determine users' feelings toward a particular company or service , This analysis can help airlines understand the level of customer satisfaction and identify common issues they face, and thus improve their services based on negative tweets and appreciation of positive feedback.

•  Dataset:

It's based on data from the Kaggle Twitter Airline Sentiment collection, which contains Twitter tweets related to users' experiences with airlines.
The data set includes multiple columns, including the tweet itself, the airline, and the type of sentiment (positive, negative, neutral), in addition to other columns that may be useful for deeper analysis.

•  Model:

- The basic model used is (Naive Bayes), specifically Complement Naive Bayes, which is effective in processing text classification especially when there is imbalanced data.
  
- (Logistic Regression): To analyze texts
  
•  data preprocessing steps:

   1- Data Cleaning: Removing useless links, numbers, and tags from texts.
   
   2- Remove stop words: Such as common unimportant words (such as "the", "and") using nltk library.
   
   3- Segmentation and Rooting: Using nltk to divide text into words and retrieve roots.
   
   4- Create a word cloud  (WordCloud): to visualize the most common words in tweets and identify key terms that are frequently used.

● Colab link:
https://colab.research.google.com/drive/1r-p5--sQ1Y1xE43kIs7KCGR51pR683W1
