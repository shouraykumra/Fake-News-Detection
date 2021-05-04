# Fake-News-Detection

Table of Contents -
Report : [Link](https://sites.google.com/umbc.edu/data606/spring-21-section-1/shouray-kumra?authuser=0)

Presentation Phase 1 : [Link](https://drive.google.com/file/d/1gkzsql6sEvIKG8IKxOtjIo0Imr-17pnS/view)

Presentation Phase 2 : [Link](https://docs.google.com/presentation/d/1D0WImljStMJtZGW57jSiaunvYSHhVbUPDxPAuYidK5U/present?slide=id.gd08ca7ebb8_7_0)

Presentation Phase 3 : [Link](https://docs.google.com/presentation/d/17Bd7tDjzPNr2ZX4XkMFJwC47sL3rPcC1PRsnuf5k-14/edit?usp=sharing)

# Intoduction

The accelerated increase in fake news in online social network which is assessable to every single person worldwide in just one click has led to change in the way the information is absorbed, the allurement towards social media news has made a significant amount of news being broadcast. People are witnessing hate crimes all over the world due to acceptance of false and fraudulent information, on the other hand, there is no claim to that falsified information. The arguable published news is being propagated, people use social media to spread fake news selfishly for their profits, benefits and entertainment. This influences ideology of people, which lead to change in views or hatred among people of different culture.
 
With increase of social media fake news can be spread faster than a forest fire, the driving factor for this false information is not newspapers but new traditions like Facebook, Instagram, YouTube, podcast, etc. Evening knowing about these problems, to track down each news or piece of information is very difficult since the language used is hard to be understood by any method, we have to detect the fake news, because the language is never stable but changes person to person. Therefore, many machine learning algorithms fail due to this constraint. 
With this project I aim to determine which news is fake by applying classification techniques, the initial steps include cleaning of data, applying natural language processing, topic modelling and EDA.

# About the data
The dataset I am using was acquired from IEEE Data Port available at https://ieee-dataport.org/open-access/fnid-fake-news-inference-dataset. The dataset includes 15212 training samples, 1058 validation samples, and 1054 test samples. 

## The DataSet columns:

id: matches the id in the PolitiFact website API (unique for each sample)

date: The time each article was published in the PolitiFact website

speaker: The person or organization to whom the Statement relates

statement: A claim published in the media by a person or an organization and has been investigated in the PolitiFact article.

sources: The sources used to analyze each Statement

paragraph_based_content: content stored as paragraphed in a list

fullText_based_content: Full text using pasted paragraphs

label: The class for each sample

# Method

I am planning to build fake news detection system using data processing, supervised machine learning and deep learning models. 
1. Data preprocessing – using NLP techniques to prepare the data for next phase, preprocessing steps are as followed:

a.     Tokenized input

b.     Stemming

c.     Text cleaning

d.     Final preprocessed text

2. Supervised machine learning model – to build the detection system I will start with basic machine learning approaches like Linear Regression, support vector machine. The result from the proposed machine learning approach is studied using TF-IDF.

3. Deep learning models – with believe that above mentioned supervised machine learning techniques will give a good result, I will try to experiment the dataset with deep learning model.

a.     LSTM – LSTM will be used with an idea that it might solve the long term dependency problem.

b.     CNN – the model will consist of an embedding layer, a convolution layer with 3 convolutions, a max-pooling layer, and a fully connected network.

# Results

1. LinearSVC - accuracy (67.36%)	

2. Logistic Regression - accuracy (68.31%)

3. Decision Tree - accuracy (61.10)	

4. MultinomialNB - accuracy (71.82%)

5. CNN1D - accuracy (61.52%)

6. LSTM - accuracy (50.37%)


# Project Information and Software Requirements
Capstone Project - Shouray Kumra

Languages : Python 2.7

Tools/IDE : Google Collaboratory
