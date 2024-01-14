# Stock-Sentiment
### Predicting Market Behaviour From Tweets

1. Project Objective

--- 

“Over time, major indexes go up and down based on internal and external factors. Performance like that excites investors, but typically in opposite ways. Constant gains lead some investors to expect more of the same. Others worry the good times are surely about to end. The former sentiment is sometimes called “bearish,” while the latter is referred to as “bullish.”1
The goal of this project is to develop an NLP model capable of predicting Market sentiment based on tweets. In summary, with the NLP techniques you have learned during class, you must implement a classifier that receives tweets as inputs and is able to predict, for each tweet, if it describes a Bearish (0), Bullish (1), or Neutral (2) attitude.
The project has been developed using python 3 and libraries such as NLTK and Scikit Learn. Also, the project is simple and can be solved in various ways, which means there is no exact correct solution.

2. Corpora

---

The data is divided in a file for training “train.csv”, and another file for testing “test.csv”:
•
Train (9543 lines): Presents the tweets (“text”) and the sentiment label (“label”). Each tweet can have one of the following labels: Bearish (0), Bullish (1), or Neutral (2). You can divide this set in Train/Validation.
•
Test (299 lines): The structure of these dataset is the same as the train set, except that it does not contain the “label” column. You are expected to provide the predicted status (0, 1 or 2) for each tweet in this set and we will compare your predictions with the actual (true) labels.


