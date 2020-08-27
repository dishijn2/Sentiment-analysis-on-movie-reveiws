# Sentiment-analysis-on-movie-reveiws

Sentiment Analysis is an application of Natural Language Processing (NLP) which is used to find the sentiments of users‟ reviews, comments etc. on the internet. 
Nowadays, social websites like Facebook, Twitter are widely used for posting the users reviews about different things such as movies, news, food, fashion, politics and much more. 
Reviews and opinions play a major role in identifying the level of satisfaction of users regarding a particular entity. These are then used to find the polarity i.e. positive, negative and neutral. In this project, an approach to Sentiment Analysis on movie reviews is discussed.  

There are various research works which have used machine learning based approach for sentiment analysis on product reviews and it showed better results than lexical based approach. This project focuses around looking at the effectiveness of three AI strategies (Support Vector Machines (SVM), Naive Bayes (NB) and Maximum Entropy (ME)) for classiﬁcation of online surveys utilizing a web model utilizing regulated learning technique


![Sentiment-Analysis](https://user-images.githubusercontent.com/31739123/90477673-6f09d900-e149-11ea-96ef-c60eb566a5e2.jpg)

## Types of Sentiment Analysis
Sentiment analysis models focus on polarity (positive, negative, neutral) but also on feelings and emotions (angry, happy, sad, etc), and even on intentions (e.g. interested v. not interested).
### Fine-grained Sentiment Analysis
If polarity precision is important to your business, you might consider expanding your polarity categories to include:
* Very positive
* Positive
* Neutral
* Negative
* Very negative
This is usually referred to as fine-grained sentiment analysis, and could be used to interpret 5-star ratings in a review, for example:
Very Positive = 5 stars
Very Negative = 1 star

### Emotion detection
This type of sentiment analysis aims at detecting emotions, like happiness, frustration, anger, sadness, and so on. Many emotion detection systems use lexicons (i.e. lists of words and the emotions they convey) or complex machine learning algorithms.

One of the downsides of using lexicons is that people express emotions in different ways. Some words that typically express anger, like bad or kill (e.g. your product is so bad or your customer support is killing me) might also express happiness.

### Aspect-based Sentiment Analysis
Usually, when analyzing sentiments of texts, let’s say product reviews, you’ll want to know which particular aspects or features people are mentioning in a positive, neutral, or negative way. That's where aspect-based sentiment analysis can help, for example in this text: "The battery life of this camera is too short", an aspect-based classifier would be able to determine that the sentence expresses a negative opinion about the feature battery life.

### Multilingual sentiment analysis
Multilingual sentiment analysis can be difficult. It involves a lot of preprocessing and resources. Most of these resources are available online (e.g. sentiment lexicons), while others need to be created (e.g. translated corpora or noise detection algorithms).

## Sentiment Analysis Algorithms – How It Works?
Sentiment analysis uses various Natural Language Processing (NLP) methods and algorithms, they are: 

The main types of algorithms used include:

* **Rule-based systems** perform sentiment analysis based on a set of manually crafted rules.
These rules may include various techniques developed in computational linguistics, such as:

Stemming, tokenization, part-of-speech tagging and parsing.
Lexicons (i.e. lists of words and expressions).

* **Automatic systems** rely on machine learning techniques to learn from data.
1. The Training and Prediction Processes
2. Feature Extraction from Text
3. Classification Algorithms

* **Hybrid systems** combine both rule-based and automatic approaches.

### Sentiment Analysis Challenges

* Subjectivity and Tone
e.g. The package is red  (can be positive or neutral or negative)
* Context and Polarity
e.g. What did you dislike about the event? 
and someone reply "Absolutely nothing". 
* Irony and Sarcasm
e.g. Not one, but many!
* Comparisons
e.g. This is better than older tools.

### Sentiment analysis applications:

* Social media monitoring
* Brand monitoring
* Voice of customer (VoC)
* Customer service
* Market research
