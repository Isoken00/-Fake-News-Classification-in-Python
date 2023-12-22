# Fake-News-Classification-in-Python

### NLP and Deep Learning For Fake News Classification in Python

## Project Overview

What is Fake News?

The purposeful presenting of (usually) incorrect or misleading statements as news, where the assertions are deceptive by design, is known as fake news.
How did digital media and news evolve?
Newspapers, tabloids, and magazines gave way to digital news platforms, blogs, social media feeds, and a plethora of news mobile apps. News organizations profited from the increasing usage of social media and mobile platforms by offering their subscribers up-to-date news almost instantly. Customers can now more easily obtain the most recent news at their fingertips. Therefore, the ease with which these digital media platforms can be accessed by everyone and their capacity to facilitate user discussion and idea sharing as well as debate about topics like such as democracy, education, health, research and history.
Apart from this benefit, however, false or fake news pieces are becoming more and more prevalent on digital platforms. They are primarily used negatively for their own gain, including financial and political gain, the creation of prejudiced attitudes, the manipulation of mindsets, and the dissemination of ridiculousness.

### How big is the problem?

Anyone can disseminate false and biased information due to the quick uptake of the Internet, social media, and digital platforms (like Facebook, Twitter, news portals, or other social media). It is difficult to stop the creation of fake news. The past ten years have seen a sharp rise in the dissemination of fake news, which now affects a wide range of topics including politics, sports, health, history, entertainment, and science and research. Consider the 2016 US presidential election, which was heavily influenced by the publication of false and slanted news. Another example would be COVID-19. Every day, we typically encounter a lot of false or misleading information that could have major repercussions, incite panic among the populace, and hasten the spread of the epidemic.

As a result, it's critical to recognize and distinguish between fake and legitimate news. One approach is to assess each piece of news by an expert and fact-checker, but this takes time and involves expertise that is not transferable. Second, by utilizing machine learning and artificial intelligence tools, we can automate the detection of fake news. While there are many different unstructured format data types (such documents, films, and audios) in online news material, we will focus on text format news here. Natural language processing has advanced to the point where we can now recognize when an article or statement is false or misleading.
The goal of this field's extensive research and experimentation is to identify fake news across all media (text, audio, and video).

### Description of Data

In my study, I employed the Kaggle Fake News dataset to apply the Deep Learning Technique Sequence to Sequence programming to identify news stories that lacked credibility as fake news.

A full training dataset with the following attributes

id : unique id for a news article

title: the title of a news article 

author: author of the news article 

text : the text of the article; could be incomplete
 
label : a label that marks the article as potentially unreliable

1 : unreliable

0 : reliable

Tech Stack

Language : Python

Libraries : Scikit-learn , Tensorflow , Keras, Glove, nltk, pandas, numpy

## Table of content:

Understanding the problem statement

Understanding the Sequence problem and their types

Understanding Sequence neural network approach like: RNN, GRU and LSTM

Importing the dataset and importing libraries

Performing basic text cleaning

Perform text preprocessing: Stop word removal, Stemming etc

Text tokenization using keras tokenizer

Sequence data preparation with tokenizer and padding

Train and test split for model validation

Explaining Text vectorization and Word embedding

Build Word embedding layer with Glove

Important parameter before train model

Explaining Sequence model steps

Implementing Simple RNN

Implementing LSTM and GRU

Making Test predictions using the trained model

Comparing Model training and validation loss and performance

Comparing LSTM and GRU performance and computation Time

