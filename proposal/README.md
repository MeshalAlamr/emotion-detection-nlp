## Project Proposal (Provisional)

This is the provisional project proposal for the unsupervised Natural Language Processing (NLP) project.
## Question / Need:
#### What is the framing question of your analysis, or the purpose of the model/system you plan to build? 

We plan to predict the user's mood using an input text in order to provide music, movie, and other recommendations based on the user's mood.

#### Who benefits from exploring this question or building this model/system?
The use cases of the planned model/system are numerous. For example, it could be used to help users get relevant movie and music recommendations. It could also be used to analyze customer reviews and categorize them by mood.

## Data Description:
#### What dataset(s) do you plan to use, and how will you obtain the data?

[Emotion Detection From Text](https://www.kaggle.com/pashupatigupta/emotion-detection-from-text) dataset on Kaggle. It provides 40,000 tweets labelled with one of 13 emotions which are: _empty, sadness, enthusiasm, neutral, worry, surprise, love, fun, hate, happiness, boredom, relief and anger_.

#### If modelling, what will you predict as your target?
- The sentiment column of the data that describes the mood.

## Tools:
#### How do you intend to meet the tools requirement of the project?
- Scikit-learn to perform unsupervised learning.
- Numpy and Pandas to perform data manipulation.
- NLTK and spaCY to perform text manipulation.

#### Are you planning in advance to need or use additional tools beyond those required?
- We plan to incorporate some additional APIs to get movies and music relevant to the predicted mood.

## MVP Goal:
The project's expected outcome is a mood predictor based on an input text. A report of the analysis and a presentation will also be provided.
