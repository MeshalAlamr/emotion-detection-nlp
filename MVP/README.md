## Minimum Viable Product (MVP) of the Unsupervised Natural Language Processing Project
One of the project's objectives is to detect emotion from written text.

The dataset for this project is the [Emotion Detection from Text](https://www.kaggle.com/pashupatigupta/emotion-detection-from-text) on Kaggle, 
it contains 40,000 tweets with their tweet_id and the associated emotions.

The data originally has 13 emotions which are: _empty, sadness, enthusiasm, neutral, worry, surprise, love, fun, hate, happiness, boredom, relief and anger_.

We started off by doing some exploratory data analysis (EDA). 

The table below describes the number of tweets in the dataset for each emotion:

| Emotion | Number of Tweets |
|:---|:---:|
| neutral         |8638|
| worry      |8459|
| happiness         |5209|
| sadness         |5165|
| love      |3842|
| surprise      |2187|
| fun       |1776|
| relief      |1526|
| hate    |1323|
| empty      | 827|
| enthusiasm       | 759|
| boredom          | 179|
| anger     | 110|

The figure below gives a visualization of the table:

<img width="300" height = "400" alt="Screen Shot 2021-11-08 at 1 55 26 PM" src="https://user-images.githubusercontent.com/80189295/140731999-1af95e4e-7689-48f5-aa79-07d7b54ac92a.png">


"Neurtal" and "Worry" are the most frequent emotions in the dataset as they compose ~21% of the data each. 
Additionally, We can see a clear imbalance in the classes, therefore, one of the solutions is to select the top 5 emotions in terms of tweet count.

The figure below shows the visualization after selecting the top 5 emotions:

<img width="300" height = "400" alt="Screen Shot 2021-11-08 at 1 56 40 PM" src="https://user-images.githubusercontent.com/80189295/140732242-a037de9c-7d73-4315-b4aa-eb4993f7d30f.png">

As we can see, the classes are much more balanced now.


Afterwards, we did more analysis for the top 5 emotions and found out that:
- Most of the tweets have around 45 characters.
- The most frequent token length is around 10.

Currently, wer're in the midst of text pre-processing and model development.
